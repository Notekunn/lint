# @notekunn/prettier-configs

notekunn's Prettier config.

Read the [Prettier config docs](https://prettier.io/docs/en/index.html) for more information.

## Installation

```shell
yarn add --dev @notekunn/prettier-configs
```

## Usage

After installing, update `package.json` file to add the following properties.

```text
"prettier": "@notekunn/prettier-configs",
```

The Prettier config can be applied to the root `package.json` in a Lerna project.

Additionally, you can use the following binaries to run Prettier with the default glob `js,jsx,mjs,ts,tsx,json,md,yml,yaml`.

```text
"scripts": {
  "format:check": "prettier-configs check",
  "format:write": "prettier-configs write",
},
```
