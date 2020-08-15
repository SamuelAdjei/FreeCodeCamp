**Title Case a Sentence**


**CHALLENEGE**

Return the provided string with the first letter of each word capitalized. Make sure the rest of the word is in lower case.

For the purpose of this exercise, you should also capitalize connecting words like "the" and "of".

```
function titleCase(str) {
  return str;
}

titleCase("I'm a little tea pot");

```

**SOLUTION**

```
function titleCase(str) {
  var convertToArray = str.toLowerCase().split(" ");
  var result = convertToArray.map(function(val) {
    return val.replace(val.charAt(0), val.charAt(0).toUpperCase());
  });
  return result.join(" ");
}
```

https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-title-case-a-sentence/16088
