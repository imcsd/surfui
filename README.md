# Surf UI

Surf UI is aimed at  being an lightweight, flexible, and responsive CSS framework, it's fork from bootstrap and simplify bootstrap.

Surf UI support HTML page, MVVM framework (like React, Vue and AngularJS) and WeChat Mini Progran (WXSS).

Surf UI is used for the same API (class name) as bootstrap and the following functions/components have been removed:

- All JavaScript function and plugins
- carousel
- custom-forms
- popover

In addition, the core version of Surf UI also removed the following component:

- nav
- navbar
- card
- pagination
- jumbotron
- alert
- media
- toasts
- modal
- tooltip

Surf UI is used for the same API (class name) as bootstrap, meanwhile you can learn Surf UI by reading the [Bootstrap official document](https://getbootstrap.com/docs/4.5/layout/overview/).




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
@import "surfui/dist/surfui.css";
```

Or import the core version:

```css
@import "surfui/dist/surfui.core.css";
```

### Build

Clone Surf UI source code to customize your own UI framework, then build it to CSS file:

```sh
npm run build
```

Then the target CSS will output in `dist` directory.

