# stylelint-config-kensho

This [Stylelint config](http://stylelint.io/user-guide/configuration/#extends) extends the [standard config](https://github.com/stylelint/stylelint-config-standard) with a few customizations.

You can use it to lint CSS and postcss files.

## Usage

To use the config, install stylelint and this config as development dependencies:

```sh
$ npm i -D stylelint stylelint-config-kensho
```

Add a `.stylelintrc.json` which extends the config:

```json
{
  "extends": "stylelint-config-kensho"
}
```

Add an npm script in `package.json` to run the linter on all CSS files:

```json
{
  "scripts": {
    "lint:css": "stylelint 'src/**/*.css'"
  }
}
```
