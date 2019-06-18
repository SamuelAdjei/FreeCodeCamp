**Use Bracket Notation to Find the Last Character in a String**


In order to get the last letter of a string, you can subtract one from the string's length.

For example, if `var firstName = "Charles"`, you can get the value of the last letter of the string by using `firstName[firstName.length - 1]`.



---------------------

**CHALLENEGE**
Use _bracket notation_ to find the last character in the `lastName` variable.

1. `lastLetterOfLastName` should be "e".
2. You have to use `.length` to get the last letter.

```
// Example
var firstName = "Ada";
var lastLetterOfFirstName = firstName[firstName.length - 1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var lastLetterOfLastName = lastName;


```

**SOLUTION**

```
// Example
var firstName = "Ada";
var lastLetterOfFirstName = firstName[firstName.length - 1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var lastLetterOfLastName = lastName[lastName.length -1];


```
