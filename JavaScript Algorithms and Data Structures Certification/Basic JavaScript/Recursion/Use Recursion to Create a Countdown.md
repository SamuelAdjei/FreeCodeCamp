**Use Recursion to Create a Countdown**

Continuing from the previous challenge, we provide you another opportunity to create a recursive function to solve a problem.


---------------------

**CHALLENEGE**

We have defined a function called `countdown` with two parameters. The function should take an array in the `myArray` parameter and append the numbers `n` through `1` based on the `n` parameter.
For example, calling this function with `n = 5` will pad the array with the numbers `[5, 4, 3, 2, 1]` inside of it. Your function must use recursion by calling itself and must not use loops of any kind.

```
//Only change code below this line
function countdown(myArray, n){
  
  return;
}

```

**SOLUTION**

```
function countdown(myArray, n){
  if(n <= 0){
    return;
  }
  else{
    myArray.push(n);
    countdown(myArray, n - 1);
  }
}
```
