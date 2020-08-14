**Repeat a String Repeat a String**

**CHALLENEGE**

Repeat a given string `str` (first argument) for `num` times (second argument). Return an empty string if `num` is not a positive number.

```
function repeatStringNumTimes(str, num) {
  return str;
}

repeatStringNumTimes("abc", 3);

```

**SOLUTION**

```
function repeatStringNumTimes(str, num) {
  var emptyString = "";
  while(num > 0) {
    emptyString += str;
    num --;
  }
  return emptyString;
}

repeatStringNumTimes("abc", 3);


```
