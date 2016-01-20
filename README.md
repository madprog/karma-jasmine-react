karma-jasmine-react
===================

Karma adapter for Jasmine plugin for testing React more easily.

Installation
------------

```sh
$ npm install karma-jasmine-react --save-dev
```

Add `jasmine-react` to the `frameworks` key in your Karma configuration, before `jasmine`:

```js
module.exports = function(config) {
  config.set({
    frameworks: ['jasmine-react', 'jasmine'],
    plugins: [karma-jasmine-react]
  });
}
```

Usage
-----

Please see https://github.com/tommyh/jasmine-react for details how to use `jasmine-react`
