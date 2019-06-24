**Return a Value from a Function with Return**

We can pass values into a function with _arguments_. You can use a `return` statement to send a value back out of a function.

**Example**

```
function plusThree(num) {
  return num + 3;
}
var answer = plusThree(5); // 8
```

`plusThree` takes an _argument_ for `num` and returns a value equal to `num + 3`.



---------------------

**CHALLENEGE**

Create a function `timesFive` that accepts one argument, multiplies it by `5`, and returns the new value. See the last line in the editor for an example of how you can test your `timesFive` function.

```
// Example
function minusSeven(num) {
  return num - 7;
}

// Only change code below this line



console.log(minusSeven(10));

```

**SOLUTION**

```
// Example
function minusSeven(num) {
  return num - 7;
}

// Only change code below this line

function timesFive(num) {
  return num * 5;
}

console.log(minusSeven(10));
```
