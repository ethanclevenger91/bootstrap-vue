[![CircleCI branch](https://img.shields.io/circleci/project/github/bootstrap-vue/bootstrap-vue/master.svg?style=flat-square)]()
[![npm](https://img.shields.io/npm/dt/bootstrap-vue.svg?style=flat-square)]()
[![npm](https://img.shields.io/npm/v/bootstrap-vue.svg?style=flat-square)]()
[![npm](https://img.shields.io/npm/l/bootstrap-vue.svg?style=flat-square)]()
[![deps](https://img.shields.io/david/dev/bootstrap-vue/bootstrap-vue.svg)]()

# Bootstrap Vue
[Twitter Bootstrap 4](https://v4-alpha.getbootstrap.com/) components for [Vue.js 2](https://vuejs.org/)

<p align="center"><img src="https://github.com/bootstrap-vue/bootstrap-vue/raw/master/banner.png"></p>

# Getting started
Please head to [Official Docs Website](https://bootstrap-vue.github.io) for setup guide, examples and more docs.

# Current included stable components

- Alerts
- Breadcrumb
- Buttons
- Button group
- Dropdowns
- Form Inputs
- Form Radio
- Form Checkbox
- Form Select
- Nav
- NavBar
- Pagination
- Tables (with pagination and custom rendering support)

Actually [many more components](https://github.com/bootstrap-vue/bootstrap-vue/tree/master/components) are also implemented, but they are still under development, so if you relly need them, feel free to explore and use and making pull requestes so anyone else can use them earlier ;)

# Supported versions
Both vue 2 and bootstrap 4 are changing so fast, specially bootstrap 4 is still in *alpha* stage. We keep trying to stay up to date with latest changes. currently this versions are officially tested and supported:

Package   | Compatible Version
----------|---------------------
Vue js        | 2.1.7
Bootstrap | 4.0.0-alpha.5
Webpack   | 2.2.0-rc.2

```js
import Vue from 'vue'
import BootstrapVue from 'bootstrap-vue';

// Globally register bootstrap-vue components
Vue.use(BootstrapVue);
```

Or simply include js inside HTML templates: (CDN Powered by unpkg)

```html
<script src="https://unpkg.com/bootstrap-vue/dist/bootstrapVue.js"></script>
```

## Bootstrap CSS

Because Bootstrap can be customized so heavily, this package does not include the Bootstrap CSS. You can load the bootstrap@4.0.0-alpha.5 CSS in several ways:
* [Via CDN](https://v4-alpha.getbootstrap.com/getting-started/introduction/#quick-start)
* Bundled with your own CSS
* [Via npm or yarn](https://v4-alpha.getbootstrap.com/getting-started/download/#npm), using the [webpack css loader](https://github.com/webpack/css-loader), and including like this:
```js
import 'path/to/node_modules/bootstrap/dist/css/bootstrap.css'
// OR
import 'path/to/node_modules/bootstrap/dist/css/bootstrap-flex.css'
```

## Docs
[Official Docs Website](https://bootstrap-vue.github.io/)

## Credits
+ This project and docs were originally ported from the Vue 1.x version
 [kzima/vuestrap-base-components](https://github.com/kzima/vuestrap-base-components)
 , so original credit backs to him :)
