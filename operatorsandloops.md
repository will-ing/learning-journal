# Operators and loops

## Operators
keyword| Description| 
---- | ---- 
==| is equal to
!=| is not equal to
===| strict equal to
!==| strict not equal to
>| greater than
<| less than
>=| greater than or equal to
<=| less than or equal to
&&| logical and; test more than one condition
\|\|| logical or; test at least one condition
!| Logical not; takes single boolean value and inverts it

*logical evaluation are done from left to right*

## Loops
*pg 170*
> Loops - check a condition. If it returns true, a code block will run. then the condition will be checked again and if it still returns true, it will run again. this repeats until the condition returns false.

### Loops
types| Description| 
---- | ---- | ----
For| If you need to run a code a specific number of times. Often used to loop thought the items in an array
While| If you do not know how many times the code should run.
Do while| Key difference: it will always run the statements inside the curly braces at least once, even if the condition evaluates to false

### Loop counters
types| Description| 
---- | ---- | ----
Initialization| Create a variable and set it to 0. This variable is commonly called i, and it acts as the counter; var i =0;
condition| The loop should continue to run until the counter reaches a specified number.;i < 10;
Update| Every time the lop has run the statements in the curly braces, it adds one to the counter.; i++

### Key loops

Consider three points:
* Keywords - **break**: causes termination of the loop. **continue**: tells the interpreter to stop the current iteration, and then update and check the condition again.
* Loops & Arrays - loops can help run the same code for each item in the array.
* Performance issues - can make the page slower. Can get an infinite loop.