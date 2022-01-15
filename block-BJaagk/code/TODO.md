1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
```let percentage = (marks, total) {
  return `${marks * 100} / total`;
  };
  ```
}

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```js
let percentage = (marks, total) => {
  return `${marks * 100} / {total}`;
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
```js
function nameOfFunction () {
    // function body   
};
```
4. Why is a function call an expression in JavaScript?

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer in this example the add function is not defined
five = add; // Answer in this also same 
five = five(10, 11); // Answer five is not defined it is invalid
five = function () {
  return 'Hello';
}; // Answer it can not access the five before initialization invalid
```

6. What is the difference between function definition and function call? Explain with an example.//A function is a block of code that does a particular operation and returns a result. It usually accepts inputs as parameters and returns a result. The parameters are not mandatory.
E.g:
Function add(a,b)
return a+ b
A function call is the code used to pass control to a function.
E.g.:
b = add(5,6)
Now b will have the value 11.
7. What is the similarities between function definition and function call?
//A function is procedure to achieve a particular result while function call is using this function to achive that task. The opening and closing braces defines the scope of that function while the code between these braces is the actuall code/procedure to achieve the goal.
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid the given code is valid
```

9. What is higher order function explain with an example.//a higher-order function is a function that either takes a function as an argument or returns a function.

10. Explain what is callback function. Why you can pass a function inside a function?
// A callback function is a function that is passed as an argument to another function, to be “called back” at a later time.