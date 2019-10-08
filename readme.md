
版本: 1.38.1 (user setup)
提交: b37e54c98e1a74ba89e03073e5a3761284e3ffb0
日期: 2019-09-11T13:35:15.005Z
Electron: 4.2.10
Chrome: 69.0.3497.128
Node.js: 10.11.0
V8: 6.9.427.31-electron.0
OS: Windows_NT x64 10.0.18362

vetur: 0.22.4

my settings.json:
```json
{
  "vetur.format.defaultFormatter.js": "prettier",
  "vetur.format.defaultFormatter.html": "js-beautify-html",
  "vetur.format.defaultFormatterOptions": {
    "wrap_attributes": "force-aligned",
    "prettier": {
      "semi": false,
      "singleQuote": true
    }
  },
  "vetur.format.styleInitialIndent": true,
  "vetur.format.scriptInitialIndent": true,
  "vetur.validation.template": true,
  "vetur.experimental.templateInterpolationService": false,
  "prettier.singleQuote": true,
  "prettier.semi": false,
  "prettier.trailingComma": "none",
  "prettier.arrowParens": "always",
}
```

screenshot

![editor](https://raw.githubusercontent.com/XiongAmao/vetur-error-demo/master/imgs/1.jpg)