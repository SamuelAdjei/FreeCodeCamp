**Access Array Data with Indexes**

We can access the data inside arrays using `indexes`.

Array indexes are written in the same bracket notation that strings use, except that instead of specifying a character, they are specifying an entry in the array. Like strings, arrays use zero-based indexing, so the first element in an array is element `0`.

**Example**

```
var array = [50,60,70];
array[0]; // equals 50
var data = array[1]; // equals 60
```

**Note**
There shouldn't be any spaces between the array name and the square brackets, like `array [0]`. Although JavaScript is able to process this correctly, this may confuse other programmers reading your code.


---------------------

**CHALLENEGE**

Create a variable called `myData` and set it to equal the first value of `myArray` using bracket notation.
1. The variable `myData` should equal the first value of `myArray`.
2. The data in variable `myArray` should be accessed using bracket notation.

```
// Example
var ourArray = [50,60,70];
var ourData = ourArray[0]; // equals 50

// Setup
var myArray = [50,60,70];

// Only change code below this line.

```

**SOLUTION**

```
// Example
var ourArray = [50,60,70];
var ourData = ourArray[0]; // equals 50

// Setup
var myArray = [50,60,70];

// Only change code below this line.
myData = myArray[0];
```
