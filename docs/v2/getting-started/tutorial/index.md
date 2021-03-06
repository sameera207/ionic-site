---
layout: v2_fluid/docs_base
category: getting-started
id: tutorial
subid: tutorial
title: Ionic 2 | Getting Started | Tutorial
header_title: Getting Started - Tutorial
header_sub_title: Ionic 2 Developer Preview
---

# Ionic 2 Tutorial

<a class="improve-docs" href='https://github.com/driftyco/ionic-site/edit/ionic2/docs/v2/getting-started/tutorial/index.md'>
  Improve this doc
</a>

Now that we have [Ionic and its dependencies installed](../installation), let's build our first app! This section will walk through the process of starting a new application, adding pages, navigating between those pages, and more. Let's get started!


## Starting a New Ionic 2 App

If you don't already have an app started from the [previous section](../installation), let's create a new app! Use the `start` command to initialize a new Ionic app. We specify that we want it to be an Ionic 2 app by passing in the `--v2` option.

```bash
$ ionic start MyIonic2Project https://github.com/driftyco/ionic2-starter-tutorial --v2
```

This will pull Ionic 2 down, install [npm modules](../../resources/what-is/#npm) for the application, and get [Cordova](../../resources/what-is/#cordova) set up and ready to go.

## Viewing the app in a browser
Let's `cd` in to the folder that was created. To get a quick preview of your app in the browser, use the `serve` command.

```bash
$ cd MyIonic2Project/
$ ionic serve
```

<img src="/img/docs/tutorial-screen.png" style="max-width: 320px">

You should see the welcome message shown above if everything was installed successfully.

In the next section, let's go over the project structure created by the `ionic start` command.


<a href="project-structure/" class="btn btn-primary">Project Structure</a>
