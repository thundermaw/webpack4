# Webpack 4 Template for React, or anything else

### Features

* SCSS Compiler + Hot Reloading!
* Babel (ES6)
* React

### notes

I've also included the i18n plugin I use a lot for internationalization, i18n-next I've found to be really useful at adding multiple language support to an app.

Along with that formik (good library for signup forms), lodash & moment, react-helmet for adding meta tags on-the-fly to the page and superagent for ajax requests.

### SCSS hot-reload!

When you switch over to Webpack 4 you have to switch your css compiler to *mini-css-extract-plugin* as *extract-text-webpack-plugin* is no longer supported in 4.
However mini-css-extract-plugin doesn't support hot-reloading yet but you can do it style-loader so for development we use style-loader and building production mini-css-extract-plugin.

### And finally...

Feel free to fork and customize it to your needs, I'll endeavour to keep this as up-to-date as possible while I'm working on other projects.

If you see an error or something that could be improved, log an issue and I'll check it out or if you just need a hand getting it to run.

Enjoy,


John Griffiths
www.thundermaw.com

[contributing guideline](https://github.com/thundermaw/webpack4/issues/2)
