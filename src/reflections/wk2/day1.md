# Day One - Intro the JS

### Daily challenge:

Read Intro to JS > Var, let and const and answer the following questions

## What is Scope ?
Scope refers to the placement of a variable. Outside any function is global, inside a function is block. Or for Var locally scoped.

## What is Hoisting ?
Variables and function declarations need to be above the code execution in order to get the correct output, otherwise we will recieve an error. Hoisting moves these to the top of their scope so the code execution will be after the declarations and we will get the correct output.

## In what cases might you use let vs const vs var?
You would use Var if you need a globally scoped variable to use throughout the DOM. You would use Let in a block scope if you needed to update the variable within the block. YOu would use Const inside a block scope if you need that variable to remain the same throughout the block it is in, it must be initialized during the declaration and can not be updated or redeclared.