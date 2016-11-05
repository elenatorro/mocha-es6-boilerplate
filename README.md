# Mocha + ES6 + Gulp + Browserify Boilerplate

This is a boilerplate to create fast testing environment using ES6, with a setup which enables front end testing by running a local server.

## Installation

```
 npm install
```

## Folder structure

```
 |- lib/
 |--- my-library.js // your library main files
 |- test/
 |--- test.my-library.js // your test file
```

## Test in the browser

Run `gulp watch` to compile your project and your tests. Open `localhost:8080` and your tests will be running there.

![gulp-watch screenshot](/screenshots/screenshot-gulp-watch.png)

![mocha test screenshot](/screenshots/screenshot-browser.png)

## Test in the console

Run `npm test` and you'll see the results in your console.

![npm test screenshot](/screenshots/screenshot-npm-test.png)

## Bibliography

* [Building ES6 Javascript for the Browser with Gulp, Babel, and More](https://thesocietea.org/2016/01/building-es6-javascript-for-the-browser-with-gulp-babel-and-more/)
* [ES6 + browserify + babel + gulp + jasmine - Carlos Blé](http://www.carlosble.com/2015/09/es6-browserify-babel-gulp-jasmine/)
