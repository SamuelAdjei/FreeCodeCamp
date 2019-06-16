**Escape Sequences in Strings**

Quotes are not the only characters that can be escaped inside a string. There are two reasons to use escaping characters: First is to allow you to use characters you might not otherwise be able to type out, such as a backspace. Second is to allow you to represent multiple quotes in a string without JavaScript misinterpreting what you mean. We learned this in the previous challenge.


Code	    Output


`\'`	    single quote


`\"`	    double quote

`\\`	    backslash

`\n`	    newline

`\r`	    carriage return
    
`\t`	    tab

`\b`	    backspace

`\f`	    form feed

**Note**


The backslash itself must be escaped in order to display as a backslash.

---------------------------

**CHALLENGE**

Assign the following three lines of text into the single variable myStr using escape sequences.

```
FirstLine
    \SecondLine
ThirdLine
```


You will need to use escape sequences to insert special characters correctly. You will also need to follow the spacing as it looks above, with no spaces between escape sequences or words.

Here is the text with the escape sequences written out.

"FirstLine `newline tab backslash`SecondLine`newline`ThirdLine"

1. `myStr` should not contain any spaces
2. `myStr` should contain the strings `FirstLine`, `SecondLine` and `ThirdLine` (remember case sensitivity)
3. `FirstLine` should be followed by the newline character \n
4. `myStr` should contain a tab character `\t` which follows a newline character
5. `SecondLine` should be preceded by the backslash character `\\`
6. There should be a newline character between `SecondLine` and `ThirdLine`

```
var myStr; // Change this line
```


**SOLUTION**


```

var myStr = "FirstLine\n\t\\SecondLine\nThirdLine";


```
