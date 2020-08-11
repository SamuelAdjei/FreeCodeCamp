**Reverse a String**

Reverse the provided string.

You may need to turn the string into an array before you can reverse it.

Your result must be a string.


```
function reverseString(str) {
  return str;
}

reverseString("hello");

```

**SOLUTION**

```
function reverseString(str) {
  return str
    .split("")
    .reverse()
    .join("");
}
reverseString("hello");

```
```
function reverseString(str) {
  for (var reversedStr = "", i = str.length - 1; i >= 0; i--) {
    reversedStr += str[i];
  }
  return reversedStr;
}
```
