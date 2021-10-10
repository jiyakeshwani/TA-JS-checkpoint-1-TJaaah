1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```

The difference between both the functions is that function1 has return keyword which returns the output in the browser and function2 has consolw.log keyword which displays the output in console of developer tools.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
   The value of first will be a+b and the value of second will also be a+b

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
   The output for this function will be 36 because we have taken only two arguments a and b so the third parameter will not work.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
   yes we can store the sum function into a variable named add because functions are object and objects are values so it can be stored in a variable as an expression

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
   function sayHello(name){
   return hello name
   }

6. What will be the output of the function below and why?

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

showMessage();
```

'Hello, John' 7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

alert(userName); // John

showMessage(); // 'Hello, John'

alert(userName); // John
```

8. What is a Anonymous Function give example of three functions.
   Anonymous function are the functions that have no name associated with it we only use function keyword without name and store it in a variable.
   examples-
   var example1 = function () {
   console.log("Welcome to Todo.md!");
   };
   let example2 = function () {
   console.log("This is example 2");
   };
   let example3 = function () {
   console.log("Example3!");
   };
9. Can function declaration be a Anonymous Function? Explain
   No, because function declaration has a name specified into it and anonymous function does not.

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

1-isBirthDay
2-addNumbers
3-calcBmi
4-sayHello
5-showMessage
