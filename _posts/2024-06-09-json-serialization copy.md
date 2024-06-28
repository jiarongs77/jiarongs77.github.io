---
layout: post
title:  "Set Up JSON Serialization"
date:   2024-06-09 13:50:00 -0700
categories: Github page
---

The steps of [JSON serialization set up](https://docs.flutter.dev/data-and-backend/serialization/json)

## Purpose
1. parse data from json string
2. convert model to json

## How
[Add dependencies](https://pub.dev/packages/json_serializable)

## Create build-runner.sh

- add: 
> dart run build_runner build watch --delete-conflicting-outputs

- it will generate .g. file





