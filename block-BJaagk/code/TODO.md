1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, total) => {
  return (marks * 100) / total;
};
// Your code goes here
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer

let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
<!-- let percentage = function (marks, total){
  return (marks * 100) / total;

It is called a function expression because the function is stored in a variable
} -->

4. Why is a function call an expression in JavaScript?

// to call a function so that it can be executed

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer = valid
five = add; // Answer // invalid
five = five(10, 11); // Answer = valid
five = function () {
  return "Hello";
}; // Answer = valid
```

6. What is the difference between function definition and function call? Explain with an example.

// function starts with the keyword "function" and the function is when it is called so that it can be executed
// and you need to add parentheses at the end of function keyword e.g "function()"

7. What is the similarities between function definition and function call?

// they all start with keyword "function"

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log("Hello World!");
}

hello.user = "Sam"; // valid or invalid // answer = "invalid"
```

9. What is higher order function explain with an example. // the priorities given to the function

10. Explain what is callback function. Why you can pass a function inside a function? // callback function is when you use
    // arrow function and you pass a function to a function when you want the function to call another function
