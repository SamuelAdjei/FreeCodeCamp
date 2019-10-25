**Use Destructuring Assignment to Assign Variables from Objects**

Destructuring allows you to assign a new variable name when extracting values. You can do this by putting the new name after a colon when assigning the value.

Using the same object from the last example:

`const user = { name: 'John Doe', age: 34 };`

Here's how you can give new variable names in the assignment:

```
const { name: userName, age: userAge } = user;
// userName = 'John Doe', userAge = 34
```

You may read it as "get the value of `user.name` and assign it to a new variable named `userName`" and so on.


---------------------

**CHALLENEGE**

Replace the two assignments with an equivalent destructuring assignment. It should still assign the variables `highToday` and `highTomorrow` the values of `today` and `tomorrow` from the `HIGH_TEMPERATURES` object.

```
const HIGH_TEMPERATURES = {
  yesterday: 75,
  today: 77,
  tomorrow: 80
};

// change code below this line
  
const highToday = HIGH_TEMPERATURES.today;
const highTomorrow = HIGH_TEMPERATURES.tomorrow; 

// change code above this line

console.log(yesterday) // should be not defined
console.log(highToday); // should be 77
console.log(highTomorrow); // should be 80

```

**SOLUTION**

```
const HIGH_TEMPERATURES = {
  yesterday: 75,
  today: 77,
  tomorrow: 80
};

// change code below this line
  
const {today: highToday, tomorrow: highTomorrow} = HIGH_TEMPERATURES;

// change code above this line

console.log(yesterday) // should be not defined
console.log(highToday); // should be 77
console.log(highTomorrow); // should be 80

```
