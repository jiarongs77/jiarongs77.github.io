---
layout: post
title:  "Create a site by using Github Page"
date:   2023-03-09 13:50:00 -0700
categories: Github page
---

This site is created by following the steps in [GitHub Pages](https://docs.github.com/en/pages).

## Publish iniital site
Step 1: Create a repository with name: `username.github.io`, username is your Github username.

Step 2: Create a file named `index.md` in the repository and commit the change.

Step 3: publish the site by following [Configure publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

Once you commit the change, the site will be published. You should be able to see the site at `https://username.github.io`.

Step 4: remove the `index.md` file, this will allow following steps in **Customize site with Jekyll** section below to create a site with Jekyll, e.g. run `jekyll new --skip-bundle .` in the repository.

## Customize site with Jekyll
Step 5: create site with Jekyll by following [Creating a GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)

- Set up Jekyll on macOS: [Installing Jekyll on macOS](https://jekyllrb.com/docs/installation/macos/)
- Generate a new Jekyll site: `jekyll new --skip-bundle .`, make sure to remove index.md or index.html file in the repository first.
- Run `bundle install` to install the dependencies.
- Run `bundle exec jekyll serve` to start the server.
- Check the site at `http://127.0.0.1:4000/`

Step 6: commit the change and publish the site.

If you want to add more content or theme, you can follow the steps in [Set up site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).
