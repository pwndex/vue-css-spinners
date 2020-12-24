<br>
<br>
<p align="center">
  <a href="https://github.com/pwndex/vue-css-spinners" target="_blank">
    <img width="200" src="https://user-images.githubusercontent.com/65390434/91702828-ba34da80-eb92-11ea-9064-92535e283b99.png" alt="logo">
  </a>
</p>
<br>
<br>
<br>

<p align="center">
  <a href="https://www.npmjs.com/package/vuespins">
    <img src="https://flat.badgen.net/npm/v/vuespins?color=green" alt="NPM Version" />
  </a>
  <a href="https://vuejs.org">
    <img src="https://flat.badgen.net/badge/icon/2.x?label=vue&color=green" alt="Vue Version" />
  </a>
  <a href="https://travis-ci.com/pwndex/vuespins">
    <img src="https://flat.badgen.net/travis/pwndex/vuespins?label=build" alt="Build Status" />
  </a>
  <a href="https://coveralls.io/github/pwndex/vuespins?branch=master">
    <img src="https://flat.badgen.net/coveralls/c/github/pwndex/vuespins" alt="Coverage Status" />
  </a>
  <a href="https://www.npmjs.com/package/vuespins">
    <img src="https://flat.badgen.net/npm/dt/vuespins?label=npm%20downloads" alt="NPM Downloads" />
  </a>
  <br>
  <a href="https://bundlephobia.com/result?p=vuespins@latest">
    <img src="https://flat.badgen.net/bundlephobia/min/vuespins?color=green" alt="Minified Size" />
  </a>
  <a href="https://bundlephobia.com/result?p=vuespins@latest">
    <img src="https://flat.badgen.net/bundlephobia/tree-shaking/vuespins" alt="Tree Shaking" />
  </a>
  <a href="https://github.com/pwndex/vuespins/blob/master/LICENSE">
    <img src="https://flat.badgen.net/github/license/pwndex/vuespins?color=green" alt="MIT License" />
  </a>
</p>
<br>

# Installation

### Demo

Browse components and explore their props with [Docs](https://pwndex.github.io/vuespins)

### Prerequisites

- [Nodejs](https://nodejs.org/en/)
- [Yarn Classic](https://classic.yarnpkg.com/en/)

### Quick Start

To install it, open up your terminal and run

```sh
npm install vuespins
# or yarn - whichever you prefer
yarn add vuespins
```

# Usage

### Browser

```html
<!-- Include after Vue -->
<!-- Local files -->
<script src="/node_modules/vuespins/dist/vuespins.min.js"></script>

<!-- CDN -->
<script src="https://unpkg.com/vuespins@latest/dist/vuespins.min.js"></script>
```

### Bundler (Webpack, Rollup)

```js
import Vue from 'vue'
import Vuespins from 'vuespins'

Vue.use(Vuespins)
```

### How to use it?

After above steps, simply use any spinners in your Vue components

```vue
<template>
  <div>
    // Basic Ring Spinner
    <Ring />

    // Custom Ring Spinner
    <Ring
      color="custom color"
      :size="custom size"
      :thickness="custom thickness"
    />
  </div>
</template>
```

Or you can import any spinner to your liking

```vue
<template>
  <div>
    // Basic Ring Spinner
    <CubeGrid />

    // Custom Ring Spinner
    <CubeGrid color="custom color" :size="custom size" />
  </div>
</template>
<script>
import { CubeGrid } from 'vuespins'

export default {
  name: 'app',
  components: {
    CubeGrid
  }
}
</script>
```

## Examples

You will find further demos under `/examples` folder

- [CDN](./examples/cdn)
- [Vue-CLI](./examples/vcli)

## Contributing

1. Fork it
2. Create your feature branch: **git checkout -b my-new-feature**
3. Commit your changes: **git commit -m "feat: add some feature"**
4. Push to the branch: **git push origin my-new-feature**
5. Submit a pull request

## Copyright

[MIT Licensed](https://github.com/pwndex/vuespins/blob/master/LICENSE) | Copyright © 2020 Amal' Greenberg
