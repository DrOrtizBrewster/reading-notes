# What I Learned in My Readings

## Class Seven Notes

### Control Flow

* The control flow is the order in which the computer executes statements in a script.

* Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.

* For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:

**Example of a conditional structure**
if (isEmpty(field)) {
  promptUser();
} else {
  submitForm();
}

* A typical script in JavaScript or PHP (and the like) includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.
* The above excerpt might be inside a function that runs when the user clicks the Submit button for the form.
* The function could also include a loop, which iterates through all of the fields in the form, checking each one in turn. 
* Looking back at the code in the if and else sections, the lines ***promptUser*** and *****submitForm*** could also be calls to other functions in the script.
* Control structures can dictate complex flows of processing even with only a few lines of code.

* Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

### Loop

* A loop is a sequence of instructions that is continually repeated until a certain condition is met in computer programming. 
* An example would be the process of getting an item of data and changing it, and then making sure some condition is checked such as, if a counter has reached a prescribed number.

**Example of a loop**

for (statement 1; statement 2; statement 3) {
  execute code block
}

*Statement 1 is executed once before the code block is run.
Statement 2 defines the condition needed to execute the code block.
Statement 3 is executed every time the code block is run.

for (let i = 0; i < 10; i++) {
  console.log(i);
}
//This loop will print numbers 0-9, will stop when condition is met (i = 10)

For the above example, the syntax is as follows:

Statement 1 sets the variable for the loop (let i = 0).
Statement 2 sets the loop condition (i < 10).
Statement 3 increases the value of i (i++) each time the code block is run.
While loop
Syntax
while (condition) {
  execute code block
}
The code block will continue to loop as long as the condition is true.
Example
let i = 0;
while (i < 5) {
  console.log(i);
  i++;
}
//This loop will print number 0-4, will stop when condition becomes false (i >=5)
Copy to Clipboard
For the above example, the syntax is as follows:

The code block will continue to run as long as the variable (i) is less than 5.

### Function
* A function is a code snippet that can be called by other code or by itself, or a variable that refers to the function.
* When a function is called, arguments are passed to the function as input, and the function can optionally return a value. 
* A function in JavaScript is also an object.
* A function name is an identifier included as part of a function declaration or function expression. 
* The function name's scope depends on whether the function name is a declaration or expression.

An identifier is a sequence of characters in the code that identifies a variable, function, or property.

A variable is a named reference to a value. That way an unpredictable value can be accessed through a predetermined name.

