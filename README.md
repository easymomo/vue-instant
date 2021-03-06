# vue-instant

[![npm](https://img.shields.io/npm/v/vue-instant.svg) ![npm](https://img.shields.io/npm/dm/vue-instant.svg)](https://www.npmjs.com/package/vue-instant)
[![vue2](https://img.shields.io/badge/vue-2.x-brightgreen.svg)](https://vuejs.org/)

vue instant allows you to easily create search controls with auto suggest for your vue application.
## Table of contents

- [Example](#example)
- [Installation](#installation)
- [Usage](#usage)

# Example
https://santiblanko.github.io/vue-instant


# Installation

```
npm install --save vue-instant
```

## Default import

Install all the components:

```javascript
import Vue from 'vue'
import VueInstant from 'vue-instant'

Vue.use(VueInstant)
```

**⚠️ A css file is included when importing the package. You may have to setup your bundler to embed the css in your page.**

## Distribution import

Install all the components:

```javascript
import 'vue-instant/dist/vue-instant.css'
import VueInstant from 'vue-instant/dist/vue-instant.common'

Vue.use(VueInstant)
```
**⚠️ You may have to setup your bundler to embed the css file in your page.**

## Browser

```html
<link rel="stylesheet" href="vue-instant/dist/vue-instant.css"/>

<script src="vue.js"></script>
<script src="vue-instant/dist/vue-instant.browser.js"></script>
```

The plugin should be auto-installed. If not, you can install it manually with the instructions below.

Install all the components:

```javascript
Vue.use(VueInstant)
```

## Source import

Install all the components:

```javascript
import Vue from 'vue'
import VueInstant from 'vue-instant/src'

Vue.use(VueInstant)
```

**⚠️ You need to configure your bundler to compile `.vue` files.** More info [in the official documentation](https://vuejs.org/v2/guide/single-file-components.html).

## License

MIT © [Santiago Blanco](http://twitter.com/santiblanko)
