***

> A WebdriverIO plugin to generate cucumber step definitions snippets to paste in your code.

## Installation

The easiest way is to keep `wdio-cucumber-snippet-reporter` as a devDependency in your `package.json`.

```json
{
  "devDependencies": {
    "wdio-cucumber-snippet-reporter": "~0.0.3"
  }
}
```

You can simple do it by:

```bash
npm i wdio-cucumber-snippet-reporter -D
```

## Configuration

Following code shows the default wdio test runner configuration. Just add `'cucumber-snippet'` as reporter
to the array.

```js
// wdio.conf.js
module.exports = {
  // ...
  reporters: ['dot', 'spec', 'cucumber-snippet'],
  // ...
};
```

## Development

All commands can be found in the package.json. The most important are:

Watch changes:

```sh
$ npm run watch
```

Run tests:

```sh
$ npm test

# run test with coverage report:
$ npm run test:cover
```

Build package:

```sh
$ npm run build
```
