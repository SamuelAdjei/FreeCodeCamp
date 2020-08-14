**Truncate a String**


**CHALLENEGE**

Truncate a string (first argument) if it is longer than the given maximum string length (second argument). Return the truncated string with a `...` ending.

```
function truncateString(str, num) {
  return str;
}

truncateString("A-tisket a-tasket A green and yellow basket", 8);

```

**SOLUTION**

```
function truncateString(str, num) {
  if(str.length > num){
    return str.slice(0,num) + "...";
  }
  return str;
}

truncateString("A-tisket a-tasket A green and yellow basket", 8);

```
