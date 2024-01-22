# eslint-config-hmdarkfir3

This is my personal ESLint config.

## Features

The config includes these plugins by default:

- [@typescript-eslint/eslint-plugin](https://github.com/typescript-eslint/typescript-eslint)
- [import](https://github.com/import-js/eslint-plugin-import)
- [jest](https://github.com/jest-community/eslint-plugin-jest)
- [prettier](https://github.com/prettier/eslint-plugin-prettier)
- [a11y](https://github.com/jsx-eslint/eslint-plugin-jsx-a11y)
- [react](https://github.com/yannickcr/eslint-plugin-react)
- [react-hooks](https://www.npmjs.com/package/eslint-plugin-react-hooks)
- [react-native](https://github.com/intellicode/eslint-plugin-react-native)

## Setup

1. Install the dependencies
```
npm i -D eslint eslint-config-hmdarkfir3
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "eslint-config-hmdarkfir3/react-native"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
