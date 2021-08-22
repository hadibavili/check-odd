# check-odd
Returns true if the given number is odd, and is an integer that does not exceed the JavaScript MAXIMUM_SAFE_INTEGER.


# Usage


sample:
```js
const isOdd = require('check-odd');

console.log(isOdd('1')); //=> true
console.log(isOdd('3')); //=> true

console.log(isOdd(0)); //=> false
console.log(isOdd(2)); //=> false
```

