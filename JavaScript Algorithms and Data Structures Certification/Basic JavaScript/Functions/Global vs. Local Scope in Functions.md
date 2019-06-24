**Global vs. Local Scope in Functions**

It is possible to have both _local_ and _global_ variables with the same name. When you do this, the `local` variable takes precedence over the `global` variable.

In this example:

```
var someVar = "Hat";
function myFun() {
  var someVar = "Head";
  return someVar;
}
```

The function `myFun` will return `"Head"` because the `local` version of the variable is present.

---------------------

**CHALLENEGE**

Add a `local` variable to `myOutfit` function to override the value of `outerWear` with `"sweater"`.

```
// Setup
var outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
  
  
  
  // Only change code above this line
  return outerWear;
}

myOutfit();
```

**SOLUTION**

```
// Setup
var outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
  var outerWear = "sweater";
  
  
  // Only change code above this line
  return outerWear;
}

myOutfit();
```
