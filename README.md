# tsconfig-base

This is a base `tsconfig.json` file for [Robot-Inventor](https://github.com/Robot-Inventor)'s TypeScript projects.

## Usage

```bash
npm install --save-dev @robot-inventor/tsconfig-base
```

Then, in your `tsconfig.json` file:

```json5
{
    "extends": "@robot-inventor/tsconfig-base/tsc.json"
}
```

- `@robot-inventor/tsconfig-base/tsc.json`: For use with the TypeScript compiler (`tsc`).
- `@robot-inventor/tsconfig-base/bundler.json`: For use with a bundler like Webpack.
- `@robot-inventor/tsconfig-base/react-emotion.json`: For use with React and Emotion.
