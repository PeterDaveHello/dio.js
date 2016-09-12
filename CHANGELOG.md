## 1.2.0 (September 12, 2016)

- Improves performance in various ways.
- Added fragment support, you can now return a fragment/array of elements in render

### dio.PropTypes

- Added all the react land PropTypes 

```javascript
[
	number, string, bool, array, object, func, element, node
	any, shape, instanceOf, oneOf, oneOfType, arrayOf, objectOf
]
```

### dio.createStore

- Added middleware support. `dio.createStore(reducer(s), initalState, enhancer)`

### API

- Added `version, isValidElement, cloneElement, renderToString, renderToStaticMarkup`
- Exposes internal utilities to `dio._` that are used to get out-the-box support for IE8+

``` javascript
toArray
assign      (Object.assign)
keys        (Object.keys)
forEach     ([]/{}.forEach)
reduce      ([].reduce)
reduceRight ([].reduceRight)
filter      ([].filter)
map         ([].map)
isObject
isFunction
isString
isArray
isDefined
addEventListener
```