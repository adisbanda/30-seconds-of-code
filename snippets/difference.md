### difference

Returns the difference between two arrays.

Create a `Set` from `b`, then use `Array.filter()` on `a` to only keep values not contained in `b`.

```js
const difference = (a, b) => a.filter(x => !b.includes(x));
```

```js
difference([1, 2, 3], [1, 2, 4]); // [3]
```
