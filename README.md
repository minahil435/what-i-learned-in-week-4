## What I Learned In Week 4 at Code Immersives
1. **Function**
    - A function in JavaScript is similar to a procedure which is a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output. 
    - JavaScript functions are defined with the **function** keyword.
    - A function avoids redundancy of code and make code resuable.
    ``` css
    function functionName() {
      // statements
      }  
 
2. **Function with parameters**
   - Function parameters are the names listed in the function definition.
   - JavaScript function definitions do not specify data types for parameters.
   ``` css
    function functionName(parameter1, parameter2, parameter3) {
      // code to be executed
    }
    ```
  
3. **Maths Function**
   #### Learnt about some Maths functions e.g
    - Modolus % : to get reminder
    - Math.pow(x,y) : to get x raise to power z
    - Math.sqrt(x) : to get square root of x

4. **Const vs Let**
  ##### *let* is now preferred for variable declaration. A variable declared with *let* can be updated within its scope.
  ##### Variables declared with the *const* maintain constant values. This means that the value of a variable declared with *const* remains the same within its scope. It cannot be updated or re-declared.

5. **Function return**
    - When a function does not return anything it return **undefined**
    - When JavaScript reaches a return statement, the function will stop executing.
  ``` cs 
  var x = myFunction(4, 3);  
  // Function is called, return value will end up in x

  function myFunction(a, b) {
  return a * b;             
  // Function returns the product of a and b
  }

6. **String property and method**
    - A property is a variable that is stored as part of another.
    - All string property starts with **dot '.'**
    - Method is a special kind of property that's a   function.
      ##### Examples of string property and methods are below.
      1. x.length : to find the number of characters of string 'x'
      2. x.toUpperCase : to convert every character in x to uppercase 
      3. x[y] : to access the yth character in x
      4. x.indexOf('y') : to find the index of letter 'y' in x string.

  7. **Boolean**
    ##### A JavaScript Boolean represents one of two values, *true or false*. It is mainly use when comparing and/or in conditional statements.
    -  When comparing two same data types we use **"==="**
  8. **If/Else conditional statements**
    ##### The if/else statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed. The if/else statement is a part of JavaScript's "Conditional" Statements, which are used to perform different actions based on different conditions.
    ##### we use *'&&'* and *'||'* to combine different conditions in one statement know as complex conditional statement.

    


   


    

  
# What I Learned In Week 4 at Code Immersives
1. **Function**
    - A function in JavaScript is similar to a procedure which is a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output. 
    - JavaScript functions are defined with the **function** keyword.
    - A function avoids redundancy of code and make code resuable.
    ``` css
    function functionName() {
      // statements
      }  
 
2. **Function with parameters**
   - Function parameters are the names listed in the function definition.
   - JavaScript function definitions do not specify data types for parameters.
   ``` css
    function functionName(parameter1, parameter2, parameter3) {
      // code to be executed
    }
    ```
  
3. **Maths Function**
   #### Learnt about some Maths functions e.g
    - Modolus % : to get reminder
    - Math.pow(x,y) : to get x raise to power z
    - Math.sqrt(x) : to get square root of x

4. **Const vs Let**
  ##### *let* is now preferred for variable declaration. A variable declared with *let* can be updated within its scope.
  ##### Variables declared with the *const* maintain constant values. This means that the value of a variable declared with *const* remains the same within its scope. It cannot be updated or re-declared.

5. **Function return**
    - When a function does not return anything it return **undefined**
    - When JavaScript reaches a return statement, the function will stop executing.
  ``` cs 
  var x = myFunction(4, 3);  
  // Function is called, return value will end up in x

  function myFunction(a, b) {
  return a * b;             
  // Function returns the product of a and b
  }

6. **String property and method**
    - A property is a variable that is stored as part of another.
    - All string property starts with **dot '.'**
    - Method is a special kind of property that's a   function.
      ##### Examples of string property and methods are below.
      1. x.length : to find the number of characters of string 'x'
      2. x.toUpperCase : to convert every character in x to uppercase 
      3. x[y] : to access the yth character in x
      4. x.indexOf('y') : to find the index of letter 'y' in x string.

  7. **Boolean**
    ##### A JavaScript Boolean represents one of two values, *true or false*. It is mainly use when comparing and/or in conditional statements.
    -  When comparing two same data types we use **"==="**
  8. **If/Else conditional statements**
    ##### The if/else statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed. The if/else statement is a part of JavaScript's "Conditional" Statements, which are used to perform different actions based on different conditions.
    ##### we use *'&&'* and *'||'* to combine different conditions in one statement know as complex conditional statement.
