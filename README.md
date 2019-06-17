# debug-mock

Mocks usage of the `debug` module to reduce the size of your JS bundle.

## Usage

```
npm install --save github:petermikitsh/debug-mock
```

In `webpack.config.js`:

```js
{
  resolve: {
    alias: {
      'debug': 'debug-mock'
    }
  }
}
```
