# xcxerxes-sorted

A small module to check sorted

## Example
```
 javascript
 var sorted = require('xcxerxes-sorted')

 console.log(sorted([1, 2, 3]))
 // => true

 console.log(sorted([3, 1, 2]))
 // => false

 console.log(sorted([3, 2, 1], function (a, b) { return b - a })
// => true
```