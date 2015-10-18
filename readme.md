Kitten.js
-------------------

Kitten js is a dumb library to show kitten running on you webpage.

```
npm install --save kittens
```

```javascript
// Kittens is also expose in the global scope
// but if you use modules
var Kittens = require('kittens');

Kittens.init(); // show 5 kitten
Kittens.init(42); // show 42 kitten
```
