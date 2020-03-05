**Match Characters that Occur Zero or More Times**

The last challenge used the plus `+` sign to look for characters that occur one or more times. There's also an option that matches characters that occur zero or more times.

The character to do this is the asterisk or star: `*`.

```
let soccerWord = "gooooooooal!";
let gPhrase = "gut feeling";
let oPhrase = "over the moon";
let goRegex = /go*/;
soccerWord.match(goRegex); // Returns ["goooooooo"]
gPhrase.match(goRegex); // Returns ["g"]
oPhrase.match(goRegex); // Returns null
```


---------------------

**CHALLENEGE**

For this challenge, `chewieQuote` has been initialized as "Aaaaaaaaaaaaaaaarrrgh!" behind the scenes. Create a regex `chewieRegex` that uses the `*` character to match an uppercase `"A"` character immediately followed by zero or more lowercase `"a"` characters in `chewieQuote`. Your regex does not need flags or character classes, and it should not match any of the other quotes.

```
// Only change code below this line
let chewieRegex = /change/; // Change this line
// Only change code above this line

let result = chewieQuote.match(chewieRegex);

```

**SOLUTION**

```
// Only change code below this line
let chewieRegex = /Aa*/; // Change this line
// Only change code above this line

let result = chewieQuote.match(chewieRegex);

```
