**Write Reusable JavaScript with Functions**

In JavaScript, we can divide up our code into reusable parts called _functions_.

Here's an example of a function:

```
function functionName() {
  console.log("Hello World");
}
```

You can call or invoke this function by using its name followed by parentheses, like this: 

`functionName();`

Each time the function is called it will print out the message `"Hello World"` on the dev console. All of the code between the curly braces will be executed every time the function is called.


---------------------

**CHALLENEGE**

1. Create a function called `reusableFunction` which prints `"Hi World"` to the dev console.

2. Call the function.

```
// Example
function ourReusableFunction() {
  console.log("Heyya, World");
}

ourReusableFunction();

// Only change code below this line

```

**SOLUTION**

```
// Example
function ourReusableFunction() {
  console.log("Heyya, World");
}

ourReusableFunction();

// Only change code below this line

function reusableFunction() {
    console.log("Hi World");
}

reusableFunction();
```
