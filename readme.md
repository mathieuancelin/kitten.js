Kittens.js
-------------------

Kittens.js is a dumb library to show kittens running on you webpage.

```
npm install --save kittens
```

```javascript
// Kittens is also expose in the global scope
// but if you use modules
var Kittens = require('kittens');

Kittens.run(); // show 5 kittens
Kittens.run(42); // show 42 kittens
Kittens.run({
  kittens: 42,
  baseIncrement: 7,
  widthOffset: 200,
  heightOffset: 200
});
```
