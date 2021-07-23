# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

My wife actually had a very good analogy to help us understand the difference between .map and .filter. Her example, which has become my own now as well, was as follows:

.filter is very similar to looking at a book shelf that is filled with books and only wanting the books that are written by a certain author, say C.S. Lewis. The .filter method will scan through all of our books and decide which books have been written by C.S. Lewis and put them into your library cart in order for you to check them out. .filter may skip over some indices in our array if they do not pass the condition set forth. 

.map will consider all of the books on the shelf and take someting or manipulate each of them according to some designated change we have told it to make. So, maybe I want to catalog every book I own on my shelf? .map would take every book title I have and put it into a new array for me. .map must go through every index in our array. 

2. Explain the difference between a callback and a higher order function.

So, a higher order function is a function that returns another function while a callback function is a function that we pass through a different function as an argument. 

3. Explain what a closure is.

Closure occurs as soon we enter into a function. It is a good idea to think of functions as little black boxes. A lot of things can happen inside of the black boxes but everything outside of the black box can't see or access what was created or defined inside of the blackbox unless the blackbox outputs information. However, everything in the blackbox has access to the scope outside of the blackbox. So, the blackbox has access to everything outside of it but everything outside of the blackbox does not have access to what is inside the blackbox. This is closure. 

4. Describe the four principles of the 'this' keyword.

(1) Global Binding - This is when we have no context for the this keyword, it attaches itself to the the context/object that it lives within, which will be the window/console object.

(2) Implicit Binding - This is when we enter into an object, where we find ourselves in the object is actually a function, and within that function we have the keyword this, then the original object is "this". The original object is our context. 

(3) New Binding - In this situation, the this keyword is refering to the specific instance object that we are creating and calling by our constructor function. This new object is our context. 

(4) Explicit Binding - with .call() and .apply() we are explicity passing in the object context for the this keyword. So, that is what this will mean in this context. 

5. Why do we need super() in an extended class?

The best/most concise explanation I have found about super() is that it is used to make sure we do not duplicate any of the constructor parts' that are common between the parent object and the child object. 

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

