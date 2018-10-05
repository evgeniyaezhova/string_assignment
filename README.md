# String Exercises

1. console.log the first character of a string.
let str = "elephant"
console.log(str[0])

2. console.log the length of a string.

console.log(str.length)

3. console.log the last character of any string.

console.log(str[str.length - 1])

4. Create a code block that takes a single string variable, and returns a copy of the string with the last letter capitalized.

str = str.slice(0, [str.length - 1]) + str[str.length - 1].toUpperCase()
console.log(str)

5. Create a drEvil code block that will take a single number variable, and log the '<variablbeAmount> dollars',
your code block should add '(pinky)' at the end of the amount if it's 1 million. For example:

```js
let amount = 10
// => 10 dollars
let amount = 1000000
// =>  1000000 dollars (pinky)
```

let variableAmount = 27
if (variableAmount === 1000000) {
  console.log(variableAmount + " dollars" + " (pinky)")
} else {
  console.log(variableAmount + " dollars")
}


6. Create a `verbing` code block. It should take a single string variable. If its length is at least 3, it should add 'ing' to its end, unless it already ends in 'ing', in which case it should add 'ly' instead. If the string length is less than 3, it should leave it unchanged.
For example:

```js
verbing('box')
// => 'boxing'
verbing('train')
// => 'training'
verbing('swimming')
// =>  'swimmingly'
verbing('go')
// =>  'go'
```
let verbing = "cool";
if(verbing.slice(verbing.length - 3) === "ing") {
  console.log(verbing + "ly")
}
else if(verbing.length < 3){
  console.log(verbing)
} else {
  console.log(verbing + "ing")
}



7. Create a `withoutLast` code block that takes a single string variable, and returns a copy of the string without the  last

let str = "street";
let withoutLast = str.slice(0, [str.length - 1]);
console.log(withoutLast)
