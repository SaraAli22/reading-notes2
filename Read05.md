# Decision and Loops

** Comparision Operators: Evaluating Conditions **

In JavaScript, there are a number of comparison operators that you can use to evaluate whether given values are different or equal, as well as if a value is greater than or less than another. Often, these operators are used with stored values in variables.Comparison operators all return a Boolean (logical) value of true or false.

![image](https://images.slideplayer.com/26/8394316/slides/slide_2.jpg)

*The table below summarizes the comparison operators available in JavaScript.*

|Operator |	What it means |
|---------|---------------|
|==	|Equal to|
|!=	|Not equal to|
|===|	Strictly equal to with no type conversion|
|! ==	|Strictly unequal to with no type conversion|
|>	|Greater than|
|>=	|Greater than or equal to|
|<|	Less than|
|<=	Less than or equal to|


![image](https://i.pinimg.com/originals/87/10/26/8710268553cee427b57cc2e019c68e5e.png)


* **Equality** :The equality operator measures whether values on either side of the operator are equal.

* **Inequality**:The != operator tests inequality, to determine whether the values on either side of the operator are not equal.

* **Identity**:The === operator determines whether two values are both of equal value and of equal type. This is also known as a strict equality operator. This means you cannot mix number and string data types

* **Non Identity** :Like ===, the operator !== evaluates a strict inequality, which considers both the value and the type of the operands on either side of the operator.

* **Greater than**:The greater than symbol in JavaScript may be familiar to you from math: >. This evaluates whether one value (on the left side of the expression) is greater than another value (on the right side of the expression).
Like the == operator above, the greater than operator is not strict, and therefore will allow you to mix strings and numbers.

* **Greater than or equal**:Similarly, the operator for greater than or equal to will evaluate whether one operand meets the threshold of the other. This operator is typed as >= a kind of compound between greater than (>) and the equal sign (=)

* **Less than**:The less than operator appears as the mirror version of the greater than operator: <.

* **Less than or equal**:The opposite of greater than or equal, the less than or equal operator <=  will evaluate whether the value on the left side of the operator is less than or equal to the value on the right side.

## Logical Operators
In JavaScript, there are three logical operators, which connect two or more programming statements to return a true (also called “truthy”) or false (“falsy”) value. These are most often used with Boolean (logical) types, but can be applied to values of any data type.

These logical operators are summarized in the table below.

|Operator|	Syntax  |	Description|
|-------|-------- |------------|
|AND	|&&	|Returns true if both operands are true|
|OR|	II	|Returns true if either operand is true |
|NOT|	!	|Returns true if operand is false|

 * **AND**
The AND operator is represented by two ampersands  && —it will return true if the operands to the left and right evaluate to be true.

* **OR** 
The OR operator is represented by two pipes || it will return true if one of the operands is true.

* **NOT**
The NOT operator is represented by an exclamation point ! it will return true if the operand is set to false, and vice versa.
![image](https://i.ytimg.com/vi/JVL6xEzOCrE/maxresdefault.jpg)