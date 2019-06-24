**Compound Assignment With Augmented Addition**


In programming, it is common to use assignments to modify the contents of a variable. Remember that everything to the right of the equals sign is evaluated first, so we can say:

`myVar = myVar + 5;`


to add `5` to `myVar`. Since this is such a common pattern, there are operators which do both a mathematical operation and assignment in one step.

One such operator is the `+=` operator.

`var myVar = 1;`

`myVar += 5;` 

`console.log(myVar); // Returns 6`

------------------------------
**CHALLENGE**

Convert the assignments for `a`, `b`, and `c` to use the `+=` operator.

1. `a` should equal `15`
2. `b` should equal `26`
3. `c` should equal `19`
4. You should use the `+=` operator for each variable
5. Do not modify the code above the line


`var a = 3;`

`var b = 17;`

`var c = 12;`


// Only modify code below this line


`a = a + 12;`

`b = 9 + b;`

`c = c + 7;`

-----------------------
**SOLUTION**


`var a = 3;`

`var b = 17;`

`var c = 12;`


`a += 12;`

`b =+ 9;`

`c =+ 7;`



gvjhkbj
