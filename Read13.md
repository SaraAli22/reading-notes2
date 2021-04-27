# List
* There are three types of HTML lists: ordered,
unordered, and definition.

* Ordered lists use numbers.

* Unordered lists use bullets.

* Definition lists are used to define terminology.

* Lists can be nested inside one another.
![image](https://i2.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/01/ordered-list.jpg?fit=474%2C397&ssl=1)

HTML offers web authors three ways for specifying lists of information. All lists must contain one or more list elements. Lists may contain :

ul − An unordered list. This will list items using plain bullets.

ol − An ordered list. This will use different schemes of numbers to list your items.

dl − A definition list. This arranges your items in the same way as they are arranged in a dictionary.

# Boxes
* *SS treats each HTML element as if it has its own box.

* You can use CSS to control the dimensions of a box. 

* You can also control the borders, margin and padding for each box with CSS.

* It is possible to hide elements using the display and visibility properties.

* Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.

* Legibility can be improved by controlling the width of boxes containing text and the leading.

* CSS3 has introduced the ability to create image borders and rounded borders.

## Block and inline boxes
In CSS we broadly have two types of boxes — block boxes and inline boxes. These characteristics refer to how the box behaves in terms of page flow, and in relation to other boxes on the page:

If a box is defined as a block, it will behave in the following ways:

* The box will break onto a new line.
* The box will extend in the inline direction to fill the space available in its container. In most cases this means that the box will become as wide as its container, filling up 100% of the space available.
* The width and height properties are respected.
* Padding, margin and border will cause other elements to be pushed away from the box Unless we decide to change the display type to inline, elements such as headings (e.g. h1) and p all use block as their outer display type by default.

If a box has an outer display type of inline, then:

* The box will not break onto a new line.
* The width and height properties will not apply.
* Vertical padding, margins, and borders will apply but will not cause other inline boxes to move away from the box.
* Horizontal padding, margins, and borders will apply and will cause other inline boxes to move away from the box.
![image](https://lh3.googleusercontent.com/proxy/RUMkk6rXfpPtOG_hFlMYT8G1Zr21MCGw28Pk-u4ZIWOkzjLqd5W5EXM_aASRvgJ8DqAgSUmKRlr_XMkTWnFLihR62D_U0UToTMgQ)
![image](https://static.javatpoint.com/csspages/images/how-to-add-a-border-in-css2.png)

# ARRAYS
An array is a special type of variable. It doesn't just store one value; it stores a list of values.

Creating an Array
Using an array literal is the easiest way to create a JavaScript Array.

Syntax:

var array_name = [item1, item2, ...]; 

**Using the JavaScript Keyword new
The following example also creates an Array, and assigns values to it:**
Example
var cars = new Array("Saab", "Volvo", "BMW");

**Access the Elements of an Array
You access an array element by referring to the index number.**

This statement accesses the value of the first element in cars:

var name = cars[0];
![image](https://i.stack.imgur.com/qkZqF.png)

# Decision and loop 
* Conditional statements allow your code to make decisions about what to do next.

* Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>) are used to compare two operands.

* Logical operators allow you to combine more than one set of comparison operators.

* if ... else statements allow you to run one set of code if a condition is true, and another if it is false.

 * switch statements allow you to compare a value against possible outcomes (and also provides a default option if none match).

* Data types can be coerced from one type to another.

* All values evaluate to either truthy or falsy.

* There are three types of loop: for, while, and do ... while. Each repeats a set of statements. 