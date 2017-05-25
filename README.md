# stylelint-config-tourstream

> Shareable config for stylelint of Tourstream

## Installation

```console
$ npm install stylelint-config-tourstream --save-dev
```

or

```console
$ yarn add stylelint-config-tourstream -D
```

## Usage

Create a .stylelintrc file with the following basic configuration:

```json
{
  "extends": "stylelint-config-tourstream"
}
```

### Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to tabs and turn off the `number-leading-zero` rule:


```json
{
  "extends": "stylelint-config-tourstream",
  "rules": {
    "indentation": "tab",
    "number-leading-zero": null
  }
}
```

## Presets

In addition to the default preset, there are also specific presets. All presets extend the default one.

### SCSS

```json
{
  "extends": [
    "stylelint-config-tourstream/scss"
  ]
}
```

## Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to four spaces and turn off the `number-leading-zero` rule:


```json
{
  "extends": "stylelint-config-tourstream",
  "rules": {
    "indentation": 4,
    "number-leading-zero": null
  }
}
```


## [License](LICENSE)
