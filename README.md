Vue setPath
========
Sets a dotted notation path via Vue's `$set` function.

Install
-------
```javascript
import VueSetpath from '@momsfriendlydevco/vue-setpath';
Vue.use(VueSetpath);
```

API
------------


* @param {Object} [target] The target to set the path of, if omitted the `vm` object is used as the base for traversal 
* @param {string|array} path The path to set within the target / vm
* @param {*} value The value to set
* @param {Object} [options] Additional options
* @param {boolean} [options.arrayNumeric=true] Process numeric path segments as arrays
* @param {boolean} [options.removeUndefined=true] If undefined is specified as a value the key is removed instead of being set
* @param {boolean} [options.debug=false] Also print out debugging information when setting the value
* @returns {Object} The set value, like $set()


MacGyver widgets follow the regular [Vue component syntax](https://vuejs.org/v2/guide/components.html) with some additions:

| Property           | Type                   | Default                     | Description                                                                                |
|--------------------|------------------------|-----------------------------|--------------------------------------------------------------------------------------------|
| `target`             | `object`               | `vm`                        | Meta information object - used by the form editor to configure the widget                  |
| `options.arrayNumeric`          | `boolean`               | `true`          | Process numeric path segments as arrays |
| `options.removeUndefined`       | `boolean`               | `true`  | The human friendly title of the widget                                                     |
| `options.debug`        | `boolean`               | | The set value, like `$set()` |