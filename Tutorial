## JAVASCRIPT DISPLAY POSSIBILITIES.

## WHAT IS JAVASCRIPT DISPLAY POSSIBILITIES?
JavaScript display output or display possibilities is the feasible ways of displaying the output of a given code. 

## JavaScript Display Possibilities
The output can be display by using four different ways which are listed below:

## innerHTML:
This method sets or returns the HTML content of an element. it is also used to access an element.

Example:
<p id="cool">hey</p>
<script>
document.getElementById('cool').innerHTML = "Hello world!";
</script>.

## document.write():
This method is mostly used for testing purpose. it is used to write some content or JavaScript code in a Document. also used to delete all the content from the HTML document and inserts the new content.

<script>
document.write('How are you?');
</script>

## window.alert():
It is use to display an alert box on the window. The alert box is mostly used when you want an information to come through to the user. It is displayed with a message and an OK button.

<script>
window.alert("Hello world!")
alert(" HEY!" )
</script>
NOTE: These are both the same syntax.

## console.log():
The console.log() method outputs a message to the web console. The message may be a single string or it may be any one or more JavaScript objects.

<script>
console.log(6+3)
</script>

## JavaScript Print
window.print() method in the browser is call to print the content of the current window.

## JavaScript Statements
Javascript statements are list of javascript instructions found in javascript program.

JavaScript statements are composed of: Values, Operators, Expressions, Keywords, and Comments.

## break statement
The break statement terminates the current loop or switch statement and transfers program control to the statement following the terminated statement. It can also be used to jump past a labeled statement when used within that labeled statement.

let i = 0;

while (i < 6) {
  if (i === 3) {
    break;
  }
  i = i + 1;
}

console.log(i);
// Break out of a loop when i is 3.

## class	
Declares a class

Example
class Car {
constructor(brand) {
    this.carname = brand;
  }
}

myCar = new Car("Ford");

Create a Car class, and then an object (myCar) based on the Car class:

## const	
Declares a variable, array or object with a constant value

//Declares variables
const total = 600;
const name = "Volvo";


// Create an array:
const cars = ["Saab", "Volvo", "BMW"];

// Create an object:
const car = {type:"Fiat", model:"500", color:"white"};

## continue	
Breaks one iteration (in the loop) if a specified condition occurs, and continues with the next iteration in the loop

//Loop through a block of code, but skip the value of 3

let text = "";
for (let i = 0; i < 5; i++) {
  if (i === 3) continue;
  text += i + "<br>";
}

let text = "";
let i = 0;
while (i < 5) {
  i++;
  if (i === 3) continue;
  text += i + "<br>";
}

## debugger	
Stops the execution of JavaScript.

## do ... while	
Executes a block of statements and repeats the block while a condition is true

Example:

let text = "";
let i = 0;
do {
  text += i + "<br>";
  i++;
}
while (i < 5);

## for	
Loops through a block of code a number of times

//Loop through a code block five times:

for (let i = 0; i < 5; i++) {
  text += i + "<br>";
}

//Loop through an array to collect car names:

const cars = ["BMW", "Volvo", "Saab", "Ford"];
for (let i = 0; i < cars.length; i++) {
  text += cars[i] + "<br>";
}

## for ... in	
Loops through the properties of an object

//Iterate over the properties of an object:

const person = {fname:"John", lname:"Doe", age:25};
let text = "";
for (let x in person) {
  text += person[x] + " ";
}

//Iterate over the values of an array:

const cars = ["BMW", "Volvo", "Saab", "Ford"];
let text = "";
for (let x in cars) {
  text += cars[x] + " ";
}

## for ... of	
Loops through the values of an iterable object

//Iterate over the values of an array

let text = "";
const cars = ['BMW', 'Volvo', 'Mini'];
for (let x of cars) {
  text += x + " ";
}

//Iterate over the values of a string:

let text = "JavaScript";
for (let x of text) {
  text += x + " ";
}

## function	
Declares a function

Example
Declare a function that outputs "Hello World" when it is called

// Declare a function
function myFunction() {
  document.getElementById("demo").innerHTML = "Hello World!";
}

// Call the function
myFunction();

## if ... else ... else if	
Marks a block of statements to be executed depending on a condition

Examples
// If the hour is less than 20, output "Good day":

let hour = new Date().getHours();
if (hour < 20) {
  document.getElementById("demo").innerHTML = "Good day";
}

// Output "Good day" or "Good evening":

let hour = new Date().getHours();
if (hour < 20) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}

## let	
Declares a variable

Example
// Declares a variable called carName and assign the value "Volvo" to it:
let carName = "Volvo";

return	
Stops the execution of a function and returns a value from that function

