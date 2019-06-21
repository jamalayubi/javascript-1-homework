> complete [the basic JS exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript) through _Counting Cards_ & paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/freecode_camp_solutions.MD) 

#  Homework Basic Javascript 


### 1. Comment Your Code

```js
// this is my first comment
/* this is a multi line comment */
```

### 2. Declare Variables
```js
var myName;
```

### 3.Storing Values with the Assignment Operator
```js
a = 7;
b = a;
a = b;
```

### 4. Initializing Variables with the Assignment Operator
```js
var a = 9;
```

### 5. Understanding Uninitialized Variables
```js
var a = 5;
var b = 10;
var c = "I am a";
```
### 6. Understanding Case Sensitivity in Variables
```js
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```

### 7.Add Two Numbers (+)
```js
var sum = 10 + 0;
sum = 10 + 10;
```
### 8. Subtract One Number from Another
```js
var difference = 45 - 33;
```
### 9. Multiply Two Numbers
```js
var product = 8 * 10;
```
### 10. Divide One Number by Another (/)
```js
var quotient = 66 / 33;
```
### 11 .Increment a Number (i++)

```js
var myVar = 87;
myVar++;
```

### 12. Decrement a Number (i--)
```js
myVar--;
```


### 13. Create Decimal Numbers
```js
var myDecimal = 8.8;
```

### 14. Multiply Two Decimals
```js
var product = 2.0 * 2.5;
```

### 15. Divide One Decimal by Another
```js
var quotient = 4.4 / 2.0;
```
### 16. Finding a Remainder
```js
var remainder;
remainder = 11 % 3;
```
### 17. Compound Assignment With Augmented Addition (+=)
```js
a += 12;
b += 9;
c += 7;
```
### 18. Compound Assignment With Augmented Subtraction (-=)

```js
a -= 6;
b -= 15;
c -= 1;
```
### 19. Compound Assignment With Augmented Multiplication
```js
a *= 5;
b *= 3;
c *= 10;
```
### 20. Compound Assignment With Augmented Division
```js
a /= 12;
b /= 4;
c /= 11;
```

### 21. Declare String Variables
with  ``` " "  ```
```js
var myFirstName = "Jamal";
var myLastName = "Ayubi";
```

### 22. Escaping Literal Quotes in Strings
Using *backlash* ```\``` in the beginning and in the end of your quotes.
```js
var myStr = "I am a \"double quoted\" string inside \"double quotes\".";
```
### 23. Quoting Strings with Single Quotes
String values in JS may be written with single or double quotes.
```js
var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```

### 24. Escape Sequences in Strings
Reasons to use escaping characters:
- is to allow you to use characters you might not otherwise be able to type out, such as a backspace.
- is to allow you to represent multiple quotes in a string without JS misinterpreting what you mean.

```js
var myStr = 'FirstLine\n\t\\SecondLine\nThirdLine';
```

### 25. Concatenating Strings with Plus Operator
```js
var myStr = "This is the start. " +  "This is the end.";

## 26. Concatenating Strings with the Plus Equals Operator
```js
var myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";
```
### 27. Constructing Strings with Variables
```js
var myStr = "My name is " + myName + " and I am well!";
```
### 28. Appending Variables to Strings
```js
var someAdjective = "boring";
var myStr = "Learning to code is ";
myStr += someAdjective;
```
### 29. Find the Length of a String
```js
lastNameLength = lastName.length;
```
### 30. Use Bracket Notation to Find the First Character in a String
```js
firstLetterOfLastName = lastName[0];
```
### 31. Understand String Immutability
String values are *immutable*, means that they cannot be altered once created.
```js
myStr = "Hello World";
```
### 32. Use Bracket Notation to Find the Nth Character in a String
```js
var thirdLetterOfLastName = lastName[2];
```
### 33. Use Bracket Notation to Find the Last Character in a String
Use  ```.length-1```
```js
var lastLetterOfLastName = lastName[lastName.length-1];
```
### 34. Use Bracket Notation to Find the Nth-to-Last Character in a String
```js
var secondToLastLetterOfLastName = lastName[lastName.length - 2];
```
### 35. Word Blanks
```js
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
  var result = "The " + myAdjective + " " + myNoun + " " + myVerb + " " + myAdverb + ".";
  return result;
}
wordBlanks("cat", "little", "hit", "slowly");
```
### 36. Store Multiple Values in one Variable using JavaScript Arrays
Array variables for storing several pieces of data in one place.
```js
var myArray = ["Jamal", 25];
```
### 37. Nest one Array within Another Array
```js
var myArray = [["Bulls", 23], ["White Sox", 45]];
```
### 39. Modify Array Data With Indexes
```js
myArray[0] = 45;
```
### 40. Access Multi-Dimensional Arrays With Indexes
```js
var myData = myArray[2][1];
```
### 41. Manipulate Arrays With push()
Adding an extra to the last array.
```js
myArray.push(["dog", 3]);
```
### 42. Manipulate Arrays With pop()
You can pop off the last array, and store it in a variable.
```js
var removedFromMyArray = myArray.pop();
```
### 43. Manipulate Arrays With shift()
removing the first in the array
```js
var removedFromMyArray = myArray.shift();
```
### 44. Manipulate Arrays With unshift()
Adding an extra to the first in the array.
```js
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();

myArray.unshift(["Paul",35]);
```
### 45. Shopping List
```js
var myList = [["rudbull", 10] , ["beers", 20] , ["chips", 10], [ "water", 5], ["cola", 15]];
```
### 46. Write Reusable JavaScript with Functions
```js
function reusableFunction() {
  console.log("Hi World");
}

reusableFunction();
```
### 47. Passing Values to Functions with Arguments
```js
function functionWithArgs (a , b) {
console.log(a + b);
}
functionWithArgs (1 , 2);
functionWithArgs (7 , 9);
```
### 48. Global Scope and Functions
Scope refers to the visibility of variables.
Variables which are defined **outside of a function block** have **Global scope**.
Variables which are used **without the ```var```** keyword are automatically created in the ```global``` scope. This can create unintended consequences elsewhere in your code or when running a function again. You should always declare your variables with ```var```.
```js
var myGlobal = 10;
function fun1() {
  oopsGlobal = 5;
}
```
### 49. Local Scope and Functions
```js
function myLocalScope() {
var myVar = 'use strict';
}
myLocalScope();
```
### 50. Global vs. Local Scope in Functions
```js
var outerWear = "T-Shirt";
function myOutfit() {
  var outerWear = "sweater";
  return outerWear;
}
myOutfit();
```
### 51. Return a Value from a Function with Return
Use a ```return``` statement to send a value back out of a function.
```js
function timesFive (num) {
  return num * 5;
}
timesFive(5);
timesFive(2);
timesFive(0);
```
### 52. Understanding Undefined Value returned from a Function
```js
function addFive() {
  sum = sum + 5;
}
```
### 53. Assignment with a Returned Value
```js
var processed = 0;
function processArg(num) {
  return (num + 3) / 5;
}
processed = processArg(7);
```
### 54. Stand in Line
 A **queue** is an abstract Data Structure where items are kept in order.
 New items can be added (```push```) at the back of the queue and old items are taken off (```shift```) from the front of the queue.

