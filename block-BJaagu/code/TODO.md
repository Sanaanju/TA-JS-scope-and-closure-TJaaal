Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT Nan
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT Error
let numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //OUTPUT Error
```

Find the output of the code snippets below:

```js
console.log(sayHello()); // OUTPUT Hello
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
sayHello(); // OUTPUT Tyrion
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT Tyrion
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT Error
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // OUTPUT
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
sayHello(); // OUTPUT Error
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // OUTPUT Error
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // OUTPUT Error
```