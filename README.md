# Wallaby.js

**To get wallaby.js working** with angular2-webpack-starter, you'll need to do the following:
- Add the [wallaby.js config file](https://github.com/wallabyjs/angular2-webpack-starter/blob/master/wallaby.js) to the project.
- [Move](https://github.com/wallabyjs/angular2-webpack-starter/blob/master/config/spec-bundle.js#L41) karma specific hack to a [separate file](https://github.com/wallabyjs/angular2-webpack-starter/blob/master/config/karma-require.js) called `karma-require.js`.
- Run `npm install wallaby-webpack angular2-template-loader null-loader --save-dev`.
