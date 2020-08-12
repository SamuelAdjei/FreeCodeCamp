**Find the Longest Word in a String**

**CHALLENEGE**

Return the length of the longest word in the provided sentence.

Your response should be a number

```
function findLongestWordLength(str) {
  return str.length;
}

findLongestWordLength("The quick brown fox jumped over the lazy dog");

```

**SOLUTION**

```
function findLongestWordLength(str) {
  var words = str.split(' ');
  var maxLength = 0;

  for (var i = 0; i < words.length; i++) {
    if (words[i].length > maxLength) {
      maxLength = words[i].length;
    }
  }

  return maxLength;
}

```
