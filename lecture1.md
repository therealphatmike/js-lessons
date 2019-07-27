# Part 1: Values, Types, Operators, and Program Structure I

## Basic operation and binary (Number Theory part I)
Though we write code in a near-english format, a computer has no concept of what a line of code like 
```
if (foo !=== bar) { ... }
``` 
means. Someone had to write a compiler or interpreter to translate that into something a computer can understand, or, like back in the old days, code was written in binary. 

Binary is just a counting system. We use a decimal counting system in everyday life. Deci- means ten. So decimal means a base ten. Essentially what this means is that every ten digits we start counting over at 0 with whatever preceding count follows it. What I mean is that our counting system relies on 10 digits, 0-9. Once we hit the 11th number, what we can ten, we write 10, the 1 indicating the tenths place, or that this is the second iteration of 0-9. Likely we can think of 111 as being the 11th 1 in a series of numbers.

Binary is much like our counting system, but it is  base 2 as the prefix bi- implies. so instead of starting back over at 1 and 0 after going to 9, we start over after 1. 

What does this look like? Below is a table of binary numbers

| Decimal Number | Binary Equivalent |
| -------------- | ----------------- |
| 0 | 0 |
| 1 | 1 |
| 2 | 10 |
| 3 | 11 |
| 4 | 100 |
| 5 | 101 |
| 6 | 110 |
| 7 | 111 |
| 8 | 1000 |
| 9 | 1001 |
| 10 | 1010 |

So, instead of having 1s, 10s, 100s, 1000s places; we have 1s, 2s, 4s, 8s, 16s places. It takes a little of a getting used to, but this is ultimate how computers read information. Strings of 1s and 0s. This is because a 1 can be represented as the presence of voltage (high voltage) and a 0 is represented as absence of voltage (low voltage) in the actual hardware.

We will continue on with binary and counting theory in the next lecture with some basic binary arithmetic, how computers do math, and getting into bytes and words and other data sizes. 

# The mysterious Algorithm
Algorithm: a process or set of rules to be followed in calculations or other problem-solving operations

So basically an algorithm is a process one can follow to solve a problem. It's that simple.

But the implications are huge. Algorithm development is of utmost important to programmers, mathematicians, and other problem solvers. It gives us a structured way to approach the world around us and interact with it on a day to day basis. An algorithm can be as complex as statistical modelling of a problem set into mathematical vectors to create a program that can recognize patterns inside larger images, or as simple as printing a string to standard output.

# Program Structure
## Bindings
Binding are used to hold values for later use in a program. Adding or changing a binding is said to change the state of the program. 

Program state is defined as the condition of all stored constants and variables.

## Expressions and Statements
In computer science an expression is a combination of one or more constants, variables, operators, and functions that the programming language(read computer) interprets/computes to produce another value

In computer science a statement is a syntactic unit of an imperative programming language that instructs the computer to carry out some action. A statement can have multiple internal components, of which can include expressions.

For example, the if **statement** below is, indeed, a statement, but it also contains an expression. This expression is used to determine if the action should be carried out.

```
if (name === 'jon') {
    say('hello, ' + name);
} else {
    say('sad, I don\'t know your name');
}
```

## Control Flow
### Conditional Execution
```
if (condition1) {

} else if (condition2) {

} else {

}
```
```
switch(condition) {
    case 1: value
        // do something
        break;
    case 2: value
        // do something
        break;
}
```

### While Loops
```
while (condition) {
    // do something
}
```

### Do While Loops
```
do {
    // something
} while (condition)
```

### For Loops
```
for (...) {
    // do something
}
```

## Closing Thoughts and Cosiderations