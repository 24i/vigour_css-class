# css-class

[![Build Status](https://api.travis-ci.org/vigour-io/css-class.svg)](https://travis-ci.org/vigour-io/css-class)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)
[![npm (scoped)](https://img.shields.io/npm/v/@vigour-io/css-class.svg)](https://github.com/vigour-io/css-class)

Reusable CSS classes for Vigour apps

## Getting started

### Install it:
```shell
npm i @vigour-io/css-class --save
```

### Require it:
```js
require('@vigour-io/css-class')
```

### Use it:
```js
const render = require('brisky/render')

const app = {
  element: {
    class: 'flex-grid full-absolute'
  }
}

document.body.appendChild(render(element))
```

## Available classes:

```
.flex-column
.flex-grid
.flex-row
.full-absolute
.full-fixed
.inline-row
.justify-center
.scroll-x
.scroll-y
.transform-03s
```