# @spencercreative/eslint-config

ESLint configuration for Spencer Creative

## Install

```bash
# npm
npm i -D @spencercreative/eslint-config

# yarn
yarn add -D @spencercreative/eslint-config
```

## Add to ESLint Config

```js
{
  "extends": [
    // ... other configs
    "@spencercreative/eslint-config"
  ],
}
```

## Add Prettier Config

Create a `prettier.config.js` file. This helps avoid ESLint and Prettier conflicts.

```js
/** @type {import('prettier').RequiredOptions} */
module.exports = {
  arrowParens: 'always',
  bracketSpacing: true,
  tabWidth: 2,
  printWidth: 80,
  semi: false,
  singleQuote: true,
  trailingComma: 'es5',
}
```
