# Surf UI

Surf UI is aimed at  being an lightweight, flexible, and responsive CSS framework, it's fork from bootstrap and simplify bootstrap.

Surf UI support HTML page, MVVM framework (like React, Vue and AngularJS) and WeChat Mini Progran (WXSS).

Surf UI is used for the same API (class name) as bootstrap and the following functions/components have been removed:

- All JavaScript function and plugins
- carousel

- popover

Surf UI is used for the same API (class name) as bootstrap, meanwhile you can learn Surf UI by reading the [Bootstrap official document](https://getbootstrap.com/docs/4.5/layout/overview/).




## Quick start

### Direct Include

You can copy the file `dist/surfui.css` to your web page project and link it to you HTML file directly

```
<link rel="stylesheet" href="./dist/surfui.css">
```

### NPM Install and Import

Install Surf UI to your project

```sh
npm install -S surfui
```

Import `surfui.css` into your project main CSS file:

```
@import "surfui/dist/surfui.css";
```

### Build

Clone Surf UI source code to customize your own UI framework, then build it to CSS file:

```
npm run build
```

Then the target CSS will output in `dist` directory.

