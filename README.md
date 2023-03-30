# Javascript for Dummies
A Javascript Tutorial for dummies


## Variables

In JavaScript, a variable is a container that stores a value. You can declare a variable using the var, let, or const keywords.

The var keyword was used to declare variables in older versions of JavaScript, but it is now considered outdated. Instead, it's recommended to use let or const.

Here's how to declare a variable using let or const:

<pre>
<code>
let myVariable = "Hello, world!";
const myConstant = 42;
</code>
</pre>

In the example above, myVariable is a variable that stores a string value, and myConstant is a variable that stores a number value. Note that myConstant is declared using const, which means its value cannot be changed once it is assigned.

Once you've declared a variable, you can use it throughout your code. Here's an example:

<pre>
<code>
let myVariable = "Hello, world!";
console.log(myVariable); // Output: "Hello, world!"
myVariable = "Goodbye, world!";
console.log(myVariable); // Output: "Goodbye, world!"
</code>
</pre>

In the example above, we declare myVariable with the value "Hello, world!". We then log the value of myVariable to the console using console.log(). The output is "Hello, world!". We then assign a new value to myVariable and log it to the console again. This time, the output is "Goodbye, world!".

You can also use variables to store the result of expressions or calculations. Here's an example:

<pre>
<code>
let num1 = 5;
let num2 = 10;
let result = num1 + num2;
console.log(result); // Output: 15
</code>
</pre>

In the example above, we declare two variables, num1 and num2, with the values 5 and 10, respectively. We then declare a third variable, result, and assign it the value of num1 + num2, which is 15. We log the value of result to the console using console.log(), and the output is 15.

## Chapter 2: Data types

JavaScript has several built-in data types that are used to represent different kinds of values. Here are the most common data types:

### Number
This data type is used to represent numeric values. Numbers can be positive, negative, or decimal. Here's an example:

<pre>
<code>
let age = 27;
let temperature = -10.5;
</code>
</pre>

In this example, we define two variables called age and temperature that are both of the Number data type.

### String
This data type is used to represent text values. Strings are enclosed in single or double quotes. Here's an example:

<pre>
<code>
let name = "John";
let message = 'Hello, world!';
</code>
</pre>

In this example, we define two variables called name and message that are both of the String data type.

### Boolean
This data type is used to represent true/false values. Here's an example:

<pre>
<code>
let isRainy = true;
let isSunny = false;
</code>
</pre>

In this example, we define two variables called isRainy and isSunny that are both of the Boolean data type.

###Array 
This data type is used to represent a collection of values. Arrays are enclosed in square brackets and can contain any combination of data types. Here's an example:

<pre>
<code>
let numbers = [1, 2, 3, 4, 5];
let fruits = ["apple", "banana", "orange"];
</code>
</pre>

In this example, we define two variables called numbers and fruits that are both of the Array data type.

###Object 
This data type is used to represent a collection of key-value pairs. Objects are enclosed in curly braces and can contain any combination of data types. Here's an example:

<pre>
<code>
let person = {
  name: "John",
  age: 27,
  isStudent: true
};
</code>
</pre>

In this example, we define a variable called person that is of the Object data type. The person object has three key-value pairs: name with a value of "John", age with a value of 27, and isStudent with a value of true.

To access the value of a variable, we can simply use the variable name. For example:

<pre>
<code>
console.log(name); // Output: "John"
console.log(isSunny); // Output: false
console.log(fruits[0]); // Output: "apple"
console.log(person.age); // Output: 27
</code>
</pre>

In this example, we use console.log() to print the value of the name, isSunny, fruits[0], and person.age variables to the console.

## Chapter 3: Operators

Operators are symbols that perform operations on one or more values (operands) to produce a new value. JavaScript has several types of operators, including arithmetic, comparison, logical, and assignment operators.

Arithmetic operators: These operators perform mathematical calculations on numeric values. Here are some common arithmetic operators:
+ Addition: Adds two values together.
- Subtraction: Subtracts one value from another.
* Multiplication: Multiplies two values together.
/ Division: Divides one value by another.
% Modulus: Returns the remainder of a division operation.
Here's an example of using arithmetic operators:

<pre>
<code>
let x = 5;
let y = 2;

let sum = x + y; // 7
let difference = x - y; // 3
let product = x * y; // 10
let quotient = x / y; // 2.5
let remainder = x % y; // 1
</code>
</pre>

Comparison operators: These operators compare two values and return a Boolean value (true or false). Here are some common comparison operators:
== Equal to: Returns true if two values are equal.
!= Not equal to: Returns true if two values are not equal.
> Greater than: Returns true if the first value is greater than the second value.
< Less than: Returns true if the first value is less than the second value.
>= Greater than or equal to: Returns true if the first value is greater than or equal to the second value.
<= Less than or equal to: Returns true if the first value is less than or equal to the second value.
Here's an example of using comparison operators:

