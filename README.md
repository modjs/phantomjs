mod-phantomjs
===

Run in phantomjs sandbox


## Usage

```js
module.exports = {
    plugins: {
        "phantom": "mod-phantomjs"
    },
    tasks: {
        "phantom": {
            script: "./test.js",
            args: "http://www.baidu.com"
        }
    }
};
```