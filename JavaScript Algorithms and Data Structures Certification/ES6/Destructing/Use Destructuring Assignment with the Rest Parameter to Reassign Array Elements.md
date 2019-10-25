**Use Destructuring Assignment with the Rest Parameter to Reassign Array Elements**

n some situations involving array destructuring, we might want to collect the rest of the elements into a separate array.

The result is similar to `Array.prototype.slice()`, as shown below:

```
const [a, b, ...arr] = [1, 2, 3, 4, 5, 7];
console.log(a, b); // 1, 2
console.log(arr); // [3, 4, 5, 7]
```

Variables `a` and `b` take the first and second values from the array. After that, because of rest parameter's presence, `arr` gets rest of the values in the form of an array. The rest element only works correctly as the last variable in the list. As in, you cannot use the rest parameter to catch a subarray that leaves out last element of the original array.


---------------------

**CHALLENEGE**

Use destructuring assignment with the rest parameter to perform an effective`Array.prototype.slice()` so that `arr` is a sub-array of the original array `source` with the first two elements omitted.

```
const source = [1,2,3,4,5,6,7,8,9,10];
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  const arr = list; // change this
  // change code above this line
  return arr;
}
const arr = removeFirstTwo(source);
console.log(arr); // should be [3,4,5,6,7,8,9,10]
console.log(source); // should be [1,2,3,4,5,6,7,8,9,10];

```

**SOLUTION**

```
const source = [1,2,3,4,5,6,7,8,9,10];
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  list = source;
  const [a,b, ...arr] = list;
  // change code above this line
  return arr;
}
const arr = removeFirstTwo(source);
console.log(arr); // should be [3,4,5,6,7,8,9,10]
console.log(source); // should be [1,2,3,4,5,6,7,8,9,10];

```
