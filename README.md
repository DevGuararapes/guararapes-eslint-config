# Guararapes ESLint Config
[![NPM Version][npm-image]][npm-url]
[![Downloads Stats][npm-downloads]][npm-url]

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

**1.** Install the dependencies
```
npm i -D eslint @guararapes/eslint-config
```
&ensp;&ensp;&ensp; or
```
yarn add -D eslint @guararapes/eslint-config
```

**2.** Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@guararapes/eslint-config/react"
}
```

**3.** Reload VSCode

[npm-image]: https://img.shields.io/npm/v/@guararapes/eslint-config.svg?style=flat-square
[npm-url]: https://npmjs.org/package/@guararapes/eslint-config
[npm-downloads]: https://img.shields.io/npm/dm/@guararapes/eslint-config.svg?style=flat-square
