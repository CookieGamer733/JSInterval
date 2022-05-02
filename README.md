<div align="center">
  <img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/cookiegamer733/jsinterval/njsscan%20sarif">
  <img alt="Libraries.io dependency status for latest release" src="https://img.shields.io/librariesio/release/npm/ms">
  <img alt="jsDelivr hits (GitHub)" src="https://img.shields.io/jsdelivr/gh/hw/cookiegamer733/jsinterval">
  <img alt="npm" src="https://img.shields.io/npm/dw/jsinterval">
  <img alt="GitHub" src="https://img.shields.io/github/license/cookiegamer733/jsinterval">
  <img alt="npm" src="https://img.shields.io/npm/v/jsinterval">
</div>

# JSInterval

## Description

JSInterval is a JavaScript library that makes working with intervals easier. It has a simple API and can be used in both Node.js and the browser

## Installation

Install JSInterval with npm

```bash
  npm install jsinterval
```

## Features

- Works in both [Node.js](https://nodejs.org/) and in the browser
- Uses [ms](https://npmjs.com/package/ms/) (Node.js only) to allow strings such as "1 minute", "30s", etc.

## Usage/Examples

### HTML

```html
<script src="https://cdn.jsdelivr.net/gh/CookieGamer733/JSInterval/dist/jsinterval.min.js">
<script>
  const timer = new Interval({
    func: () => {
      console.log(Date.now());
    },
    delay: 1000
  });
</script>
```

### JavaScript / TypeScript

```javascript
const Interval = require("jsinterval");
// TypeScript: import Interval from "jsinterval"; with --esModuleInterop
// TypeScript: import * as Interval from "jsinterval"; with --allowSyntheticDefaultImports
// TypeScript: import Interval = require("jsinterval"); with neither of the above

const timer = new Interval({
  func: () => {
    console.log(Date.now());
  },
  delay: "1 Second"
});
```

## Documentation

Documentation is not public yet
<!-- [Documentation](https://cookiegamer733.dev/projects/jsinterval/docs/) -->

## Support

For support, email [keithbrown7526@outlook.com](mailto:keithbrown7526@outlook.com) or make an [issue](https://github.com/CookieGamer733/jsinterval/issues/new) on GitHub

## License

[ISC](https://github.com/CookieGamer733/jsinterval/blob/main/LICENSE)
