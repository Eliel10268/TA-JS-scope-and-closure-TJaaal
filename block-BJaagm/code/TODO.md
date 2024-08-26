1. What does thread of execution means in JavaScript?

In JavaScript, a "thread of execution" refers to the path or sequence in which code is executed by the JavaScript engine. JavaScript is single-threaded, which means it has one main thread of execution. This thread processes one task at a time, executing code line by line.

2. Where the JavaScript code gets executed?

JavaScript code gets executed in a JavaScript engine, which is a program or environment that interprets and runs JavaScript.
In places such as web browsers, embedded systems, etc..

3. What does context means in Global Execution Context?

the Global Execution Context is the default or base execution context where JavaScript code runs when it is not inside a function. The "context" in this case refers to the environment or scope in which the code is executed.

4. When do you create a global execution context.

when loading a page, running a script in Node.js etc..

5. Execution context consists of what all things?

An Execution Context in JavaScript consists of the Variable Environment (variables, functions, and scope chain), the Lexical Environment (structure managing the current scope and outer references),

6. What are the different types of execution context?

Global execution and function execution

7. When global and function execution context gets created?

Global execution is created as soon as a file is loaded and executed.

Function execution is created when the function is called

8. Function execution gets created during function execution or while declaring a function.

during function execution

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.

```js
var user = "Arya";

function sayHello() {
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)

```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount) {
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)

```js
var age = 21;

function customeMessage(userAge) {
  if (userAge > 18) {
    return `You are an adult`;
  } else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)
