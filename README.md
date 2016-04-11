# Basic Front-End template

This repo is meant to be used as a very basic starting point for new front-end
projects.

It uses npm scripts for automation, following the instructions in [Damen Bower's
guest post](https://css-tricks.com/why-npm-scripts/) on CSS-Tricks.

The scripts, listed in the [package.json](https://github.com/aehrmann/front-end-basic-template/blob/master/package.json)
file, run tasks that:

- compile SASS
- run the CSS through autoprefixer (using PostCSS)
- concatenate and uglify all js files
- watch for changes to css files
- watch for changes js files
- watch all files

