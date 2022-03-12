# eslint-config-nijicha

Personal ESLint rules for React Project (with Typescript ❤️)

## Prerequisites

NodeJS and `yarn` should be installed.

## Installation

Install npm package and its peerDependencies

```shell
yarn add -D eslint-config-nijicha
npx install-peerdeps -D eslint-config-nijicha
```

## Usage

1. Add config to your `.eslintrc.js`

```
{
  'extends': [
    'nijicha'
  ]
}
```

2. Copy the following files into your project

```
.husky/pre-commit
.eslintignore
.eslintrc.js
.prettierrc
.prettierignore
```

## TODO

- [ ] Add development section
- [ ] Add script to copy setting to the setting up project

## Development

```shell
./bin/setup.sh
```
