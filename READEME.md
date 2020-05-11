# webpack js loader for require in comment

## install

```bash
npm i auto-lego-export-loader --save-dev
```

## use

**webpack.config.js**

```js
module.exports = {
  module: {
    rules: [
      {
        test: /\.js$/,
        loaders: ["auto-lego-export-loader"],
        include: [path.resolve(__dirname, "node_modules")],
      },
    ],
  },
};
```

[参考文献](https://juejin.im/post/5a4f3791f265da3e3f4c7ee6)
