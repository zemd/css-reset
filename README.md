# @zemd/css-reset

[![npm](https://img.shields.io/npm/v/@zemd/css-reset?color=0000ff&label=npm&labelColor=000)](https://npmjs.com/package/@zemd/css-reset)

Simple and minimal CSS reset for modern web development.

## Installation

```sh
bun add @zemd/css-reset
npm install @zemd/css-reset
pnpm add @zemd/css-reset
```

## Usage

```css
@import "@zemd/css-reset";
/* @import @zemd/css/extra.css */ /* - imports additional styles that were not included in the default reset file */
```

Note: when using `@zemd/reset-css` with Tailwind you might also want to disable preflight styles: 

```js
// tailwind.config.js
module.exports = {
  // ...
  corePlugins: {
    preflight: false,
  },
}
```

## License

All the code in the repository released under the Apache 2.0 license

## Donate

[![](https://img.shields.io/badge/patreon-donate-yellow.svg)](https://www.patreon.com/red_rabbit)
[![](https://img.shields.io/static/v1?label=UNITED24&message=support%20Ukraine&color=blue)](https://u24.gov.ua/)