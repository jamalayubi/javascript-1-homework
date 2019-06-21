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

### 69. Introducing Else If Statements
```js
function testElseIf(val) {
  if (val > 10) {
       return "Greater than 10";
  } else if (val < 5) {
       return "Smaller than 5";
  }
  else{
       return "Between 5 and 10";
  }
}
// Change this value to test
testElseIf(7);
```
### 70. Logical Order in If Else Statements
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
// Change this value to test
orderMyLogic(7);
```

### 71. Chaining If Else Statements
```js
function testSize(num) {
  // Only change code below this line
  if (num < 5){
     return "Tiny";
  } else if (num < 10){
     return "Small";
  } else if (num < 15){
    return "Medium";
  } else if (num < 20){
     return "Large";
  } else if (num >= 20)
  {return "Huge"
  } else{
    return "Change Me";
  }
}
  // Only change code above this line
 // Change this value to test
testSize(7);
```
## 72. Golf Code
```js
var names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];
function golfScore(par, strokes) {
  // Only change code below this line
  if (strokes == 1) { 
    return names [0];
  } else if (strokes <= par-2 ){
     return names [1];
  } else if (strokes <= par-1 ){
    return names [2];
  } else if (strokes == par){
    return names [3];
  } else if(strokes >= par + 3){
    return names [6];
  } else if(strokes == par + 2){
     return names [5];
  } else if(strokes == par + 1){
    return names [4];
  } else {
    return "Change Me";
  }
  // Only change code above this line
}
// Change these values to test
golfScore(5, 4);
```
### 73. Selecting from Many Options with Switch Statements
```js
function caseInSwitch(val) {
  var answer = "";
 // Only change code below this line
switch(val) {
  case  1:
    answer ="alpha";
    break;
  case  2:
     answer ="beta";
    break;
  case 3:
     answer ="gamma";
    break;
  case 4:
     answer ="delta";
    break;
  // Only change code above this line  
  return answer;  
 }
}
// Change this value to test
caseInSwitch(5);
```

### 74. Adding a Default Option in Switch Statements
```js
function switchOfStuff(val) {
  var answer = "";
  // Only change code below this line
  switch (val) {
  case "a":
    answer =  "apple";
    break;
  case "b":
    answer = "bird";
    break;
  case "c":
    answer =  "cat";
    break;
  default:
     answer =  "stuff";
    break;
}
   // Only change code above this line  
  return answer;  
}
// Change this value to test
switchOfStuff("a");
```
### 75.Multiple Identical Options in Switch Statements
```js
function sequentialSizes(val) {
  var answer = "";
  // Only change code below this line
  switch(val) {
  case 1:
  case 2:
  case 3:
    answer  = "Low";
    break;
  case 4:
  case 5:
  case 6:
   answer  = "Mid";
    break;
  case 7:
  case 8:
  case 9:
    answer  = "High";
    break;
}
  // Only change code above this line  
  return answer;  
}
// Change this value to test
sequentialSizes(5);

```
### 76.Replacing If Else Chains with Switch

```js
function chainToSwitch(val) {
  var answer = "";
  // Only change code below this line
  switch(val) {
  case "bob":
    answer = "Marley";
    break;
  case 42:
    answer = "The Answer";
    break;
  case 1:
    answer = "There is no #1";
    break;
  case  99:
    answer = "Missed me by this much!";
    break;
  case 7:
    answer = "Ate Nine";
    break;
  }
  // Only change code above this line  
  return answer;  
}
// Change this value to test
chainToSwitch(7);
```

### 77.Returning Boolean Values from Functions

```js
function isLess(a, b) {
  // Fix this code
    return a < b;
}
// Change these values to test
isLess(10, 15);
```

### 78.Return Early Pattern for Functions
```js
// Setup
function abTest(a, b) {
  // Only change code below this line
  if(a<0 || b<0)
   return;
  // Only change code above this line
  return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
}

// Change values below to test your code
abTest(2,2);
```
### 79.Counting Cards
```js
var count = 0;
function cc(card) {
  // Only change code below this line
  switch(card)
  {
    case 2:
    case 3:
    case 4:
    case 5:
    case 6:
    count+=1;
    break;
    case 10:
    case 'J':
    case 'Q':
    case 'K':
    case 'A':
    count-=1;
    break;
  }
   if (count > 0){
     return count + " Bet";
   } else{
     return count + " Hold";
   }
  // Only change code above this line
}
cc(2); cc(3); cc(7); cc('K'); cc('A');
```
### 80. Build JavaScript Objects
```js
// Example
var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"]
};
// Only change code below this line.
var myDog = {
  "name": "myDog",
  "legs": 4,
  "tails": 1,
  "friends": ["Ali"]
}
```
### 81. Accessing Object Properties with Dot Notation
```js
// Setup
var testObj = {
  "hat": "ballcap",
  "shirt": "jersey",
  "shoes": "cleats"
};
// Only change code below this line

var hatValue = testObj.hat;      // Change this line
var shirtValue = testObj.shirt;    // Change this line
```
### 82. Accessing Object Properties with Bracket Notation
```js
// Only change code below this line

var entreeValue = testObj["an entree"];   // Change this line
var drinkValue = testObj["the drink"];    // Change this line
```
### 83. Accessing Object Properties with Variables
```js

// Setup
var testObj = {
  12: "Namath",
  16: "Montana",
  19: "Unitas"
};
var playerNumber= 16;       // Change this Line
var player = testObj[playerNumber];   // Change this Line
```
### 84. pdating Object Properties
```js 

// Setup
var testObj = {
  "an entree": "hamburger",
  "my side": "veggies",
  "the drink": "water"
};
// Only change code below this line

var entreeValue = testObj["an entree"];   // Change this line
var drinkValue = testObj["the drink"];  // Change this line
```
### 85. Add New Properties to a JavaScript Object
```js

// Example
var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"]
};

ourDog.name = "Happy Camper";

// Setup
var myDog = {
  "name": "Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line.

myDog.name = "happy coder";
```
### 86. Delete Properties from a JavaScript Object
```js
// Example
var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"]
};

ourDog.bark = "bow-wow";

// Setup
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line.
myDog.bark = "woof";
```
### 87. Using Objects for Lookups
```js
// Example
var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"],
  "bark": "bow-wow"
};

delete ourDog.bark;

// Setup
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"],
  "bark": "woof"
};

// Only change code below this line.

delete myDog.tails;
```
### 88. Testing Objects for Properties
```js

```
### 89. Manipulating Complex Objects
### 90. Accessing Nested Objects
### 91. Accessing Nested Arrays
### 92. Record Collection
### 93. Iterate with JavaScript While Loops
### 94. Iterate with JavaScript For Loops
### 95. Iterate Odd Numbers With a For Loop
### 96. Count Backwards With a For Loop
### 97. Iterate Through an Array with a For Loop
### 98. Nesting For Loops
### 99. Iterate with JavaScript Do...While Loops
### 100. Profile Lookup
### 101. Generate Random Fractions with JavaScript
### 102. Generate Random Whole Numbers with JavaScript
### 103. Generate Random Whole Numbers within a Range
### 104. Use the parseInt Function
### 105. Use the parseInt Function with a Radix
### 106. Use the Conditional (Ternary) Operator
### 107. Use Multiple Conditional (Ternary) Operators
