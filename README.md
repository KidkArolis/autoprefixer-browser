# autoprefixer-browser

A browserified version of autoprefixer for running in the browser.

## Usage

`autoprefixer.js` is the browserify output, require that in the browser and do the usual

```
var prefixed = require("autoprefixer").process(css).css;
```

## Generate updated version

Update package.json, npm install and run `npm run make`.