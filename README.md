# Surf UI

Surf UI is aimed at  being an lightweight, flexible, and responsive CSS framework, it's fork from bootstrap and simplify bootstrap.

Surf UI support HTML page, MVVM framework (like React, Vue and AngularJS) and WeChat Mini Progran (WXSS).

Surf UI is used for the same API (class name) as bootstrap, meanwhile you can learn Surf UI by reading the [Bootstrap official document](https://getbootstrap.com/docs/4.5/layout/overview/).



### Version comparison

#### Component

| component        | bootstrap | surfui | core | mp | base   |
| ---------------- | --------- | ------ | ---- | ---- | ---- |
| jQuery Functions | √         | ✕     | ✕  | ✕    | ✕   |
|carousel| √ | ✕ | ✕ | ✕ | ✕ |
|custom-forms| √ | ✕ | ✕ | ✕ | ✕ |
|popover| √ | ✕ | ✕ | ✕ | ✕ |
| nav| √ | √ | ✕ | ✕ | ✕ |
| navbar| √ | √ | ✕ | ✕ | ✕ |
| card| √ | √ | ✕ | ✕ | ✕ |
| pagination| √ | √ | ✕ | ✕ | ✕ |
| jumbotron| √ | √ | ✕ | ✕ | ✕ |
| alert| √ | √ | ✕ | ✕ | ✕ |
| media| √ | √ | ✕ | ✕ | ✕ |
| toasts| √ | √ | ✕ | ✕ | ✕ |
| modal| √ | √ | ✕ | ✕ | ✕ |
| tooltip| √ | √ | ✕ | ✕ | ✕ |
| type| √ | √ | ✕ | ✕ | ✕ |
| table| √ | √ | √ | ✕ | ✕ |
| transitions| √ | √ | √ | ✕ | ✕ |
| input-group| √ | √ | √ | ✕ | ✕ |
| close| √ | √ | √ | ✕ | ✕ |
| print| √ | √ | √ | ✕ | ✕ |
| buttons| √ | √ | √ | √ | ✕ |
| button-group| √ | √ | √ | √ | ✕ |
| utilities | √ | √ | √ | √ | √* |
| grid | √ | √ | √ | √ | √ |

#### Utilities

The core version of Utilities is different from the base version.

|  Utilitie | Full and core version | Base and mp version |
|  - | - | - |
|  align|√|✕|
|  embed|√|✕|
|  flex|✕|✕|
|  interactions|√|✕|
|  overflow|√|✕|
|  position|√|✕|
|  screenreaders|√|✕|
|  stretched-link|√|✕|
|  background|√|√|
|  borders|√|√|
|  clearfix|√|√|
|  display|√|√|
|  float|√|√|
|  shadows|√|√|
|  sizing|√|√|
|  spacing|√|√|
|  text|√|√|
|  visibility|√|√|



## Quick start

### Direct Include

You can copy the file `dist/surfui.css` to your web page project and link it to you HTML file directly

```html
<link rel="stylesheet" href="./dist/surfui.css">

<!-- Or link the compress version -->
<link rel="stylesheet" href="./dist/surfui.min.css">
```

Or link the core version:

```html
<link rel="stylesheet" href="./dist/surfui.core.css">

<!-- Or link the compress version -->
<link rel="stylesheet" href="./dist/surfui.core.min.css">
```

### NPM Install and Import

Install Surf UI to your project

```sh
npm install -S surfui
```

Import `surfui.css` into your project main CSS file:

```css
|  "surfui/dist/surfui.css
```

Or import the core version:

```css
|  "surfui/dist/surfui.core.css
```

### Build

Clone Surf UI source code to customize your own UI framework, then build it to CSS file:

```sh
# Build all version
npm run build

# Build Full version
npm run build-full

#Build core version
npm run build-core

# Build base version
npm run build-base

# Build mp(mini-program) version
npm run build-mp
```

Then the target CSS will output in `dist` directory.



## Change Log

##### V 1.2.1 2022-09-24

1. Fixed some base style problem of core, mini-program and base version.

##### V 1.2.0 2021-12-05

1. Add mini program version
2. Add base version

##### V 1.0.1 2021-06-22

1. Upgrade bootstrap to 4.6.0;
2. Remove list-group;
3. Remove utilities/flex;