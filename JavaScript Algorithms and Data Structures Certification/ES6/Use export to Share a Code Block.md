**Use export to Share a Code Block**

Imagine a file called math_functions.js, it contains several functions related to mathematical operations. One of them is stored in a variable, add, that takes in two numbers and returns the sum of them. You want to use this function in several different JavaScript files. In order to share it with the files, you need to first export it.

```
export const add = (x, y) => {
  return x + y;
}
```

The above is a common way to export a single function, but you can achieve the same thing like this:

```
const add = (x, y) => {
  return x + y;
}

export { add };
```

After you export a variable or function, you can import it in another file to use without having to rewrite the code. You can export multiple things by repeating the first example for each thing you want to export, or by placing them all in the export statement of the second example like this:

`export { add, subtract };`

---------------------

**CHALLENEGE**

There are two functions related to strings in the editor. Export both of them using the method of your choice.

```
const uppercaseString = (string) => {
  return string.toUpperCase();
}

const lowercaseString = (string) => {
  return string.toLowerCase()
}
```

**SOLUTION**

```
const uppercaseString = (string) => {
  return string.toUpperCase();
}

const lowercaseString = (string) => {
  return string.toLowerCase()
}

export { uppercaseString, lowercaseString};
```
