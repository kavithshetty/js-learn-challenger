# <a href="https://www.jschallenger.com/" target="_blank"><img src="./assets/logo.svg" alt="js challenger logo"></a>

## **Welcome !** 👋

Thanks for checking out this [js-challenger solutions repo](https://github.com/CyrusKabir/js-challenger).

## **What is JSchallenger ?** 🙂

JSchallenger is a cool and great and free and ... tool to practice most of the JS fundamentals and JS dom. It's a very helpful free Javascript resource for beginners. JSchallenger created by [Erik Kückelheim](https://www.erik-kueckelheim.com/). thanks Erik.

## **Why this repo ?** 😶

In this repo, I put all the available solutions to solve the challenges of this site.

## **Table of solutions**
- **Javascript Basics**
    <details><summary>variables</summary>

    <!-- inject tos-variables start -->
    1. [Accessing a variable 1](#accessing-a-variable-1)
    1. [Accessing a variable 2](#accessing-a-variable-2)
    1. [Declare a variable and assign a number](#declare-a-variable-and-assign-a-number)
    1. [Reassign a value to a variable 1](#reassign-a-value-to-a-variable-1)
    1. [Reassign a value to a variable 2](#reassign-a-value-to-a-variable-2)
    <!-- inject tos-variables end -->
    </details>
    <details><summary>operators</summary>

    <!-- inject tos-operators start -->
    1. [Comparison operators - Equal](#comparison-operators---equal)
    1. [Comparison operators - Not Equal](#comparison-operators---not-equal)
    1. [Comparison operators - Greater than](#comparison-operators---greater-than)
    1. [Comparison operators - Less than](#comparison-operators---less-than)
    1. [Comparison operators - Greater than or equal](#comparison-operators---greater-than-or-equal)
    1. [Comparison operators - Less than or equal](#comparison-operators---less-than-or-equal)
    1. [Logical operators - logical AND](#logical-operators---logical-and)
    1. [Arithmetic operators - Addition](#arithmetic-operators---addition)
    1. [Arithmetic operators - Subtraction](#arithmetic-operators---subtraction)
    1. [Arithmetic operators - Multiplication](#arithmetic-operators---multiplication)
    1. [Arithmetic operators - Division](#arithmetic-operators---division)
    1. [Arithmetic operators - Exponential](#arithmetic-operators---exponential)
    <!-- inject tos-operators end -->
    </details>
    <details><summary>strings</summary>
    
    <!-- inject tos-strings start -->
    1. [Create a Javascript string](#create-a-javascript-string)
    1. [Different ways to create Javascript strings](#different-ways-to-create-javascript-strings)
    1. [Connect Javascript strings 1](#connect-javascript-strings-1)
    <!-- inject tos-strings end -->
    </details>
    <details><summary>conditionals</summary>

    <!-- inject tos-conditionals start -->
    <!-- inject tos-conditionals end -->
    </details>
    <details><summary>functions I</summary>

    <!-- inject tos-functions I start -->
    <!-- inject tos-functions I end -->
    </details>
    <details><summary>arrays</summary>

    <!-- inject tos-arrays start -->
    <!-- inject tos-arrays end -->
    </details>
    <details><summary>loops</summary>

    <!-- inject tos-loops start -->
    <!-- inject tos-loops end -->
    </details>
- **Javascript Practice**
    <details><summary>Javascript fundamentals</summary>

    <!-- inject tos-Javascript fundamentals start -->
    <!-- inject tos-Javascript fundamentals end -->
    </details>
    <details><summary>Javascript arrays</summary>

    <!-- inject tos-Javascript arrays start -->
    <!-- inject tos-Javascript arrays end -->
    </details>
    <details><summary>Javascript objects</summary>

    <!-- inject tos-Javascript objects start -->
    <!-- inject tos-Javascript objects end -->
    </details>
    <details><summary>Javascript dates</summary>

    <!-- inject tos-Javascript dates start -->
    <!-- inject tos-Javascript dates end -->
    </details>
    <details><summary>Javascript Sets</summary>

    <!-- inject tos-Javascript Sets start -->
    <!-- inject tos-Javascript Sets end -->
    </details>
- **Javascript DOM**
    <details><summary>DOM selector methods</summary>

    <!-- inject tos-DOM selector methods start -->
    <!-- inject tos-DOM selector methods end -->
    </details>
    <details><summary>Events and user interactions</summary>

    <!-- inject tos-Events and user interactions start -->
    <!-- inject tos-Events and user interactions end -->
    </details>
    <details><summary>DOM manipulation</summary>

    <!-- inject tos-DOM manipulation start -->
    <!-- inject tos-DOM manipulation end -->
    </details>
    <details><summary>DOM fundamentals</summary>

    <!-- inject tos-DOM fundamentals start -->
    <!-- inject tos-DOM fundamentals end -->
    </details>
    <details><summary>Recursive functions</summary>

    <!-- inject tos-Recursive functions start -->
    <!-- inject tos-Recursive functions end -->
    </details>

## **Javascript Basics :**
- ### variables
    <!-- inject variables start -->
    - #### Accessing a variable 1
        scenario :
        ```python
        In this simple exercise we declare a variable called num and assign it a value of 5. Then we try to log the value of the variable using the console.log() method.
        But, the console.log() method contains a small mistake. If you try the run the code, you will see an error message.
        Fix the mistake and run the code again.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const num = 5;
        console.log(num);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Accessing a variable 2
        scenario :
        ```python
        This exercise is very similar to the previous one. We declare a variable called num, assign it a value of 5, and try to log it. But again, we introduced a small mistake.
        Fix the code and run it.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const num = 5;
        console.log(num);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Declare a variable and assign a number
        scenario :
        ```python
        In this exercise we practice how to declare a new variable and how to assign it a number. The console.log() statement below attempts to log a variable named num.
        Declare a variable with this name and assign it a number of your choice. Run the code to see if the number is being logged.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const num = 5;
        console.log('The value of num is: ' + num);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Reassign a value to a variable 1
        scenario :
        ```python
        The code below first declares a variable named text with a string value hello. Then, a new value bye is assigned. Finally, the variable is logged.
        But, the code will not work like that. Find the mistake and fix it. Execute the corrected code.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        let text = 'hello';
        text = 'bye';
        console.log(text);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Reassign a value to a variable 2
        scenario :
        ```python
        Here again, we want to assign a new value to a variable that we previously declared. Again, the code will not work the way it is. Find the mistake and fix it. Execute the corrected code.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        let text = 'hello';
        text = 'hello world';
        console.log(text);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    <!-- inject variables end -->
- ### operators
    <!-- inject operators start -->
    - #### Comparison operators - Equal
        scenario :
        ```python
        In the console.log() statement below we use the Equal operator to check whether numOne and numTwo have the same value. Change the code so that the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 5;
        const numTwo = 5;
        console.log(numOne == numTwo);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Comparison operators - Not Equal
        scenario :
        ```python
        In the console.log() statement below we use the Not Equal operator to check whether numOne and numTwo have different values. Change the code so that the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 5;
        const numTwo = 6;
        console.log(numOne != numTwo);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Comparison operators - Greater than
        scenario :
        ```python
        In the console.log() statement below we use the Greater Than operator to check whether the value of numOne is greater than the value of numTwo. Change the code so that the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 6;
        const numTwo = 5;
        console.log(numOne > numTwo);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Comparison operators - Less than
        scenario :
        ```python
        In the console.log() statement below we use the Less Than operator to check whether the value of numOne is less than the value of numTwo. Change the code so that the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 1;
        const numTwo = 2;
        console.log(numOne < numTwo);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Comparison operators - Greater than or equal
        scenario :
        ```python
        In the console.log() statement below we use the Greater Than Or Equal operator to check whether the value of numOne is greater than or equal the value of numTwo. It also checks whether the value of numTwo is greater than or equal the value of numThree. Change the code so that both expressions in the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 3;
        const numTwo = 2;
        const numThree = 2;
        console.log(numOne >= numTwo, numTwo >= numThree);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Comparison operators - Less than or equal
        scenario :
        ```python
        In the console.log() statement below we use the Less Than Or Equal operator to check whether the value of numOne is less than or equal the value of numTwo. It also checks whether the value of numTwo is less than or equal the value of numThree. Change the code so that both expressions in the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 1;
        const numTwo = 1;
        const numThree = 2;
        console.log(numOne <= numTwo, numTwo <= numThree);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Logical operators - logical AND
        scenario :
        ```python
        You can chain multiple comparison operators using the logical AND (&&) operator. In the code below, result will only have the value true if both comparison expressions evaluate to true.
        Adjust the code below such that result will have the value true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 13;
        const numTwo = 13;
        const result = numOne > 12 && numTwo > 12;
        console.log(result);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Arithmetic operators - Addition
        scenario :
        ```python
        In the code below we calculate the sum of numOne and numTwo with the Addition operator +. Then, the console.log() statement checks whether the sum equals 10. Change the code so that the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 4;
        const numTwo = 6;
        const sum = numOne + numTwo;
        console.log(sum == 10);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Arithmetic operators - Subtraction
        scenario :
        ```python
        In the code below we calculate the difference of numOne and numTwo with the Substraction operator -. Then, the console.log() statement checks whether the difference equals 5. Change the code so that the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 9;
        const numTwo = 4;
        const dif = numOne - numTwo;
        console.log(dif == 5);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Arithmetic operators - Multiplication
        scenario :
        ```python
        In the code below we calculate the product of numOne and numTwo with the Multiplication operator *. Then, the console.log() statement checks whether the product equals 81. Change the code so that the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 9;
        const numTwo = 9;
        const product = numOne * numTwo;
        console.log(product == 81);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Arithmetic operators - Division
        scenario :
        ```python
        In the code below we divide numOne by numTwo with the Division operator /. Then, the console.log() statement checks whether the quotient equals 9. Change the code so that the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 81;
        const numTwo = 9;
        const quotient = numOne / numTwo;
        console.log(quotient == 9);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Arithmetic operators - Exponential
        scenario :
        ```python
        In the code below we calculate numOne to the power of numTwo with the Exponential operator **. Then, the console.log() statement checks whether the result of this calculation equals 8. Change the code so that the console.log() statement logs true.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const numOne = 2;
        const numTwo = 3;
        const res = numOne**numTwo;
        console.log(res == 8);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    <!-- inject operators end -->
- ### strings
    <!-- inject strings start -->
    - #### Create a Javascript string
        scenario :
        ```python
        In this exercise the existing console.log() statement logs the value of the variable text. The variable text has already been declared with an empty string – as indicated by the two single quotes.
        Fill in the string with some characters and run the code to see if the string is being logged.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const text = 'hello world';
        console.log('The value of text is: ' + text);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Different ways to create Javascript strings
        scenario :
        ```python
        Here, we have declared 3 variables textOne, textTwo, and textThree. An empty string is assigned to all of them.
        Do you see how in each case different symbols are used to create the string? All three of them are valid methods to create a JavaScript string.
        Fill in all 3 strings with some characters and run the code to see if the values get logged.In this exercise the existing console.log() statement logs the value of the variable text. The variable text has already been declared with an empty string – as indicated by the two single quotes.
        Fill in the string with some characters and run the code to see if the string is being logged.
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const textOne = 'Hello, ';
        const textTwo = "it's ";
        const textThree = `me`;
        console.log('The value of text is: ' + text);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    - #### Connect Javascript strings 1
        scenario :
        ```python
        After we have learnt how to create JavaScript strings, we will now connect 2 strings together. In the code below we use the Addition (+) operator to concatenate textOne and textTwo. The console.log() statement logs the resulting string. Currently, the result would be HelloWorld.
        Change the code below so that the value of res is Hello World
        ```
        
        <details><summary>Solution 1</summary>
        <p>

        js :
        ```js
        const textOne = 'Hello';
        const textTwo = 'World';
        const combined = textOne + ' ' + textTwo;
        console.log(combined);
        ```
        </p>
        </details>

        [Back to table ⬆](#table-of-solutions)
    <!-- inject strings end -->
- ### conditionals
    <!-- inject conditionals start -->
    <!-- inject conditionals end -->
- ### functions I
    <!-- inject functions I start -->
    <!-- inject functions I end -->
- ### arrays
    <!-- inject arrays start -->
    <!-- inject arrays end -->
- ### loops
    <!-- inject loops start -->
    <!-- inject loops end -->

## **Javascript Practice :**

- ### Javascript basics
    <!-- inject Javascript basics start -->
    <!-- inject Javascript basics end -->
- ### Javascript arrays
    <!-- inject Javascript arrays start -->
    <!-- inject Javascript arrays end -->
- ### Javascript objects  
    <!-- inject Javascript objects start -->
    <!-- inject Javascript objects end -->
- ### Javascript dates
    <!-- inject Javascript dates start -->
    <!-- inject Javascript dates end -->
- ### Javascript Sets
    <!-- inject Javascript Sets start -->
    <!-- inject Javascript Sets end -->
## **Javascript DOM :**

- ### DOM selector methods
    <!-- inject DOM selector methods start -->
    <!-- inject DOM selector methods end -->
- ### Events and user interactions
    <!-- inject Events and user interactions start -->
    <!-- inject Events and user interactions end --> 
- ### DOM manipulation
    <!-- inject DOM manipulation start -->
    <!-- inject DOM fundamentals end -->
- ### DOM fundamentals
    <!-- inject DOM fundamentals start -->
    <!-- inject DOM fundamentals end -->
- ### Recursive functions
    <!-- inject Recursive functions start -->
    <!-- inject Recursive functions end -->