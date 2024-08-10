# tsconfig-base

This is a base `tsconfig.json` file for [Robot-Inventor](https://github.com/Robot-Inventor)'s TypeScript projects.

## Usage

```bash
npm install --save-dev @robot-inventor/tsconfig-base
```

Then, in your `tsconfig.json` file:

```json5
{
    // If you are using a bundler like Webpack, use `@robot-inventor/tsconfig-base/bundler.json` instead.
    "extends": "@robot-inventor/tsconfig-base/tsc.json"
}
```