<pre>
</code>
let age = 27;

console.log(age == 27); // true
console.log(age != 27); // false
console.log(age > 30); // false
console.log(age < 30); // true
console.log(age >= 27); // true
console.log(age <= 27); // true
</code>
</pre>

Logical operators: These operators are used to combine or invert Boolean values. Here are some common logical operators:
&& Logical AND: Returns true if both values are true.
|| Logical OR: Returns true if at least one value is true.
! Logical NOT: Inverts the Boolean value.
Here's an example of using logical operators:

<pre>
<code>
let isSunny = true;
let isWarm = true;

console.log(isSunny && isWarm); // true
console.log(isSunny || isWarm); // true
console.log(!isSunny); // false
</code>
</pre>

Assignment operators: These operators are used to assign values to variables. Here are some common assignment operators:
= Simple assignment: Assigns a value to a variable.
+= Addition assignment: Adds a value to a variable and assigns the result to the variable.
-= Subtraction assignment: Subtracts a value from a variable and assigns the result to the variable.
*= Multiplication assignment: Multiplies a variable by a value and assigns the result to the variable.
/= Division assignment: Divides a variable by a value and assigns the result to the variable.
%= Modulus assignment: Calculates the remainder of a variable divided by a value and assigns the result to the variable.
Here's an example of using assignment operators:

<pre>
<code>
let x = 10;
let y = 2;

x += y; // equivalent to x = x + y;
console.log(x); // 12

x -= y; // equivalent to x = x - y;
console.log(x); // 10

x *= y; // equivalent to x = x * y;
console.log(x); // 20

x /= y; // equivalent to x = x / y;
console.log(x); // 10

x %= y; // equivalent to x = x % y;
console.log(x); // 0
</code>
</pre>

String operators: In addition to the arithmetic operators, JavaScript also has string operators:
+ Concatenation: Joins two or more strings together.
Here's an example of using string operators:

<pre>
<code>
let firstName = 'John';
let lastName = 'Doe';

let fullName = firstName + ' ' + lastName;
console.log(fullName); // John Doe
</code>
</pre>

Type operators: These operators are used to determine the data type of a value. Here are some common type operators:
typeof Returns a string that represents the data type of the value.
Here's an example of using type operators:

<pre>
<code>
let age = 27;
let name = 'John';
let isMarried = false;

console.log(typeof age); // number
console.log(typeof name); // string
console.log(typeof isMarried); // boolean
</code>
</pre>

## Chapter 4: Functions 

Functions in JavaScript are reusable blocks of code that perform a specific task. They can accept inputs (called parameters) and return outputs (called return values). Here's an example of a simple function:

<pre>
<code>
function greet(name) {
  console.log("Hello, " + name + "!");
}
</code>
</pre>

This function is called greet, and it accepts one parameter called name. The function uses console.log() to print a greeting message to the console, with the name parameter inserted into the message.

To call the function and pass in a value for the name parameter, we simply write:

<pre>
<code>
greet("John"); // Output: "Hello, John!"
</code>
</pre>

In this example, we call the greet() function and pass in the string "John" as the value for the name parameter. The function then executes and prints the greeting message to the console.

Functions can also return values using the return keyword. Here's an example:

<pre>
<code>
function add(num1, num2) {
  return num1 + num2;
}
</code>
</pre>

This function is called add, and it accepts two parameters called num1 and num2. The function returns the result of adding num1 and num2 together using the + operator.

To call the function and get the return value, we can assign the result to a variable, like this:

<pre>
<code>
let result = add(3, 5);
console.log(result); // Output: 8
</code>
</pre>

In this example, we call the add() function and pass in the values 3 and 5 as the num1 and num2 parameters. The function then executes and returns the value 8, which we assign to the result variable. We then log the value of result to the console using console.log(), and the output is 8.

Functions can also be assigned to variables, like this:

<pre>
<code>
let square = function(num) {
  return num * num;
};
</code>
</pre>

In this example, we define a function called square that accepts one parameter called num. The function returns the result of multiplying num by itself using the * operator. We then assign the function to a variable called square.

To call the function, we can use the variable name instead of the function name, like this:

<pre>
<code>
let result = square(4);
console.log(result); // Output: 16
</code>
</pre>

In this example, we call the square function by using the square variable name and passing in the value 4 as the num parameter. The function then executes and returns the value 16, which we assign to the result variable. We then log the value of result to the console using console.log(), and the output is 16.
