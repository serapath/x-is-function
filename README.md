# x-is-function
Simple function test

## Usage
`npm install x-is-function`

```js
var isFunction = require('x-is-function')

isFunction(function () {})
// -> true

isFunction("hello")
// -> false

isFunction("")
// -> false

isFunction(9)
// -> false

isFunction(true)
// -> false

isFunction(new Date())
// -> false

isFunction({
// -> false

isFunction(null)
// -> false

isFunction(undefined)
// -> false
```

## Related

* [x-is-array](https://www.npmjs.com/package/x-is-array)
* [x-is-object](https://www.npmjs.com/package/x-is-object)
* [x-is-string](https://www.npmjs.com/package/x-is-string)
