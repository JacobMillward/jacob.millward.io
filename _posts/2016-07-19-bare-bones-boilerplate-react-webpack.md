---
layout: post
title: Bare-bones boilerplate for React and webpack projects
comments: true
---

### **tldr; [Here it is.]({{site.github_url}}/react-starter)**


In my endeavours to get to grips with front-end JS development, I did some research and decided to launch into learning [React](https://facebook.github.io/react) by Facebook. This in turn introduced me to the huge complicated mess that is *front-end tooling*.

A lot of React tutorials and documentation requires that you use [webpack](https://webpack.github.io), so that's my module loader chosen for me. I didn't fancy using webpack to manage my non-JS assets ([although you can](https://webpack.github.io/docs/using-loaders.html)) so I decided to use [Gulp](http://gulpjs.com) to fill in the gaps.

An hour of looking at documentation later, I produced a [relatively bare-bones boilerplate project]({{site.github_url}}/react-starter). The readme goes over the details but essentially run the following command to install the dependancies.

``` bash
npm install
```
That's it.

Then just run `gulp` to build it all! I've also included a gulp task to start webpack-dev-server and allow it to hot-load changes to your JS/JSX. Just run `gulp webpack-server` and it will load up the server and compile your changes on the fly.

If you have any suggestions or improvements let me know, I'm new to this!
