# #100DaysOfCode Log - Round 1 - [Charles Freeborn Eteure]

The log of my #100DaysOfCode challenge. Started on [October 24, Tuesday, 2017].

## Log

### R1Day1 
Started the #100DaysOfCode. I will be working on my portfolio page for the freeodeCamp. Let's get started

### R1Day2
Finished the portfolio website for the freeCodeCamp Front-End Development curriculum. Here is the link to the page. [Portfolio Website](https://codepen.io/ceteure/full/RZpNBV/)
Beginning the basic javascript with freeCodeCamp.

### R1Day3

Studied and practie on ES6 arrow functions. The take away from the session -
1. Arrow functions are more concise than regular functions
2. They have implicit returns
3. It doesn't rebind the value of this when you use arrow function inside of another function

An example: 

```
const readingLists = ["MDN", "Eloquent JavaScript", "Speaking JavaScript"];

const readingGoals = readingLists.map((readingList)=>
{
return `${readingList} - currently reading these materials`;
});

console.log(readingGoals);
```

### R1Day4

Studied and practice on arrow functions in ES6. The key take aways for today's training and practice session is:
1. Arrow functions are always anonymous
2. Arrow functions can work with anything
3. You can use an arrow function inside of a regular function and it will inherit the value of "this".
