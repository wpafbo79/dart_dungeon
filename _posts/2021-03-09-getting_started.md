---
layout: post
title: Getting Started
author: Theron E. Weimer, Jr.
updated: 2021-03-10 11:53:00 -0500
---
## Background

I found the [documentation](https://dart.dev/tutorials) for [getting started](https://dart.dev/tutorials/server/get-started) with Dart lacking in many ways.  Instead of providing a simple guide to setting up a Dart project, they direct you to the Dart playground, [DartPad](https://dartpad.dev/), which doesn't help at all with setting up a project so it can be versioned, packaged, and released.  Further down, they tell you how to get a CLI application working, but there isn't equivalent documentation for a web application.

However, [The Polyglot Developer](https://www.thepolyglotdeveloper.com/) was far more [useful](https://www.thepolyglotdeveloper.com/2019/04/building-simple-web-application-dart/).

## Create the Project

A combination of instructions between the official documentation and The Polyglot Developer.

1. Make sure Dart is installed.  In my case, on Windows:

    ```powershell
    choco install dart-sdk
    ```

1. Install the web development tool and verify it is working.

    ```shell
    pub global activate webdev
    webdev
    ```

1. Install Stagehand for scaffolding (not necessary in this case, but Stagehand does provide more scaffolding options beyond the default `dart create`) and verify it is working.

    ```shell
    pub global activate stagehand
    stagehand
    ````

1. Create a small app and update the dependencies.

    ```shell
    stagehand web-simple
    pub get
    ```

1. Serve the application locally.

    ```shell
    webdev serve
    ```

## Begin working with Dart

To begin learning about Dart and using the HTML Canvas, I did a quick workthrough of setting up the [Snake game](https://dart.academy/web-games-with-dart-and-the-html5-canvas/) on [Dart Academy](https://dart.academy/).

This is more involved that I needed, so once I covered the basics of the canvas and using Points to refrence position, I moved on to trying to get something working for this project.
