# prettier-config-marksmall

My personal [Prettier](https://prettier.io) config.

## Install

```bash
npm install --save-dev prettier-config-marksmall
yarn add -D prettier-config-marksmall
```

## Usage

Add `.prettierrc.js` file with contents:

```js
module.exports = {
  ...require('prettier-config-marksmall'),
  semi: false,
}
```

This allows you to use the contents of the shareable config, while still having the option of overriding properties from shared config.
