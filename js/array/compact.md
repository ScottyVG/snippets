### compact

Removes falsey values from an array.

Use `Array.prototype.filter()` to filter out falsey values (`false`, `null`, `0`, `""`, `undefined`, and `NaN`).

```js
const compact = arr => arr.filter(Boolean);
```

<details>
<summary>Examples</summary>

```js
compact([0, 1, false, 2, '', 3, 'a', 'e' * 23, NaN, 's', 34]); // [ 1, 2, 3, 'a', 's', 34 ]
```

