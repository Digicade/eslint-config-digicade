# eslint-config-digicade


## Installation

```
$ npm install --save-dev eslint eslint-config-digicade
```


## Usage

Once the `eslint-config-digicade` package is installed, you can use it by specifying `digicade` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```js
{
  "extends": "digicade",
  "rules": {
    // Additional, per-project rules...
  }
}
```