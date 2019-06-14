Brittany Moyers

# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.
        The biggest difference between .forEach and .map lies in the way they handle the data that they parse after they're done with it. .forEach discards the data, while .map copies it to an entirely new array. This also means that .forEach will modify the original array, while .map does not.  

2. What is the difference between a function and a method?
        A method is a function called on an object. 


3. What is closure?
        Closure is a combo of a function and the environment it was initialized in; it has access to three distinct scope chains: it's own personal scope (the lexical environment in which it was instantiated), the scope of the outer functions it's nested in, and the global scope. 

4. Describe the four rules of the 'this' keyword.
        GLOBAL BINDING - In the global sope, the value of 'this' is the window or console object.

        IMPLICIT BINDING - Whenever a method is called with dot notation, the object to the left of the dot is designated as "this"

        NEW BINDING - Whenever a constructor function is used, 'this' is bound to the specific instance of the object that is created and returned by the constructor. 

        EXPLICIT BINDING - Whenever the '.call' or '.apply' methods are used, 'this' is explicity defined by the following parameter.  

5. Why do we need super() in an extended class?
        super() takes the place of the 'Object.create(this, Class) syntax necessary when using prototypes. 

#


## Minimum Viable Product

Your finished project must include all of the following requirements:

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [ ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [ ] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
