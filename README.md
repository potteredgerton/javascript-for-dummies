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


## Functions 

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
In this example, we call the square function by using the square variable name and passing in the value 4 as the num parameter. The function then executes and returns the value 16, which we assign to the result variable. We then log the value of result to the console using console.log(), and the output is 16.
</code>
</pre>

That's it! With these basic concepts, you can start using and creating functions in your JavaScript code. As you continue learning, you'll discover more advanced features and techniques for working with functions.
