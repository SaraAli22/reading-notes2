# HTMl and CSS :
What is difference between HTML and CSS?
![image](https://www.codingdojo.com/blog/wp-content/uploads/real-slimmmy.jpg)
Quite simply, HTML (Hypertext Markup Language) is used to create the actual content of the page, such as written text, and CSS (Cascade Styling Sheets) is responsible for the design or style of the website, including the layout, visual effects and background color.

![image](https://www.codingdojo.com/blog/wp-content/uploads/Infographic-HTML-CSS.png)

### Designing A Script Tasks :
A script is a series of instructions that a 
computer can follow to achieve a goal. 
 **How can I Write and Design script**
 
* Each time the script runs, it might only use a subset of 
all the instructions. 

* Computers approach tasks in a different way than 
humans, so your instructions must let the computer 
solve the task prggrammatically. 

* To approach writing a script, break down your goal into 
a series of tasks and then work out each step needed 
to complete that task (a flowchart can help).

![image](https://i.stack.imgur.com/OVmOR.png)

### EXPRESSIONS 
An expression evaluates into (results in) a single value. Broadly speaking ,there are two types of expressions. 

1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE  

### OPERATORS 
Expressions rely on things called operators; they allow programmers to create a single value from one or more values. 

 ### ARITHMETI C OPERATORS 
JavaScript contains the following mathematical 
operators, which you can use with numbers. 
### STRING OPERATOR 
There is just one string operator: the+ symbol. 
It is used to join the strings on either side of it. 

# Declaring a function
The function declaration (function statement) defines a function with the specified parameters.
You can also define functions using the Function constructor and a function expression.

function calcRectArea(width, height) {
  return width * height;
}
console.log(calcRectArea(5, 6));
 expected output: 30

## Syntax
function name([param[, param,[..., param]]]) {
   [statements]
}

## Name
The name of an argument to be passed to the function. Maximum number of arguments varies in different engines.
statements Optional
The statements which comprise the body of the function.
## Description
A function created with a function declaration is a Function object and has all the properties, methods and behavior of Function objects. See Function for detailed information on functions.
A function can also be created using an expression (see function expression).
By default, functions return undefined. To return any other value, the function must have a return statement that specifies the value to return.


## Conditionally created functions
Functions can be conditionally declared, that is, a function statement can be nested within an if statement, however the results are inconsistent across implementations and therefore this pattern should not be used in production code. For conditional function creation, use function expressions instead.

var hoisted = "foo" in this;
console.log(`'foo' name ${hoisted ? "is" : "is not"} hoisted. typeof foo is ${typeof foo}`);
if (false) {
  function foo(){ return 1; }
}

// In Chrome:
// 'foo' name is hoisted. typeof foo is undefined
//
// In Firefox:
// 'foo' name is hoisted. typeof foo is undefined
//
// In Edge:
// 'foo' name is not hoisted. typeof foo is undefined
//
// In Safari:
// 'foo' name is hoisted. typeof foo is function
The results are exactly the same for a condition that evaluates to true

var hoisted = "foo" in this;
console.log(`'foo' name ${hoisted ? "is" : "is not"} hoisted. typeof foo is ${typeof foo}`);
if (true) {
  function foo(){ return 1; }
}

// In Chrome:
// 'foo' name is hoisted. typeof foo is undefined
//
// In Firefox:
// 'foo' name is hoisted. typeof foo is undefined
//
// In Edge:
// 'foo' name is not hoisted. typeof foo is undefined
//
// In Safari:
// 'foo' name is hoisted. typeof foo is function

## Function declaration hoisting
Function declarations in JavaScript are hoisted to the top of the enclosing function or global scope. You can use the function before you declared it:

hoisted(); // logs "foo"

function hoisted() {
  console.log('foo');
}
Note that function expressions are not hoisted:

notHoisted(); // TypeError: notHoisted is not a function

var notHoisted = function() {
   console.log('bar');
};