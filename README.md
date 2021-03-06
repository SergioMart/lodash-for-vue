# lodash-for-vue
[![npm version](https://img.shields.io/npm/v/lodash-for-vue.svg?style=flat)](https://www.npmjs.com/package/lodash-for-vue)
[![downloads](https://img.shields.io/npm/dm/lodash-for-vue.svg?style=flat)](https://www.npmjs.com/package/lodash-for-vue)

>A small wrapper for integrating [lodash](https://github.com/lodash/lodash#lodash-v4174) to [Vue.js](https://github.com/vuejs/vue)
(inspired by vue-axios plugin by imcvampire)

## How to install:
### CommonJS:
```
npm install lodash-for-vue --save
```

And in your entry file:
```
import Vue from 'vue'
import LodashForVue from 'lodash-for-vue'

Vue.use(LodashForVue)
```

### Script:
Just add 2 scripts in order: `vue` and `vue-lodash` to your `document`.

## Usage:
This wrapper bind `lodash` to `Vue` or `this` if you're using single file component.

You can `lodash` like this:
```
Vue.$lodash.random(20)

this.$lodash.random(20)
```
