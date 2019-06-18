> complete [the basic JS exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript) through _Counting Cards_ & paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/freecode_camp_solutions.MD) 

>[My freeCodeCamp Portfolio](https://www.freecodecamp.org/ebruispir)


## 1.Comment Your JavaScript Code

```js
//this is a comment.
/* this is a multi-line comment*/
```
## 2.Declare JavaScript Variables

```js
var myName;
```
## 3.Storing Values with the Assignment Operator

```js
a=7;
b=a;
```
## 4.Initializing Variables with the Assignment Operator

```js
var a = 9;
```
##5.Understanding Uninitialized Variables

```js
var a = 5;
var b= 10;
var c = "I am a";
```
## 6.Understanding Case Sensitivity in Variables

```js
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments

studlyCapVar =10;
properCamelCase ="A String";
titleCaseOver = 9000;
```
## 7.Add Two Numbers (+)

```js
var sum = 10 + 10;
```
## 8.Subtract One Number from Another

```js
var difference = 45 - 33;
```
## 9.Multiply Two Numbers with JavaScript

```js
var product = 8 * 10;
```
## 10.Divide One Number by Another with JavaScript

```js
var quotient = 66 / 33;
```
## 11.Increment a Number with JavaScript

```js
myVar++;
```
## 12.Decrement a Number with JavaScript
```js
myVar--;
```
## 13. Create Decimal Numbers with JavaScript

```js
var myDecimal = 3.5;
```
## 14.Multiply Two Decimals with JavaScript

```js
var product = 2.0 * 2.5;
```
## 15.Divide One Decimal by Another with JavaScript
```js
var quotient = 4.4 / 2.0;
```
## 16.Finding a Remainder in JavaScript

```js
var remainder = 11 % 3;
```
## 17.Compound Assignment With Augmented Addition

```js
a += 12;
b += 9;
c += 7;

```
## 18.Compound Assignment With Augmented Subtraction

```js
a -= 6;
b -= 15;
c -= 1;

```
## 19.Compound Assignment With Augmented Multiplication

```js
a *= 5 ;
b *=3 ;
c *= 10;

```
## 20.Compound Assignment With Augmented Division

```js
a /= 12;
b /= 4;
c /= 11;
```
## 21.Declare String Variables

```js
var myFirstName = "Ebru";
var myLastName= "Ispir";
```
## 22.Escaping Literal Quotes in Strings

```js
var myStr = "I am a \"double quoted\" string inside \"double quotes\"."; 
```
## 23.Quoting Strings with Single Quotes

```js
var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```
## 24.Escape Sequences in Strings

```js
var myStr='FirstLine\n\t\\SecondLine\nThirdLine'; 
```
## 25.Concatenating Strings with Plus Operator

```js
var myStr= "This is the start. " +  "This is the end.";
```
## 26.Concatenating Strings with the Plus Equals Operator

```js
var myStr="This is the first sentence. ";
myStr += "This is the second sentence."
```
## 27.Constructing Strings with Variables

```js
var myName="ebru";
var myStr= "My name is "+ myName + " and I am well!" ;
```
## 28.Appending Variables to Strings

```js
var someAdjective="super";
var myStr = "Learning to code is ";
myStr += someAdjective;
```
## 29.Find the Length of a String

```js
lastNameLength = lastName.length;
```
## 30.Use Bracket Notation to Find the First Character in a String

```js
firstLetterOfLastName = lastName[0];
```
## 32.Understand String Immutability

```js
var myStr = "Jello World";
myStr= "Hello World";
```
## 33.Use Bracket Notation to Find the Nth Character in a String

```js
var thirdLetterOfLastName = lastName[2];
```
## 34.Use Bracket Notation to Find the Last Character in a String

```js
var lastLetterOfLastName = lastName[lastName.length -1];
```
## 35.Use Bracket Notation to Find the Nth-to-Last Character in a String

```js
var secondToLastLetterOfLastName = lastName[lastName.length -2];
```
## 36.Word Blanks

```js
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
var result = "My "+ myAdjective + " " + myNoun + " " + myVerb + " " + myAdverb + "." ;
return result;
}
wordBlanks("dog", "big", "ran", "quickly");
```
## 37.Store Multiple Values in one Variable using JavaScript Arrays

```js
var myArray = ["one",2];
```
## 38.Nest one Array within Another Array

```js
var myArray = [["ebru",32],["erdem",36]];
```
## 39.Access Array Data with Indexes

```js
var myArray = [50,60,70];
var myData =myArray[0];
```
## 40. Modify Array Data With Indexes

```js
var myArray = [18,64,99];
myArray[0]=45;
```
## 41.Access Multi-Dimensional Arrays With Indexes

```js
var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];
var myData = myArray[2][1]; // equals=8
```
## 42. Manipulate Arrays With push()

```js
var myArray = [["John", 23], ["cat", 2]];
myArray.push(["dog", 3]);
```
## 43.Manipulate Arrays With pop()
>You can pop off the last array, and store it in a variable.
```js
var myArray = [["John", 23], ["cat", 2]];
var removedFromMyArray=myArray.pop();
```
## 44.Manipulate Arrays With shift()
>You can remove the first in the array
```js
var myArray = [["John", 23], ["dog", 3]];
var removedFromMyArray= myArray.shift();
```
## 45.Manipulate Arrays With unshift()

```js
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();
myArray.unshift(["Paul",35]);
```
## 46.Shopping List

```js
var myList = [["egg",6],["milk",2],["chocolat",5],["bread",2],["tomato",15]];

```
## 47.Write Reusable JavaScript with Functions

```js
function reusableFunction(){
    console.log( "Hi World");
}
reusableFunction();
```
## 48. Passing Values to Functions with Arguments

```js
function  functionWithArgs(a,b){
console.log(a+b); 
}
functionWithArgs(20,15);
```
## 49.Global Scope and Functions

```js
var myGlobal=10;

function fun1() {
  // Assign 5 to oopsGlobal Here
  oopsGlobal=5
}
```
## 50. Local Scope and Functions

```js
function myLocalScope() {
var myVar='use strict';
{
myLocalScope();
```
## 50.

```js
```
