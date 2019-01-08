# Sass Maps Next

[![](https://img.shields.io/travis/lunelson/sass-maps-next.svg?style=flat-square)](#travis)
[![](https://img.shields.io/npm/v/@lunelson/sass-maps-next.svg?style=flat-square)](#releases)
[![](https://img.shields.io/github/license/lunelson/sass-maps-next.svg?style=flat-square)](#license)

These functions enable `get`, `set` and `merge` operations on nested values in Sass' `map` data type. They provide a `map-set` function, while patching Sass' native `map-get` and `map-merge` functions to work with nested values. The API of these functions corresponds to [this informal proposal](https://github.com/sass/sass/issues/1739#issuecomment-122435753) at the sass repo.

Some additional utility functions are also provided.

They are fully tested, and compatible with current versions of [libsass](https://github.com/sass/libsass) and [dart-sass](https://github.com/sass/dart-sass).

## Installation
```sh
# in your project

npm install --save @lunelson/sass-maps-next
```
```scss
// in your sass file, assuming you have 'node_modules' in Sass' search path

@import '@lunelson/sass-maps-next/index';

// ...now you have access to nested map-get, map-merge and map-set
```
