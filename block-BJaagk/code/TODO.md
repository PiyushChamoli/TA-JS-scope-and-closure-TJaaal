1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let calculatePercentage = function (marks, total) {
  return (marks * 100) / total;
}

let calculatePercentage = (marks, total) => (marks * 100) / total;
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
Function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
//answer : Function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
// answer: Function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
//answer: Function Expression, arrow function
```

```js
let percentage = (marks, total) => (marks * 100) / total;
// answer: Function Expression, arrow function
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
    
    Expression is something that resolves into a value. As in JS function is an Object and an Object can be stoerd in a variable so function definition is an expression.

4. Why is a function call an expression in JavaScript?



5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer: Valid as function is an object
five = add; // Answer: valid as it is function reference
five = five(10, 11); // Answer: 
five = function () {
  return 'Hello';
}; // Answer: valid 
```

6. What is the difference between function definition and function call? Explain with an example.

7. What is the similarities between function definition and function call?

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid 
```

9. What is higher order function explain with an example.

    A function that accepts another function as a parameter or returns a function is higher order function.

10. Explain what is callback function. Why you can pass a function inside a function?

    a function that is being passed to another function as a parameter is called callback function.
