# babel-preset-build-engine
Collection of Babel presets and plugins for all the development environments

## Installation

You'll install `babel-preset-build-engine`:

```
$ npm install babel-preset-build-engine --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `babel-preset-build-engine` globally.

## Usage

Add `build-engine` to the plugins section of your `.babelrc` configuration file. You can omit the `babel-preset-` prefix:

## For Nodejs

```json
{
    "presets": [
        "build-engine"
    ]
}
```

## For React with transform-runtime

```json
{
    "presets": [
        "build-engine/react"
    ]
}
```


## For Webpack with React & transform-runtime & enabled the Tree shaking

```json
{
    "presets": [
        "build-engine/reactWebpack"
    ]
}
```

## For Webpack & transform-runtime & enabled the Tree shaking

```json
{
    "presets": [
        "build-engine/webpack"
    ]
}
```

## License

[MIT](http://www.opensource.org/licenses/mit-license.php)