Examples
// Return the value of PI:

function myFunction() {
  return Math.PI;
}
Return "Hello John":

document.getElementById("demo").innerHTML = myFunction("John");

function myFunction(name) {
  return "Hello " + name;
}

## switch	
Marks a block of statements to be executed depending on different cases

Example

// Execute a block of code based on user input:
var text;
var fruits = document.getElementById("myInput").value;

switch(fruits) {
  case "Banana":
    text = "Banana is good!";
    break;
  case "Orange":
    text = "I am not a fan of orange.";
    break;
  case "Apple":
    text = "How you like them apples?";
    break;
  default:
    text = "I have never heard of that fruit...";
}

## throw	
Throws (generates) an error

Example
This example examines input. If the value is wrong, an exception (err) is thrown:

<p>Please input a number between 5 and 10:</p>

<input id="demo" type="text">
<button type="button" onclick="myFunction()">Test Input</button>
<p id="message"></p>

<script>
function myFunction() {
  const message = document.getElementById("message");
  message.innerHTML = "";
  let x = document.getElementById("demo").value;
  try {
    if(x == "") throw "is Empty";
    if(isNaN(x)) throw "not a number";
    if(x > 10) throw "too high";
    if(x < 5) throw "too low";
  }
  catch(err) {
    message.innerHTML = "Input " + err;
  }
}
</script>

## try ... catch ... finally	
Marks the block of statements to be executed when an error occurs in a try block, and implements error handling

Example
// This example has a typo in the try block. Alert is misspelled.The catch block catches the error and executes the code to handle it

<p id="demo"></p>

<script>
try {
  adddlert("Welcome guest!");
}
catch(err) {
  document.getElementById("demo").innerHTML = err.message;
}
</script>

## var	
Declares a variable

// Create a variable called carName and assign the value "Volvo" to it:
var carName = "Volvo";

## while	
Marks a block of statements to be executed while a condition is true

//Loop a code block as long as a i is less than 5:

let text = "";
let i = 0;
while (i < 5) {
  text += i + "<br>";
  i++;
}
Loop (iterate over) an array to collect car names:

const cars = ["BMW", "Volvo", "Saab", "Ford"];
let text = "";
let i = 0;
while (i < cars.length) {
  text += cars[i] + "<br>";
  i++;
}

NOTE: A JavaScript program is a list of programming statements. In HTML, JavaScript programs are executed by the web browser. Most JavaScript programs contain many JavaScript statements. The statements are executed, one by one, in the same order as they are written. JavaScript programs (and JavaScript statements) are often called JavaScript code.

## JavaScript keywords. These are javascript reserved words that cannot be used as variables, labels, or function names: 
abstract	  arguments	    await*	    boolean
break	      byte	        case	        catch
char	      class*	      const*	      continue
debugger	  default	      delete	      do
double	    else	        enum*	        eval
export*	    extends*	    false	        final
finally	    float	        for	          function
goto	      if	          implements	  import*
in	        instanceof	  int	          interface
let*	      long	        native	      new
null	      package	      private	      protected
public	    return	      short	        static
super*	    switch	      synchronized	this
throw	      throws	      transient	    true
try	        typeof	      var	          void
volatile	  while	        with	        yield

## Semicolons ;
Semicolons separate JavaScript statements.

Add a semicolon at the end of each executable statement:

Examples
let a, b, c;  // Declare 3 variables
a = 5;        // Assign the value 5 to a
b = 6;        // Assign the value 6 to b
c = a + b;    // Assign the sum of a and b to c

When separated by semicolons, multiple statements on one line are allowed:
e.g
a = 5; b = 6; c = a + b;

although ending statements with semicolon is not required, but highly recommended.

## JavaScript White Space

JavaScript ignores multiple spaces. You can add white space to your script to make it more readable.

The following lines are equivalent:

let person = "Ronny";
let person="Ronny";

A good practice is to put spaces around operators ( = + - * / ):

let x = y + z;

## JavaScript Line Length and Line Breaks

For best readability, programmers often like to avoid code lines longer than 80 characters. If a JavaScript statement does not fit on one line, the best place to break it is after an operator:

Example

document.getElementById("demo").innerHTML =
"Hello Dolly!";

## JavaScript Code Blocks

JavaScript statements can be grouped together in code blocks, inside curly brackets {...}. The purpose of code blocks is to define statements to be executed together.

One place you will find statements grouped together in blocks, is in JavaScript functions:

Example
function myFunction() {
  document.getElementById("demo1").innerHTML = "Hello Dolly!";
  document.getElementById("demo2").innerHTML = "How are you?";
}

## JavaScript Syntax
JavaScript syntax is the set of rules, how JavaScript programs are constructed:

