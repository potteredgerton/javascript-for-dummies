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
