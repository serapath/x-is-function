# x-is-function
x is a function

# usage
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

isFunction({})
// -> false

isFunction(null)
// -> false

isFunction(undefined)
// -> false
```

# related
* [x-is](https://www.npmjs.com/package/x-is)
* [x-is-array](https://www.npmjs.com/package/x-is-array)
* [x-is-object](https://www.npmjs.com/package/x-is-object)
* [x-is-string](https://www.npmjs.com/package/x-is-string)
* [x-is-empty-object](https://www.npmjs.com/package/x-is-empty-object)
* [x-is-ducktype-array](https://www.npmjs.com/package/x-is-ducktype-array)
