1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
//This function will return result of a+b;
// second
function sum(a, b) {
  console.log(a + b);
}
//This function will output the result on the browser console but since this function does not return anything it will return undefined by default.
```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
```js
//Value of first variable will be first=number or string depending upon the arguements provided and second=undefined
```
3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
```js
//It will output 36 as only the first two parameters will be considered
```
4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
```js
//Yes we can store the function in a variable named 'add' because in javascript function is considered as an object and since object is an expression/value we can mention function on the RHS of "=
```
5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
```js
function sayHello(name)
{
  return `Hello ${name}`;
}
```
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();

//'Hello, John'
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // undefined (will alert John)

showMessage(); // 'Hello, John'

alert(userName); // undefined (Will alert John)
```

8. What is a Anonymous Function give example of three functions.
```js
//An Anonymous function is a function that does not have a name.
eg:
1. const add=function(num1,num2)
{
  return num1+num2;
}
2. const add=(num1,num2)=>num1+num2;
3.const add=(num1,num2)=>
{
  return num1+num2;
}
```
9. Can function declaration be a Anonymous Function? Explain
```js
//Function declaration cannot be anonymous because we need to call/execute such functions using its name.
```
10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
```js
//function getName();
//function showUserDetails();
//function calcMean();
//function checkMaritalStatus()
//function createShoppingCart();
```
