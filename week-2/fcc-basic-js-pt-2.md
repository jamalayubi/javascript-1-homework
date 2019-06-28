> complete the rest of [basic JS exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript) on FCC and paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/freecode_camp_solutions.MD) 


## Testing Objects for Properties
```js
// Setup
var myObj = {
  gift: "pony",
  pet: "kitten",
  bed: "sleigh"
};

function checkObj(checkProp) {
  // Your Code Here
  
  return "Change Me!";
}

// Test your code by modifying these values
checkObj("gift");
```
## Manipulating Complex Objects
```js
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [ 
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  }
  // Add record here
  ,{
    "artist": "Guns N' Roses",
    "title": "Use Your Illusion I",
    "release_year": 1991,
    "formats": [ 
      "CD",
      "Cassette Tape"
    ],
    "gold": true
  }
];
```
## Accessing Nested Objects
```js
// Setup
var myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};
var gloveBoxContents =  myStorage.car.inside["glove box"]; // Change this line
```
## Accessing Nested Arrays
```js
// Setup
var myPlants = [
  { 
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }  
];
// Only change code below this line
var secondTree = myPlants[1].list[1]; // Change this line
```
## Record Collection
```js
// Setup
var collection = {
    "2548": {
      "album": "Slippery When Wet",
      "artist": "Bon Jovi",
      "tracks": [ 
        "Let It Rock", 
        "You Give Love a Bad Name" 
      ]
    },
    "2468": {
      "album": "1999",
      "artist": "Prince",
      "tracks": [ 
        "1999", 
        "Little Red Corvette" 
      ]
    },
    "1245": {
      "artist": "Robert Palmer",
      "tracks": [ ]
    },
    "5439": {
      "album": "ABBA Gold"
    }
};
// Keep a copy of the collection for tests
var collectionCopy = JSON.parse(JSON.stringify(collection));
// Only change code below this line
function updateRecords(id, prop, value) {
  if (!(value=="" &&collectionCopy[id].hasOwnProperty(prop) )){
    switch(prop){
     case "album":
     case "artist":
          collectionCopy[id][prop]=value;
          break;
     case "tracks":
          if(collectionCopy[id].hasOwnProperty(prop)){
            collectionCopy[id][prop].push(value);
           }
          else{
            collectionCopy[id][prop] = [value];
          }
    }      
  }else{
    delete collectionCopy[id][prop];
  }
    return collectionCopy;
}
// Alter values below to test your code
updateRecords(5439, "artist", "ABBA");
```
## Iterate with JavaScript While Loops
```js
// Setup
var myArray = [];
// Only change code below this line.
var i = 0;
while(i < 5) {
  myArray.push(i);
  i++;
}
```
## Iterate with JavaScript For Loops
``` js
// Example
var ourArray = [];

for (var i = 0; i < 5; i++) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
var myArray = [];
for (var i = 1; i < 6; i++) {
  myArray.push(i);
}
```
## Iterate Odd Numbers With a For Loop
```js
// Example
var ourArray = [];

for (var i = 0; i < 10; i += 2) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for (var i = 1; i < 10; i += 2) {
  myArray.push(i);
}
```
## Count Backwards With a For Loop
```js
// Example
var ourArray = [];

for (var i = 10; i > 0; i -= 2) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.

for (var i = 9; i > 0; i -= 2) {
   myArray.push(i);
}
```
## Iterate Through an Array with a For Loop
```js
// Example
var ourArr = [ 9, 10, 11, 12];
var ourTotal = 0;

for (var i = 0; i < ourArr.length; i++) {
  ourTotal += ourArr[i];
}

// Setup
var myArr = [ 2, 3, 4, 5, 6];

// Only change code below this line

var total = 0;
for (var i = 0; i < myArr.length; i++) {
  total += myArr[i];
}
```
## Nesting For Loops
```js
function multiplyAll(arr) {
  var product = 1;
  // Only change code below this line
  
for (var i=0; i < arr.length; i++) {
  for (var j=0; j < arr[i].length; j++) {
      product*=arr[i][j];
      console.log(arr[i][j]);
      console.log(arr.length);
      console.log(arr[i].length);
  }
}
  // Only change code above this line
  return product;

}
// Modify values below to test your code
multiplyAll([[1],[2],[3]]);
```
## Iterate with JavaScript Do...While Loops
```js
// Setup
var myArray = [];
var i = 10;

// Only change code below this line.
do {
  myArray.push(i);
  i++;
}while (i < 5)
```
## Profile Lookup
```js
//Setup
var contacts = [
    {
        "firstName": "Akira",
        "lastName": "Laine",
        "number": "0543236543",
        "likes": ["Pizza", "Coding", "Brownie Points"]
    },
    {
        "firstName": "Harry",
        "lastName": "Potter",
        "number": "0994372684",
        "likes": ["Hogwarts", "Magic", "Hagrid"]
    },
    {
        "firstName": "Sherlock",
        "lastName": "Holmes",
        "number": "0487345643",
        "likes": ["Intriguing Cases", "Violin"]
    },
    {
        "firstName": "Kristian",
        "lastName": "Vos",
        "number": "unknown",
        "likes": ["JavaScript", "Gaming", "Foxes"]
    }
];


function lookUpProfile(name, prop){
// Only change code below this line
var i=0;
var msg;
do{
  console.log(contacts[i]["firstName"]);
  if(contacts[i]["firstName"]==name) {
    if(contacts[i].hasOwnProperty(prop)){
      msg=contacts[i][prop];
    }else{
        msg="No such property";
    }
  }
  i++;  
}while (i<contacts.length && contacts["firstName"]!=name)
if (!msg)
   msg="No such contact";
return msg;
// Only change code above this line
}

// Change these values to test your function
lookUpProfile("Akira", "likes");
```
## Generate Random Fractions with JavaScript
```js
function randomFraction() {
  // Only change code below this line.
  return Math.random();
  // Only change code above this line.
}
```
## Generate Random Whole Numbers with JavaScript
```js
var randomNumberBetween0and19 = Math.floor(Math.random() * 20);
function randomWholeNum() {
  // Only change code below this line.
var randomNumberBetween0and9 = Math.floor(Math.random() * 10);
  return randomNumberBetween0and9;
}
```
## Generate Random Whole Numbers within a Range
```js
// Example
function ourRandomRange(ourMin, ourMax) {

  return Math.floor(Math.random() * (ourMax - ourMin + 1)) + ourMin;
}

function randomRange(myMin, myMax) {
  return Math.floor(Math.random() * (myMax- myMin + 1)) + myMin; 
}
// Change these values to test your function
var myRandom = randomRange(5, 15);
```
## Use the parseInt Function
```js
function convertToInteger(str) {
  return parseInt(str)
}
convertToInteger("56");
```
## Use the parseInt Function with a Radix
```js
function convertToInteger(str) {
  var a = parseInt(str,2);
  return a;
}
convertToInteger("10011");
```
## Use the Conditional (Ternary) Operator
```js
function checkEqual(a, b) {
  return a == b ? true : false ;
}
checkEqual(1, 2);
```
## Use Multiple Conditional (Ternary) Operators
```js 
function checkSign(num) {
  return (num > 0) ? "positive" : (num < 0) ? "negative" : "zero";
}
checkSign(10);
```

