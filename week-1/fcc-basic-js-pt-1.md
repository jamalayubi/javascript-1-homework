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
## 51.Global vs. Local Scope in Functions

```js
var outerWear = "T-Shirt";

function myOutfit() {
var outerWear="sweater"
return outerWear;
}
myOutfit();   //The function myFun will return "sweater"
```
## 52.Return a Value from a Function with Return

```js
function timesFive(num){
return num * 5;
}
console.log(timesFive(5));
console.log(timesFive(2));
console.log(timesFive(0));
```
## 53.Understanding Undefined Value returned from a Function

```js
function addFive(){
  sum = sum + 5;
}
```
## 54.Assignment with a Returned Value

```js
var processed = 0;
function processArg(num) {
  return (num + 3) / 5;
}
processed = processArg(7);
```
## 55.Stand in Line

```js
function nextInLine(arr, item) {
  arr.push(item);
  var removed = arr.shift();
  return removed;
 }
```
## 56.Understanding Boolean Values

```js
function welcomeToBooleans() {
return true;
}
```
## 57.Use Conditional Logic with If Statements

```js
function trueOrFalse(wasThatTrue) {
 if (wasThatTrue){
        return "Yes, that was true";
    }
  return "No, that was false";
 }
  trueOrFalse(true);
```
## 58.Comparison with the Equality Operator

```js
function testEqual(val) {
  if (val==12) {
    return "Equal";
  }
  return "Not Equal";
}
testEqual(10);
```
## 59.Comparison with the Strict Equality Operator

```js
function testStrict(val) {
  if (val===7) {
    return "Equal";
  }
  return "Not Equal";
}
testStrict(10);
```
## 60.Practice comparing different values

```js
function compareEquality(a, b) {
  if (a === b) {
    return "Equal";
  }
  return "Not Equal";
}
compareEquality(10, "10");
```
## 61.Comparison with the Inequality Operator

```js
function testNotEqual(val) {
  if (val!=99) {
    return "Not Equal";
  }
  return "Equal";
}
testNotEqual(10);
```
## 62.Comparison with the Strict Inequality Operator

```js
function testStrictNotEqual(val) {
if (val!==17) {
  return "Not Equal";
  }
return "Equal";
testStrictNotEqual(10);
```
## 63.Comparison with the Greater Than Operator

```js
function testGreaterThan(val) {
  if (val>100) {
    return "Over 100";
  }
  if (val>10) {  // Change this line
    return "Over 10";
  }
  return "10 or Under";
}
testGreaterThan(10);
```
## 64.Comparison with the Greater Than Or Equal To Operator

```js
function testGreaterOrEqual(val) {
  if (val>=20) {
    return "20 or Over";
  }
  if (val>=10) {
    return "10 or Over";
  }
return "Less than 10";
}
testGreaterOrEqual(10);
```
## 65.Comparison with the Less Than Operator

```js
function testLessThan(val) {
  if (val<25) {
    return "Under 25";
  }
  if (val<55) {
    return "Under 55";
  }
  return "55 or Over";
}
testLessThan(10);
```
## 66.Comparison with the Less Than Or Equal To Operator

```js
function testLessOrEqual(val) {
  if (val<=12) {
    return "Smaller Than or Equal to 12";
  }
  if (val<=24) {
    return "Smaller Than or Equal to 24";
  }
  return "More Than 24";
}
testLessOrEqual(10);
```
## 67.Comparisons with the Logical And Operator

```js
function testLogicalAnd(val) {
  if (val>=25 && val<=50) {
    return "Yes";
  }
  return "No";
}
testLogicalAnd(10);
```
## 68.Comparisons with the Logical Or Operator

```js
function testLogicalOr(val) {
 
  if (val<10 || val>20) {
    return "Outside";
  }
  return "Inside";
}
testLogicalOr(15);
```
## 69.Introducing Else Statements

```js
function testElse(val) {
  var result = "";
  
  if (val > 5) {
    result = "Bigger than 5";
  }else {
    result = "5 or Smaller";
  }
  return result;
}
testElse(4);
```
## 70.Introducing Else If Statements

```js
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }else if (val < 5) {
    return "Smaller than 5";
  }else{ 
   return "Between 5 and 10";
   }
}

testElseIf(7);

```
## 71.Logical Order in If Else Statements

```js
function orderMyLogic(val) {
  if (val < 5) {
    return "Less than 5";
  } else if (val < 10) {
    return "Less than 10"; 
  } else {
    return "Greater than or equal to 10";
  }
}

orderMyLogic(7);
```
## 72.Chaining If Else Statements

```js
function testSize(num) {
  // Only change code below this line
 if(num<5) {
   return "Tiny";
 }else if(num < 10){
   return "Small";
 }else if(num < 15){
   return "Medium";
 }else if(num < 20){
   return "Large";
 }else if(num >= 20){
   return "Huge";
 }else{
  
  return "Change Me";
 }
}
testSize(7);
```
## 73.Golf Code

```js
var names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];
function golfScore(par, strokes) {
  if (strokes == 1) {
return "Hole-in-one!";
  } else if (strokes <= par - 2) {
     return "Eagle" ;
  } else if (strokes == par - 1) {
     return "Birdie" ;
  } else if (strokes == par) {
     return "Par" ;
  } else if (strokes == par + 1) {
     return "Bogey" ;
  } else if (strokes == par + 2) {
     return "Double Bogey" ;
  } else if (strokes >= par + 3) {
     return "Go Home!" ;
  } else {
     return "Change Me";
  }
}
```
## 74.Selecting from Many Options with Switch Statements

```js
function caseInSwitch(val) {
  var answer = "";
  
  switch(val){
    case 1:
      return "alpha";
      break;
    case 2:
      return "beta";
      break;
    case 3:
      return "gamma";
      break;
    case 4:
      return "delta";
      break;
  }
    return answer; 
```
## 75.Adding a Default Option in Switch Statements
```js
function switchOfStuff(val) {
  var answer = "";
 switch(val){
    case 'a': answer = 'apple'; 
    break;
    case 'b': answer = 'bird'; 
    break;
    case 'c': answer = 'cat'; 
    break;
    default: answer = 'stuff';
  }
  return answer;  
}
```
## 76.
```js
function sequentialSizes(val) {
  var answer = "";
  switch(val){
    case 1: 
    case 2: 
    case 3:
      answer = "Low";
      break;
    case 4: 
    case 5: 
    case 6:
      answer = "Mid";
      break;
    case 7: 
    case 8: 
    case 9:
      answer = "High";
  }
   return answer; 
```
## 77.Replacing If Else Chains with Switch
```js
function chainToSwitch(val) {
  var answer = "";
  
  switch (val) {
    case "bob":
      answer = "Marley";
      break;
    case 42:
      answer = "The Answer";
      break;
    case 1:
      answer = "There is no #1";
      break;
    case 99:
      answer = "Missed me by this much!";
      break;
    case 7 :
      answer = "Ate Nine";
      break;
  }
  
  return answer;  
}

```
## 78.Returning Boolean Values from Functions
```js
function isLess(a, b) {
  return a<=b;
}
isLess(9, 15);
```
## 79.
```js
function abTest(a, b) {

    if (a < 0 || b < 0) {
    return;
    }

  return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
}

```
