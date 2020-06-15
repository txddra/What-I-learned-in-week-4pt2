# What-I-learned-in-week-4pt2

# Week 4;

During this week, we went over a few things to include:
 - __Variables__ (*and how to declare them*)
 - __Strings__
 - __Scope__
 - __Booleans__

---

## Scope
---
"_what happens in functions, stays in functions_ "

In JavaScript there are *two* types of scope:

- __Local scope__:
   
  - _Variables declared within a JavaScript function, become LOCAL to the function_.

  - Since local variables are only recognized inside their functions, variables with the same name can be used in different functions.



- __Global scope__
  
  - A variable declared outside a function, becomes GLOBAL.
  - If you assign a value to a variable that has not been declared, it will automatically become a GLOBAL variable.



*Stay away from global variables whenever possible 
<!-- 
intermediate variable - storing it 
Const last = str.length -1
to be used 
Return str[last] -->

---
## Variables
---
*Variables* can be thought of as named containers. You can place data into these containers and then refer to the data simply by naming the container.
Before you use a variable in a JavaScript program, you must *declare* it. Variables are declared with the keywords `const` or `let` .


`let studentName = 'Toby Keith';`

  `const schoolName = 'Code Immersives'`

  In JavaScript, there are two types of variable and also it tells you where in your program you are allowed to use the variables and functions that you’ve defined.

**Local Variable**:

are variables that are defined *within* functions.

**Global Variable**:

global variables are variables that are defined *outside* of functions. they can be used by any function without passing them to the function as parameters.

**Parameters**

Function parameters are the names listed in the function.
` function countEm(num){
return num
}`
in this function num would be the *parameter*

---
## Booleans 
---