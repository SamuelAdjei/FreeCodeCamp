**Chunky Monkey**

**CHALLENEGE**

Write a function that splits an array (first argument) into groups the length of `size` (second argument) and returns them as a two-dimensional array.


```
function chunkArrayInGroups(arr, size) {
  return arr;
}

chunkArrayInGroups(["a", "b", "c", "d"], 2);

```

**SOLUTION**

```
function chunkArrayInGroups(arr, size) {
  // Break it up.
  var arr2 = [];
  for (var i = 0; i < arr.length; i += size) {
    arr2.push(arr.slice(i, i + size));
  }
  return arr2;
}
```

https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-chunky-monkey/16005
