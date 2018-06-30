# Simple OAuth2 in Browser

This package is [version 1.6.0 of simple-oauth2](https://github.com/lelylan/simple-oauth2/tree/1.6.0) with some small changes to make it more easily webpacked for browser applications:

* source code is moved into `lib` subdir
* dependency `joi` is replaced with `joi-browser`
* dependency `@babel/polyfill` is added and required
* several babel packages are added as a dev dependencies
* `package.json` is updated to transpile `lib` to `dist` on "prepare"
* `package.json` is updated to point package at transpiled `dist/index.js`
* this version of the repo is published as `simple-oauth2-browser`

The [original repo](https://github.com/lelylan/simple-oauth2) is authored by [Andrea Reginato](http://twitter.com/lelylan) with contributions from [Jonathan Samines](http://twitter.com/jonathansamines) and licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0). The changes described above were made by [Joe Soap](https://github.com/soapsropes). As a derivative work, this repo uses the same license.
