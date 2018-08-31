# funky-functions

Create the functions for these hot dance moves!

## Objective

Use **JavaScript Objects, For Loops,** and **Arrays** to create the following functions.

## Prerequisites

## Prerequisites

To complete this project, students should have the following:
* Intermediate understanding of JavaScript and DOM (Objects, Arrays, For Loops, Functions)

## Concepts

JS | Description
-- | -----------
Function | A JavaScript procedure or set of statements that performs a task or calculates a value.
Object | Objects are variables that can contain many variables.
Array | A special variable to store multiple values in a single variable.
For Loop | A loop that repeats until a specified condition is false.
return | A statement to stop execution of a function and return the value of the expression.

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:
1. Set up your project file structure through the command line.
2. Create the following:
* HTML file
* JS file
3. Link all of your files correctly.

### Part II JS

To complete Part II, fulfill the following requirements:

1. Create a ```window.onload``` function that will run once the window has loaded as follows:

```JavaScript
window.onload = function() {
  //code goes in here
}
```

2. Create an ```object``` called funkyFunctions. In this ```object```, create the following:
  * A ```method``` called "salsa".
  * A ```method``` called "chickenDance".
  * A ```method``` called "shuffle".

3. Inside of the ```method``` salsa, create the following:
  * A ```variable``` called danceMoves that will store an ```array``` containing the numbers 3, 2, 1, 5, and 6.
  * A ```variable``` called numSteps that is equal to 0.
  * A ```for loop``` that will start from 0, loop through the length of the ```danceMoves array``` and increment by 1 every time.
    * In this for loop, assign ```numSteps``` equal to the **sum** of ```numSteps``` and **each** element of the ```danceMoves``` array. **At every iteration, numStep should be equal to the current value of numStep plus the current element of danceMoves during that loop's iteration - use the variable i from the for loop to help you!**

    ```JavaScript
    for ([initialExpression]; [condition]; [incrementExpression]) {
      numSteps [operation] numSteps + [element from the danceMoves array];
    }
    ```
  * Outside of the for loop (but still within this method), **return** the value of ```numSteps```.

4. Inside of the ```method``` chickenDance, create the following:
  * A ```variable``` called numClucks that is equal to 0.
  * A ```for loop``` that will start from 0, loop 5 times, and increment by 1 every time.
    * In this for loop, assign ```numClucks``` the sum of ```numClucks``` + 5.
  * Outside of this for loop (but still within the method), create an ```object``` called chicken.
    * In this object, **create 2 methods: funky1 and funky2**.
    * In the funky1 method, assign ```numClucks``` the sum of the current value of ```numClucks``` + 10. Return the value of ```numClucks```.
    * In the funky2 method, return the value of the function funky1. **How do you call a method from the same object?**
  * Outside of this chicken object (but still within the method), **return** the value of chicken's funky2 method.

5. Inside of the ```method``` shuffle, create the following:
  * A ```variable``` called type that will store an array containing the following strings in this order: 'melbourne', 'electronic' 'hardstyle'.
  * An ```object``` called myShuffle with the following properties and values:
    * A ```property``` called type that will store the 1st element of the type array.
    * A ```property``` called isPopular that will store the value of "true".
    * A ```property``` called numClasp that will store the number 300.
  * An ```if statement``` that will check if myShuffle's isPopular property is true. If so, **return** the value of myShuffle's numClaps property.

6. Outside of the ```funkyFunctions``` object, **console.log the sum of the values returned from all of the methods from the funkyFunctions object.** Call each method and add them together to see PART I of the combination. 
