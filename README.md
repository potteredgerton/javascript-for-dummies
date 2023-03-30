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

Number: This data type is used to represent numeric values. Numbers can be positive, negative, or decimal. Here's an example:

<pre>
<code>
let age = 27;
let temperature = -10.5;
</code>
</pre>

In this example, we define two variables called age and temperature that are both of the Number data type.

String: This data type is used to represent text values. Strings are enclosed in single or double quotes. Here's an example:

<pre>
<code>
let name = "John";
let message = 'Hello, world!';
</code>
</pre>

In this example, we define two variables called name and message that are both of the String data type.

Boolean: This data type is used to represent true/false values. Here's an example:

<pre>
<code>
let isRainy = true;
let isSunny = false;
</code>
</pre>

In this example, we define two variables called isRainy and isSunny that are both of the Boolean data type.

Array: This data type is used to represent a collection of values. Arrays are enclosed in square brackets and can contain any combination of data types. Here's an example:

<pre>
<code>
let numbers = [1, 2, 3, 4, 5];
let fruits = ["apple", "banana", "orange"];
</code>
</pre>

In this example, we define two variables called numbers and fruits that are both of the Array data type.

Object: This data type is used to represent a collection of key-value pairs. Objects are enclosed in curly braces and can contain any combination of data types. Here's an example:

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

That's it! With these basic concepts, you can start using data types in your JavaScript code. As you continue learning, you'll discover more advanced features and techniques for working with data types.

## Chapter 3: Operators

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
