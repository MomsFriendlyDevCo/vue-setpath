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

| Property           | Type                   | Default                     | Description                                                                                |
|--------------------|------------------------|-----------------------------|--------------------------------------------------------------------------------------------|
| `target`             | `object`               | `vm`                        | Meta information object - used by the form editor to configure the widget                  |
| `options.arrayNumeric`          | `boolean`               | `true`          | Process numeric path segments as arrays |
| `options.removeUndefined`       | `boolean`               | `true`  | The human friendly title of the widget                                                     |
| `options.debug`        | `boolean`               | | The set value, like `$set()` |