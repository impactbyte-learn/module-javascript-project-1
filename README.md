# JavaScript Project 1

---

# Manipulation: Number

---

## Requirements

Play around with various kind of number manipulation capabilities in JavaScript.

### Input

* Mostly numbers

### Process

* Addition
* Substraction
* Multiplication
* Division
* Modulation

### Output

* Transformed numbers

---

## Level 0

* Create some numbers you like that stored in different variables
* Those values inside those variables can be changed or not depend on your intention
* Log those numbers to the console

```js
var numberA = 10;
let numberB = 099;
const numberC = 0.02;
```

---

## Level 1

* Have some transformation to those number variables: addition, substraction, multiplication, division, modulation
* Use basic mathematical operators to accomplish that
* Output the results to the console

```js
+
-
*
/
%
```

---

## Level 2

* Try to operate those variables with a different types like string and boolean
* Try to use a negative number or a very big number, then operate on them

---

## Level 3

* Store different kind of numbers into an array variable
* Combine, push, or pop different kind of data types like a string and boolean to that array variable
* Loop through the numbers or items in the array, then log them to the console

# Manipulation: String

---

## Requirements

Play around with various kind of string manipulation capabilities in JavaScript.

### Input

* Mostly texts

### Process

* Concatination
* Upper case
* Lower case
* Title case

### Output

* Transformed texts

---

## Level 4

* Create some simple sentences that stored in different variables
* Those values inside those variables should not be changed
* If you want to create a new value, you should create a new variable
* Log those strings to the console

```js
const sentenceA = "Hello World!";
const sentenceB = "Good Bye!";

console.log(sentenceA);
console.log(sentenceB);
```

* For all the programs you write in the following days, use concise comments and indentation to better serve your code

```js
// This is a comment
/*
 * Also a comment
 * with multiple lines
 */
```

---

## Level 5

* Combine those different sentences into one sentence

```js
const sentenceC = sentenceA + " " + sentenceB;
```

* Try to use string template literals to save time

```js
const sentenceD = `${sentenceA} ${sentenceB}`;
```

* Again, log those strings to the console

---

## Level 6

* Transform all the characters of a string into different case of letters: uppercase and lowercase

Input example:

```js
"Hello World";
"Good Bye";
```

Output example:

```js
"HELLO WORLD";
"GOOD BYE";
```

---

## Level 7

* Transform all the characters of a string into title case

Input example:

```js
"hello goodness";
```

Output example:

```js
"Hello Goodness";
```

* You are free to change the value of your variables

# Comparison: Number

---

## Requirements

Compare some numbers then determine which one is bigger or smaller.

### Input

* Two or more different numbers

### Process

* Compare number and number

### Output

* Telling which one is bigger or smaller

---

## Level 8

* Store different numbers into some variables
* Create some `if else` statement blocks that tell if each number is bigger or smaller than our determined value
* Log that results to the console

---

## Level 9

* Try to compare those numbers with each other
* Expand the `if else` statements into multiple chains

```js
if (condition) {
  // code
} else if (condition) {
  // code
} else {
  // code
}
```

---

## Level 10

* Use ternary operator `? :` rather than `if else` statement

```js
condition ? resultA : resultB;
```

---

## Level 11

* Try to compare a variable with value range, with more than 2 conditions, bigger and smaller than some different value at the same time
* Experiment with various kind of operations

```js
min >= condition >= max;
```

```js
conditionA && conditionB;
```

---

## Level 12

* Wrap those logics into some functions that can be called later
* Use parameters to enable us assign different kind of inputs to compare
* You need at least two parameters for these functions

```js
function process(parameterA, parameterB) {
  // code
}

process();
```

---

## Level 13

* Create a random number generator

# Calculator: Math

---

## Requirements

Build a simple calculator to compute basic math operations.

### Input

* Numbers

### Process

* Several functions to run different kind of operations

### Output

* Calculated numbers

---

## Level 14

* Prepare all basic math operations you already learnt

---

## Level 15

* Wrap those operations into different kind functions

```js
function add(...) { ... }
function substract(...) { ... }
function multiply(...) { ... }
function divide(...) { ... }
function modulo(...) { ... }
```

---

## Level 16

* Experiment to call some chain of different functions in other functions

```js
add(substract(...), divide(...))
```

# Calculator: Shape

---

## Requirements

Build a simple calculator to compute basic calculation of shape's area size, perimeter/circumference, or volume size.

### Input

* Numbers

### Process

* Several functions to run different kind of operations

### Output

* Calculated numbers

---

## Level 17

* Prepare all basic shape calculation you already learnt

---

## Level 18

* Wrap those operations into different kind functions based on the shapes

```js
function calculateSquareArea(...) { ... }
function calculateSquarePerimeter(...) { ... }
function calculateCircleArea(...) { ... }
function calculateCircleCircumference(...) { ... }
function calculateCubeArea(...) { ... }
function calculateCubeVolume(...) { ... }
function calculateTubeArea(...) { ... }
function calculateTubeVolume(...) { ... }
// and much more
```

---

## Level 19

* Experiment to create variation and call some chain of different functions you already made with these new functions

```js
calculateSquareArea(add(...))
calculateTubeVolumeWithCircle(calculateCircleArea())
```

# Calculator: Time

---

## Requirements

Build a simple calculator to calculate time.

### Input

* Time in numbers with measurement you specify
* Time with `Date` object

### Process

* Several functions to run different kind of operations

### Output

* Calculated time

---

## Level 20

* Prepare all basic time operations you already learnt with just utilizing number
* For example, determine how to get value of seconds, minutes, hours, days, months, years based on different time

---

## Level 21

* Prepare time operations with `Date` object
* Get different kind desired values through the built-in methods

---

## Level 22

* Wrap those operations into different kind functions
* Learn which way is the best to calculate time dimension

---

## Level 23

* Experiment to create variation and call some chain of different functions in other functions

# Address Book

---

## Requirements

Let's create an address book simulation.

### Input

* People's contact information

### Process

* Storing and retrieving information

### Output

* Retrieved information

---

## Level 24

* Research a bit what you're going to model the address book after
* Sketch out your plan, try to type a simple pseudocode, then get some experiment going!
* Have fun of creating an address book simulation. :)

---

## Level 25

* Store and retrieve a single type of information in an array

---

## Level 26

* Store and retrieve multiple types of information in several objects that stored in an array

# Todo List

---

## Requirements

Let's create a simple todo list program.

### Input

* Our todo list

### Process

* Storing and retrieving information

### Output

* Our todo list ;)

---

## Level 27

* Research a bit what you're going to model the todo list after
* Sketch out your plan, try to type a simple pseudocode, then get some experiment going!
* Have fun of creating a todo list program. :)

---

## Level 28

* Store and retrieve a single type of information in an array

---

## Level 29

* Store and retrieve multiple types of information in several objects that stored in an array
