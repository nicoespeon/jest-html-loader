# jest-html-loader

[html-loader](https://github.com/webpack-contrib/html-loader) plugin for Jest v28+

An alternative to [html-loader-jest](https://www.npmjs.com/package/html-loader-jest) that only works until Jest 27

## Install

```
npm install --save-dev jest-html-loader
```

## Integration with jest

Define `jest-html-loader` as a transformer for your html files included in your source files under test. In the "transform" key for jest configuration in the `package.json` add the following:

```json
"transform": {
  "^.+\\.html?$": "jest-html-loader"
},
```
