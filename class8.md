# What I Learned in My Readings

## Class Eight Notes

### Expressions and Operators

* Assignment, comparision, arithmetic, bitwise, logical, string, ternary and more.
* An expression is a valid unit of code that resolves to a value. 
* All complex expressions are joined by operators, such as = and +
* There are two types of expressions: 
*       1. those that have side effects (such as assigning values) like x = 7 
*             It uses the operator = to assign the value seven to the variable x. 
*             The expression itself evaluates to 7.
*       2. those that purely evaluate (such as 3+4)
*             Uses the operator + to add 3 and 4 together and produces a value 7. 

#### Comparison Operators

* Compares its operands and returns a logical value based on whether the comparison is true. 
* The operands can be numerical, string, logical, or object values.
* Strings are compared based on standard lexicographical ordering, using Unicode values. 

Equal (==)
Not equal (!=)
Strict equal (===) - operands are equal and of the same type.
Strict not equal (!==)
Greater than (>)
Greater than or equal (>=)
Less than (,)
Less than or equal (<=)

#### Assignment Operators

* The simple assignment operator (=) is used to assign a value to a variable. 
* It evaluates the assigned vlaue.

### Loops

* Loops offer a quick and easy way to do something repeatedly.
* There are many different kinds of loops, but they all essentially do the same thing: 
*      they repeat an action some number of times. (Note that it's possible that number could be zero!)
* The statements for loops provided in JavaScript are:
*   for statement
*   do...while statement
*   while statement
*   labeled statement
*   break statement
*   continue statement
*   for...in statement
*   for...of statement

#### for statement

* A for loop repeats until a specified condition evaluates to false.
* for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
  
*HTML
<form name="selectForm">
  <label for="musicTypes">Choose some music types, then click the button below:</label>
  <select id="musicTypes" name="musicTypes" multiple>
    <option selected>R&B</option>
    <option>Jazz</option>
    <option>Blues</option>
    <option>New Age</option>
    <option>Classical</option>
    <option>Opera</option>
  </select>
  <button id="btn" type="button">How many are selected?</button>
</form>

#### while statement

* A while statement executes its statements as long as a specified condition evaluates to true. 
* while (condition)
  statement
 * If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
 * The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

To execute multiple statements, use a block statement ({ }) to group those statements.
