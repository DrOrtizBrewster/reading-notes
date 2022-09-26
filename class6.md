# What I Learned in My Readings

## Class Six Notes

### JavaScript

* A programming language.
* Mostly known as the scripting language for Web pages
* Also, many non-browser environments use it, such as Node.js, Apache CouchDB and Adobe Acrobat. 
* JavaScript is different from Java.

### Introduction to JavaScript - basic oputput

* Traditionally, JavaScript was used inside web browers.
* The authore would include some JavaScript in the HTML page the user receives when they visit a web site.
* Three major parts of JavaScript
    * Language that is on various browsers and server-side environments.
    The DOM API - how the language can interact with the various parts of a web page while in the browser. 
    *The server API provided by Node.js or one of the other server-side systems.
* You can either embed the JavaScript code directly inside the HTML file, or you can put a line in the HTML file that will include the external JavaScript file. 
* There are a number of way JavaScript can display text for the user (output). The most simple one is by using the alert function.

### JavaScript input with prompt and cofirm

* To use input - prompt - It will show a pop-up window with the text provided as the first parameter and with a textbox the user can fill in. When the user presses OK, the value in the text box will be returned by the prompt() function. in.
* The textbox will be pre-filled with the content of the second parameter. This can be very useful if we would like to ask the user to edit some value. We can pre-fill the box with the old value.
* In either case, if the user presses cancel or hits the ESC the prompt() function will return null.
 * The other pop-up is not really an input method. It allows the developer to ask a Yes/No question. Calling the confirm() function will show a pop-up window with the provided texts and with two buttons. If the user presses OK the confirm() function will return true, if the user presses cancel or hits the ESC key, the function will return false.
* Of course in order for this to make more sense you'll have to understand what true and false really mean and what this if - else construct does. If you have programming background then you probably already understand the code, and even if you don't have programming background you might figure out.

### Variables

* Variables are containers for storing data (storing data values).
* Always declare JavaScript variables with var,let, orconst.
* The var keyword is used in all JavaScript code from 1995 to 2015.
* The let and const keywords were added to JavaScript in 2015.
* If you want your code to run in older browsers, you must use var.
* If you want a general rule: always declare variables with const.
* If you think the value of the variable can change, use let.
* In this example, price1, price2, and total, are variables

### How Computers Work

* Input - whaat you do to make the computer work
* Storage and Processing - storage-processing via algorithms -then output
Output - Depends what type of computer it is - dispaly, robot, etc.
* Input - storage - process - output
Data & Binary - Bit - smallest piece of information - yes/no, true/false, 1/0
Decimal - 0-9 Binary - 0 or 1
* Text in binary - 
*Images - pixels also represented in numbers 
* Sound Binary - Vibrations can be represented on a sound waverform and then broken down into numbers
* More bits equals more numbers
* Adder - two bits
*Input devices - keyboard, mic, nouse, camera
* Memory - stores information
* CPU - central processing unit calculates information - Output - display monitor, robot, phone, printer
* CPU is the master chip that tells everything else what to do - it has circuits to do math and logic - other circuits to send information to ohter parts

* Data Types: String, Number, Boolean
* Const, Var, and Let are used to declare a variable
* Can't change it once it is assigned.
* JavaScript reads from top to bottom

* prompt("what is your favorite color?"); This is what type of inforamtion do you want on your site.
* Whatever you type in is the value of the prompt
        let usersColor = prompt("What is your favorite color?");

If you happen to use Chrome on OSX you can open the console using: Command-Option-J.
* The document.write() method should only be used for testing.
* For debugging purposes, you can call the console.log() method in the browser to display data.
* A computer program is a list of "instructions" to be "executed" by a computer.

In a programming language, these programming instructions are called statements.

A JavaScript program is a list of programming statements.
* JavaScript statements are composed of:

Values, Operators, Expressions, Keywords, and Comments.
* Semicolons separate JavaScript statements.

Add a semicolon at the end of each executable statement:
When separated by semicolons, multiple statements on one line are allowed: a = 5; b = 6; c = a + b;
*JavaScript ignores multiple spaces. You can add white space to your script to make it more readable.
* Numbers are written with or without decimals:
* Strings are text, written within double or single quotes:
* In a programming language, variables are used to store data values.

JavaScript uses the keywords var, let and const to declare variables.

An equal sign is used to assign values to variables.
* JavaScript uses arithmetic operators ( + - * / ) to compute values:
* JavaScript uses an assignment operator ( = ) to assign values to variables:
* An expression is a combination of values, variables, and operators, which computes to a value.

The computation is called an evaluation.

For example, 5 * 10 evaluates to 50:
* The let keyword tells the browser to create variables:
* Code after double slashes // or between /* and */ is treated as a comment.

Comments are ignored, and will not be executed:
* Hyphens are not allowed in JavaScript. They are reserved for subtractions.

* Hyphens are not allowed in JavaScript. They are reserved for subtractions.

* Any text between /* and */ will be ignored by JavaScript.
* Single line comments start with //.

Any text between // and the end of the line will be ignored by JavaScript (will not be executed).
* All JavaScript variables must be identified with unique names.

These unique names are called identifiers.
* In JavaScript we have the following conditional statements:

Use if to specify a block of code to be executed, if a specified condition is true
Use else to specify a block of code to be executed, if the same condition is false
Use else if to specify a new condition to test, if the first condition is false
Use switch to specify many alternative blocks of code to be executed