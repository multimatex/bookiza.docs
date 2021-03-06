---
layout: post
title:  "Preprocessors"
date:   2018-07-26 17:16:51 -0400
categories: bookiza templates new project
---

Customize bookiza according to your taste, make your book stand apart. Bookiza comes in multiple flavors: HAML, PUG, markdown, SASS, LESS, Stylus etc. 

There are two ways to configure bookiza for your book:

- Globally, using `.bookizarc`
- Locally, per project, using `.bookrc`

For example, this [sample book](https://github.com/marvindanig/bookiza-framework) uses `.haml` and `.scss` instead of plain html and css.

Configuring bookiza will set its `generators` and `renderers` to use the appropriate templating engine (or preprocessor) for its pages (and templates). You can also use a combination of preprocessors within the same book with a more complicated setup (discussed elsewhere). 

By default Bookiza is configured for the native web i.e. plain HTML, CSS and JavaScript. The output of the build is always HTML, CSS and JavaScript as well no matter what preprocessor logic or transformations are applied beforehand. 
