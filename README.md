### p-map
---
https://github.com/sindresorhus/p-map

```js
// test.js
import test from 'ava';


const sharedInput = [
  Promise.resolve([10, 300]),
  [20, 200],
  [30, 100]
];

const errorInput1 = [
  [20, 200],
  [30, 100],
  [() => Promise.reject(new Error('foo')), 10],
  [() => {
    throw new Error('bar');
  }, 10]
];





```

```
```

```
```
