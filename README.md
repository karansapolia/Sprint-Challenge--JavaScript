# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your team lead

1. Describe the biggest difference between `.forEach` & `.map`.

- Ans - While forEach() and map() both perform the same task on a given array, that is, they iterate through the array and perform a given function on every value of the array, .forEach() mutates the original array and replaces the current array member with the result of performing the given operation on it, in-place. .map() on the other hand does not mutate the original array. It creates a new array with the outputs of performing the operation on each value as the members of this array.

2. What is the difference between a function and a method?

- Ans - A function is a named block of a code that can be executed by calling it, using its name. A method is the same thing as a function but it is a member of ( is associated with) an object.

3. What is closure?

- Ans - A function bundled together with its outer (lexical) scope is called a closure. In JS, closures are created everytime a function is created and it is also how you have access to an outer function's scope from an inner function.

4. Describe the four rules of the 'this' keyword.

- Ans - There are four rules of ‘this’ keyword:

    1.	Global binding – When this is called in the outermost scope / global scope, or when a function where ‘this‘ is called is contained in the global scope, it refers to the global / window object. If strict mode is enabled, this returns undefined. Otherwise, it returns the global object.

    2.	Implicit binding – When a function is called with a preceding dot, for example: object1.run() , the this for the function refers to whatever object is placed before the dot.

    3.	New binding – Whenever a constructor function is used to create new instances of an object using the ‘new’ keyword, the ‘this’ refers to the specific instance of the object that is created and returned by the constructor function.

    4.	Explicit binding – Whenever JS methods like .call(), .apply() or .bind() are used, the first argument passed to these functions explicitly becomes the ‘this’ for the objects these functions are applied to.


5. Why do we need super() in an extended class?

- Ans - The super keyword helps us to access and call functions from a parent class / object. It is also used to pass values up to the parent constructor. It does the work that earlier was done by writing the line: 
    ```js 
    Child.constructor = Object.create(Parent.constructor);
    ```

## Project Set up

Follow these steps to set up and work on your project:

- [ ] Create a forked copy of this project.
- [ ] Add TL as collaborator on Github.
- [ ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [ ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [ ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [ ] You are now ready to build this project with your preferred IDE
- [ ] Implement the project on your Branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [ ] Add your team lead as a Reviewer on the Pull-request
- [ ] TL then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

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
