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

Kittens.init(); // show 5 kittens
Kittens.init(42); // show 42 kittens
```
