**Comparison with the Strict Inequality Operator**

The strict inequality operator (`!==`) is the logical opposite of the strict equality operator. It means "Strictly Not Equal" and returns `false` where strict equality would return `true` and _vice versa_. Strict inequality will not convert data types.

**Examples**

```
3 !== 3 // false
3 !== '3' // true
4 !== 3 // true
```
---------------------

**CHALLENEGE**

Add the `strict inequality operator` to the `if` statement so the function will return "Not Equal" when `val` is not strictly equal to `17`

```
// Setup
function testStrictNotEqual(val) {
  // Only Change Code Below this Line
  
  if (val) {

  // Only Change Code Above this Line

    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testStrictNotEqual(10);
```

**SOLUTION**

```
// Setup
function testStrictNotEqual(val) {
  // Only Change Code Below this Line
  
  if (val !== 17) {

  // Only Change Code Above this Line

    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testStrictNotEqual(10);
```
