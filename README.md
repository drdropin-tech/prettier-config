# prettier-config

Dr. Dropin [Prettier](https://prettier.io) config

## Install

```bash
$ npm install -D @drdropin-tech/prettier-config
```

## Usage

Dr. Dropin's shared prettier config comes bundled in @drdropin-tech/prettier-config. To enable these rules, add a prettier property in your package.json and reference this shared config as follows:

```js
"prettier": "@drdropin-tech/prettier-config"
```

Previously, rules had been defined directly in a .prettierrc or package.json

Any previous .prettierrc should be removed in favour of the shared config.