Add the number to the end of the array = ```push```
Remove the first element of the array = ```shift```
Then return the element that was removed = using ```return```.
```js
function nextInLine(arr, item) {
  arr.push(item);
  return  arr.shift();
}
```
### 55. Understanding Boolean Values
```js
function welcomeToBooleans() {
return true;
}
```
### 56. Use Conditional Logic with If Statements
```js
function trueOrFalse(wasThatTrue) {
    if (wasThatTrue) {
    return "Yes, that was true";
  }
  return "No, that was false";
}
trueOrFalse(true);
```
### 57. Comparison with the Equality Operator
```js
function testEqual(val) {
  if (val == 12) {
    return "Equal";
  }
  return "Not Equal";
}
testEqual(12);
```
### 58. Comparison with the Strict Equality Operator
However, unlike the equality operator, which attempts to convert both values being compared to a common type, the strict equality operator does not perform a type conversion.

If the values being compared have different types, they are considered unequal, and the strict equality operator will return false.
```js
function testStrict(val) {
  if (val === 7) {
    return "Equal";
  }
  return "Not Equal";
}
testStrict(10);
```
### 59. Practice comparing different values
```js
function compareEquality(a, b) {
  if (a === b) {
    return "Equal";
  }
  return "Not Equal";
}
compareEquality(10, "10");
```
### 60. Comparison with the Inequality Operator
```js
function testNotEqual(val) {
  if (val != 99) {
    return "Not Equal";
  }
  return "Equal";
}
testNotEqual(10);
```
### 61. Comparison with the Strict Inequality Operator
```js
function testStrictNotEqual(val) {
  if (val !== 17) {
    return "Not Equal";
  }
  return "Equal";
}

testStrictNotEqual(10);
```
### 62. Comparison with the Greater Than Operator
```js
function testGreaterThan(val) {
  if (val > 100) {
    return "Over 100";
  }

  if (val > 10) {
    return "Over 10";
  }

  return "10 or Under";
}

testGreaterThan(10);
```
### 63. Comparison with the Greater Than Or Equal To Operator
```js
function testGreaterOrEqual(val) {
  if (val >= 20) {
    return "20 or Over";
  }

  if (val >= 10) {
    return "10 or Over";
  }

  return "Less than 10";
}


testGreaterOrEqual(10);
```
### 64. Comparison with the Less Than Operator
```js
function testLessThan(val) {
  if (val < 25) {
    return "Under 25";
  }

  if (val < 55) {
    return "Under 55";
  }

  return "55 or Over";
}

testLessThan(10);
```
### 65. Comparison with the Less Than Or Equal To Operator
```js
function testLessOrEqual(val) {
  if (val <= 12) {
    return "Smaller Than or Equal to 12";
  }

  if (val <=24) {
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

testLessOrEqual(10);

```
### 66. Comparison with the Logical And Operator
```js
function testLogicalAnd(val) {

  if (val >= 25 && val <= 50) {
      return "Yes";
  }

  return "No";
}


testLogicalAnd(10);
```
### 67. Comparison with the Logical Or Operator
```js
function testLogicalOr(val) {


  if (val < 10 || val > 20 ) {

    return "Outside";
  }

  return "Inside";
}


testLogicalOr(15);
```
### 68. Introducing Else Statements

```js
function testElse(val) {
  var result = "";

  if (val > 5) {
    result = "Bigger than 5";
  }

  else {
    result = "5 or Smaller";
  }


  return result;
}


testElse(4);

```
