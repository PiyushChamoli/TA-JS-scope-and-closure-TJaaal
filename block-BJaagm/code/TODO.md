1. What does thread of execution means in JavaScript?

    THread of execution means the sequence in which javascript engine will execute the code.

2. Where the JavaScript code gets executed?

    Javascript code gets executed in the Global Execution Context.

3. What does context means in Global Execution Context?

    Contect means the environment in which the code gets executed.

4. When do you create a global execution context.

    Global Execution Context gets created at the beginneing of the code execution by javascript engine.

5. Execution context consists of what all things?

    2parts mainly the memory and the execution part.

6. What are the different types of execution context?

    Global and function

7. When global and function execution context gets created?

    Global gets created once at the beginneing and function gets created everytime when a function is executed.

8. Function execution gets created during function execution or while declaring a function.

    Function execution gets created duringfunction execution.

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)