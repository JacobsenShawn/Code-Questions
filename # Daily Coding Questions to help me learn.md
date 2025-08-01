Daily Coding Questions to help me learn.


Week 1: Variables & Basic Program Structure


1 What is a variable? Write a short sentence about what a variable is. 

A variable is a place in memory to store and modify data 

2 Simple Variable: Create a variable called favoriteColor and set it to your favorite color. Write what it is.

let favoriteColor = "Black";      {if the color can change}
const favoriteColor = "Black";     {if the color can not change}


3 Using Variables: Write a short program that shows your favorite color by printing: "My favorite color is ____."

const favoriteColor = "Black"
console.log(`My Favorite color is ${favoriteColor}!!!!`)

4 Program Structure: Write a small program that has two parts: one that sets your name, and another that prints "Hello, my name is ____."

const name = "Shawn"
console.log(`My name is ${name}!!!!`)



5 Changing Variables: Make a variable called age, set it to your age. Change it to your friend's age and print both ages.
let age = 47;
console.log(`My age is ${age}.`)
age = 21;
console.log(`My friends age is ${age}.`)

6 Multiple Variables: Create variables for your favorite fruit, animal, and hobby. Print a sentence using all of them.

let favoriteFruit = "watermelon";
let favoriteAnimal = "lion";
let favoriteHobby = "music";

console.log(`Heres a list of some of my favorite things fruit ${favoriteFruit}, favorite animal ${favoriteAnimal}, favorite hobby ${favoriteHobby}.`)

7 Review: Write a short paragraph explaining what you learned about variables and program structure this week.
Variables are a way to store data , some are constant and some can be changed later.

8.What does JavaScript help you do on a website?
Make things happen when you click buttons  


9. What are some of the basic data types? 
string, number, boolean, null, symbol

10. Write a JavaScript function that takes two numbers as arguments and returns their sum.
function addNumbers(num1, num2) {
  return num1 + num2;
}

// Example usage:
let result = addNumbers(5, 3);
console.log(result); // Output: 8

11.Describe Arrow Functions
Arrow functions were introduced in ES6 and are a shorthand version of writing traditional functions. They save room and can make code more easily readable, are quicker to write, and can make coding more efficient.

12. Explain the .pop() and .push() methods using the following array:
The .pop() method removes the last element in the array and returns it.

The .push() method instead adds any included elements to the end of the array, and returns the new length of that array. 