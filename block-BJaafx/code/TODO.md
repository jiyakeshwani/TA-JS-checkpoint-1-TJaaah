1. Using loops take 10 inputs from user and find the average of all the numbers.
   let average = 0
   for(let i=1; i<=10; i=i+1){
   let input = +prompt("enter a number")
   average = average + input/10;
   }
   console.log(average)
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println("hi");
  i++;
}
```

error 3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
function getEvenSum(max=10){
let sum = 0
for(let i=0; i<=10; i=i+2){
let input = +prompt("enter a number")
sum = sum + input/10;
}
console.log(sum)
};

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
   function getOddSum(max=10){
   let sum = 0
   for(let i=1; i<=10; i=i+2){
   let input = +prompt("enter a number")
   sum = sum + input/10;
   }
   console.log(sum)
   };
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
  let product = 1
  let string = prompt("enter a number")
  for(let i=1; i<string.length; i=i+1){
  product = product \* Number(string[i])
  };
  console.log(product)

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return "Bigger than 5";
  }

  if (num < 5) {
    return "Smaller than 5";
  }

  return num;
}

check(10); // bigger than 5 because 10 is greater than 5
check(1); // smaller than 5 because 1 is smaller than 5
check(5); // 5 because 5 is neither greater nor smaller than 5 its equal to 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === "Arya") return "You are arya";
  if (name === "John") return "You are john";
  return "Who are you";
}

getOutput("Arya"); //'You are Arya'
getOutput("John"); // 'You are John'
getOutput(); // 'Who are you'
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === "Arya") console.log("You are arya");
  if (name === "John") console.log("You are john");
  return "Who are you";
}

getOutput("Arya"); // 'You are arya'
getOutput("John"); // 'You are john'
getOutput(); // 'Who are you'
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
   yes a function can have multiple return statement
   example-
   function getOutput(name) {
   if (name === 'Arya') return 'You are arya';
   if (name === 'John') return 'You are john';
   return 'Who are you';
   }
   if there are multiple conditions in a function then multiple return statements are used
10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
