**Constructing Strings with Variables**

Sometimes you will need to build a string, Mad Libs style. By using the concatenation operator (+), you can insert one or more variables into a string you're building.

----------------

**CHALLENGE**
Set `myName` to a string equal to your name and build `myStr` with myName between the strings `"My name is " and " and I am well!"`

1. `myName` should be set to a string at least 3 characters long
2. Use two + operators to build `myStr` with `myName` inside it

```
// Example
var ourName = "freeCodeCamp";
var ourStr = "Hello, our name is " + ourName + ", how are you?";

// Only change code below this line
var myName;
var myStr;

```


**SOLUTION**

```
// Example
var ourName = "freeCodeCamp";
var ourStr = "Hello, our name is " + ourName + ", how are you?";

// Only change code below this line
var myName = "Samuel";
var myStr = "My name is " + myName + " and I am well!";


```
