# `@yusukehirao/dev-config`

## Install

```shell
npm i -D @yusukehirao/dev-config

yarn add -D @yusukehirao/dev-config
```

## Usage

### `.eslintrc`

```json
{
  "extends": ["./node_modules/@yusukehirao/dev-config/.eslintrc.js"]
}
```

### `prettier.config.cjs`

```js
module.exports = {
  ...require('@yusukehirao/dev-config/.prettierrc.json'),
};
```

### `tsconfig.json`

```json
{
  "extends": "@yusukehirao/dev-config/tsconfig.base.json"
}
```

### `cspell.json`

```json
{
  "import": ["./node_modules/@yusukehirao/dev-config/cspell.json"]
}
```
