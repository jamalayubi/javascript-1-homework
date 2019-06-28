> begin [the debugging exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/debugging) and paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/freecode_camp_solutions.MD)  (wrong exercises, correct markdown styling)

>[My freeCodeCamp Portfolio](https://www.freecodecamp.org/ebruispir)

## 1.Use the JavaScript Console to Check the Value of a Variable

```js
console.log(a)
```
## 2.Understanding the Differences between the freeCodeCamp and Browser Console

```js
console.log(outputTwo);
console.log(outputOne);
console.clear();
```
## 3.Use typeof to Check the Type of a Variable

```js
let seven = 7;
let three = "3";

console.log(typeof seven);
console.log(typeof three);
```
## 4.Catch Misspelled Variable and Function Names

```js
let receivables = 10;
let payables = 8;
let netWorkingCapital = receivables - payables;
console.log(`Net working capital is: ${netWorkingCapital}`);
```
## 5.Catch Unclosed Parentheses, Brackets, Braces and Quotes

```js
let myArray = [1, 2, 3];
let arraySum = myArray.reduce((previous, current) =>  previous + current);
console.log(`Sum of array values is: ${arraySum}`);
```
## 6.Catch Mixed Usage of Single and Double Quotes

```js
let innerHtml = "<p>Click here to <a href=\"#Home\">return home</a></p>";
```
## 7.Catch Use of Assignment Operator Instead of Equality Operator

```js
let x = 7;
let y = 9;
let result = "to come";

if(x == y) {
  result = "Equal!";
} else {
  result = "Not equal!";
}

```
## 8.Catch Missing Open and Closing Parenthesis After a Function Call

```js
function getNine() {
  let x = 6;
  let y = 3;
  return x + y;
}

let result = getNine() ;
```
## 9.Catch Arguments Passed in the Wrong Order When Calling a Function

```js
function raiseToPower(b, e) {
  return Math.pow(b, e);
}

let base = 2;
let exp = 3;
let power = raiseToPower(base, exp);
```
## 10.Catch Off By One Errors When Using Indexing

```js
function countToFive() {
  let firstFive = "12345";
  let len = firstFive.length;
  // Fix the line below
  for (let i = 0; i < len; i++) {
  // Do not alter code below this line
    console.log(firstFive[i]);
  }
}
```
## 11.Use Caution When Reinitializing Variables Inside a Loop

```js
function zeroArray(m, n) {
  let newArray = [];
  for (let i = 0; i < m; i++) {
    let row = []
    for (let j = 0; j < n; j++) {
      row.push(0);
    }
    newArray.push(row);
  }
  return newArray;
}

```
## 12.Prevent Infinite Loops with a Valid Terminal Condition

```js
function myFunc() {
  for (let i = 1; i <= 4; i += 2) {
    console.log("Still going!");
  }
}
```