How to create variables:
var x;
let y;

How to use variables:
x = 5;
y = 6;
let z = x + y;

## JavaScript Values
The JavaScript syntax defines two types of values:

Fixed values
Variable values

Fixed values are called Literals.

Variable values are called Variables.

## JavaScript Literals
The two most important syntax rules for fixed values are:

1. Numbers are written with or without decimals:

10.50

1001

2. Strings are text, written within double or single quotes:

"John Smith"

'John Smith'

## JavaScript Variables
In a programming language, variables are used to store data values.

JavaScript uses the keywords var, let and const to declare variables.

An equal sign is used to assign values to variables.

In this example, x is defined as a variable. Then, x is assigned (given) the value 6:

let x;
x = 6;

## JavaScript Operators
JavaScript uses arithmetic operators ( + - * / ) to compute values:

(5 + 6) * 10

JavaScript uses an assignment operator ( = ) to assign values to variables:

let x, y;
x = 5;
y = 6;

## JavaScript Expressions
An expression is a combination of values, variables, and operators, which computes to a value.

The computation is called an evaluation.

For example, 5 * 10 evaluates to 50:

5 * 10
Expressions can also contain variable values:

x * 10
The values can be of various types, such as numbers and strings.

For example, "John" + " " + "Smith", evaluates to "John Smith":

"John" + " " + "Smith"

## JavaScript Comments

Not all JavaScript statements are "executed".

Code after double slashes // or between /* and */ is treated as a comment.

Comments are ignored, and will not be executed:

let x = 5;   // This will be executed

// x = 6;   This will NOT be executed


## JavaScript Identifiers / Names

Identifiers are JavaScript names. Identifiers are used to name variables and keywords, and functions. The rules for legal names are the same in most programming languages.

A JavaScript name must begin with:

A letter (A-Z or a-z)
A dollar sign ($)
Or an underscore (_)
Subsequent characters may be letters, digits, underscores, or dollar signs.

Note
Numbers are not allowed as the first character in names. This way JavaScript can easily distinguish identifiers from numbers.

## JavaScript is Case Sensitive
All JavaScript identifiers are case sensitive. 

The variables lastName and lastname, are two different variables:

let lastname, lastName;
lastName = "Doe";
lastname = "Peterson";
JavaScript does not interpret LET or Let as the keyword let.

## JavaScript and Camel Case
Historically, programmers have used different ways of joining multiple words into one variable name:

## Hyphens:

first-name, last-name, master-card, inter-city.

Hyphens are not allowed in JavaScript. They are reserved for subtractions.

## Underscore:

first_name, last_name, master_card, inter_city.

## Upper Camel Case (Pascal Case):

FirstName, LastName, MasterCard, InterCity.

## Lower Camel Case:

JavaScript programmers tend to use camel case that starts with a lowercase letter:

firstName, lastName, masterCard, interCity.


## JavaScript Comments
JavaScript comments can be used to explain JavaScript code, and to make it more readable.

JavaScript comments can also be used to prevent execution, when testing alternative code.

## Single Line Comments
Single line comments start with //.

Any text between // and the end of the line will be ignored by JavaScript (will not be executed).

This example uses a single-line comment before each code line:

Example
// Change heading:
document.getElementById("myH").innerHTML = "My First Page";

// Change paragraph:
document.getElementById("myP").innerHTML = "My first paragraph.";

## This example uses a single line comment at the end of each line to explain the code:

Example
let x = 5;      // Declare x, give it the value of 5
let y = x + 2;  // Declare y, give it the value of x + 2
Multi-line Comments
Multi-line comments start with /* and end with */.

Any text between /* and */ will be ignored by JavaScript.

## This example uses a multi-line comment (a comment block) to explain the code:

Example
/*
The code below will change
the heading with id = "myH"
and the paragraph with id = "myP"
in my web page:
*/
document.getElementById("myH").innerHTML = "My First Page";
document.getElementById("myP").innerHTML = "My first paragraph.";

It is most common to use single line comments.
Block comments are often used for formal documentation.

## Using Comments to Prevent Execution
Using comments to prevent execution of code is suitable for code testing.

Adding // in front of a code line changes the code lines from an executable line to a comment.

## This example uses // to prevent execution of one of the code lines:

Example
//document.getElementById("myH").innerHTML = "My First Page";
document.getElementById("myP").innerHTML = "My first paragraph.";

## This example uses a comment block to prevent execution of multiple lines:

Example
/*
document.getElementById("myH").innerHTML = "My First Page";
document.getElementById("myP").innerHTML = "My first paragraph.";
*/


## JavaScript Character Set
JavaScript uses the Unicode character set.