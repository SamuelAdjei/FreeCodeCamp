**Create an Export Fallback with export default**

In the `export` lesson, you learned about the syntax referred to as a named export. This allowed you to make multiple functions and variables available for use in other files.

There is another `export` syntax you need to know, known as export default. Usually you will use this syntax if only one value is being exported from a file. It is also used to create a fallback value for a file or module.

Below are examples using `export default`:

```
// named function
export default function add(x, y) {
  return x + y;
}

// anonymous function
export default function(x, y) {
  return x + y;
}
```

Since `export default` is used to declare a fallback value for a module or file, you can only have one value be a default export in each module or file. Additionally, you cannot use `export default` with `var`, `let`, or `const`

---------------------

**CHALLENEGE**

The following function should be the fallback value for the module. Please add the necessary code to do so.

```

function subtract(x, y) {
  return x - y;
}

```

**SOLUTION**

```

export default function subtract(x, y) {
  return x - y;
}

```
