Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT : NaN
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT : Error: numA is not defined
let numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //OUTPUT : 51
```

Find the output of the code snippets below:

```js
console.log(sayHello()); // OUTPUT : 'Hello'
function sayHello() {
  console.log("Hey");
}
function sayHello() {
  console.log("Hello");
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT : Tyrion
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT : Error: Username is notdefined
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT : Error: sayHello is not defined
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT : Error: sayHello is not defined
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT : Error: sayHello is not defined
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // OUTPUT : Error: sayHello is not defined
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  var username = "John";
};
sayHello(); // OUTPUT : undefined
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // OUTPUT: John
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // OUTPUT : Error: Cannot access username before initialization
```