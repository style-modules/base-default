style-modules/base-default
==========================

[![License][license-image]][license-link]
[![Version][version-image]][version-link]
[![Build Status][build-image]][build-link]
[![Gitter][gitter-image]][gitter-link]

> The Default Base for Style Modules

## Getting Started

### Include via RawGit
Add this to the `<head>` your HTML file
```html
<link rel="stylesheet" href="https://cdn.rawgit.com/style-modules/base-default/0.1.0/base-default.css" />
```
*`base-default` must come before any other style-modules packages*

### Add to your project with Git
```shell
mkdir dependencies
cd dependencies
git clone https://github.com/style-modules/base-default.git
git checkout 0.1.0
```

Then add this to the `<head>` your HTML file
```html
<link rel="stylesheet" href="dependencies/base-default/base-default.css" />
```
*`base-default` must come before any other style-modules packages*

### Install via NPM
```shell
npm install --save style-modules/base-default#0.1.0
```
Or if using yarn
```shell
yarn add style-modules/base-default#0.1.0
```

Then add this to the `<head>` your HTML file
```html
<link rel="stylesheet" href="node_modules/base-default/base-default.css" />
```
*`base-default` must come before any other style-modules packages*

[license-image]: https://img.shields.io/github/license/style-modules/base-default.svg
[license-link]: https://github.com/style-modules/base-default/blob/master/LICENSE
[version-image]: https://img.shields.io/github/release/style-modules/base-default.svg
[version-link]: https://github.com/style-modules/base-default/releases
[build-image]:https://travis-ci.org/style-modules/base-default.svg?branch=master
[build-link]: https://travis-ci.org/style-modules/base-default
[gitter-image]: https://badges.gitter.im/style-modules.svg
[gitter-link]: https://gitter.im/style-modules
