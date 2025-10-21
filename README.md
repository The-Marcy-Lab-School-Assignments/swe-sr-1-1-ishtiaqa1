# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response

According to MDN Docs, a function is a reusable block of code designed to perform a particular task. You can define it once and then call it whenever you need it.

You can think of a function like a vending machine, you give an input, some cash and a snacks code, and recieve an output, the snack. Functions do exactly the same, they take an input, parameters, then do something internally, and gives us an output.

Check out this example:

```js
const addNumbers = (a, b) => {
  return a + b;
};

console.log(addNumbers(3, 5)); // Output: 8
```

* const addNumbers = (a,b) => {...} is an **arrow function** named addNumbers, whose purpose is to add the two numbers we give it.
* The (a,b) part are the **parameters** or what we input into the function.
* The { return a + b; } is the **code block**  which is the instructions in the function that the computer uses to compute what we need or want.
* The **return** is a statement that sends anything after it, in this case the a + b;, back to where it was called.
* **console.log** is a statement that sends anything in it, in this case addNumbers(3,5), to the terminal for us to be able view the result.
* addNumbers(3, 5) is the **function call**, its how we run the function using the parameters 3, and 5.