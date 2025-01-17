> begin [the basic data structure exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-data-structures) and paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on 

## Basic Data Structures: Use an Array to Store a Collection of Data
```js 
let yourArray = [1,true,"hello","mame", null];
```
## Basic Data Structures: Access an Array's Contents Using Bracket Notation
```js
let myArray = ["a", "b", "c", "d"];
// change code below this line
myArray[1]="n";
//change code above this line
console.log(myArray);

```
## Basic Data Structures: Add Items to an Array with push() and unshift()
```js
function mixedNumbers(arr) {
  // change code below this line
   arr.unshift('I', 2, 'three');
   arr.push(7, 'VIII', 9);
  // change code above this line
  return arr;
}
// do not change code below this line
console.log(mixedNumbers(['IV', 5, 'six']));
```
## Remove Items from an Array with pop() and shift()
``` js
function popShift(arr) {
  let popped= arr.pop(); // change this line
  let shifted = arr.shift(); // change this line
   return [shifted, popped];
}
// do not change code below this line
console.log(popShift(['challenge', 'is', 'not', 'complete']));
```
## Remove Items Using splice()
``` js
function sumOfTen(arr) {
  // change code below this line
  arr.splice(0, 1);
  arr.splice(1, 1);
  arr.splice(2, 2); 
  // change code above this line
  return arr.reduce((a, b) => a + b);
}
// do not change code below this line
console.log(sumOfTen([2, 5, 1, 5, 2, 1]));
```
## Add Items Using splice()
``` js
function htmlColorNames(arr) {
  // change code below this line
  arr.splice(0,1,'DarkSalmon');
  arr.splice(1,1,'BlanchedAlmond');
  // change code above this line
  return arr;
} 
// do not change code below this line
console.log(htmlColorNames(['DarkGoldenRod', 'WhiteSmoke', 'LavenderBlush', 'PaleTurqoise', 'FireBrick']));
```
## Copy Array Items Using slice()
```js
function forecast(arr) {
  // change code below this line
 return  arr.slice(2,4);
}
// do not change code below this line
console.log(forecast(['cold', 'rainy', 'warm', 'sunny', 'cool', 'thunderstorms']));
```
##  Copy an Array with the Spread Operator
```js
function copyMachine(arr, num) {
  let newArr = [];
  while (num >= 1) {
    // change code below this line
  newArr = [[...arr],...newArr];
    // change code above this line
    num--;
  }
  return newArr;
}
// change code here to test different cases:
console.log(copyMachine([true, false, true], 2));
```
## Combine Arrays with the Spread Operator
```js
function spreadOut() {
  let fragment = ['to', 'code'];
  let sentence = ["learning", ...fragment, "is", "fun"]; // change this line
  return sentence;
}

// do not change code below this line
console.log(spreadOut());
```

## Check For The Presence of an Element With indexOf()
```js

function quickCheck(arr, elem) {
  // change code below this line
 return (arr.indexOf(elem))>0?true:false;
  // change code above this line
}
// change code here to test different cases:
console.log(quickCheck(['squash', 'onions', 'shallots'], 'mushrooms'));
```

## Iterate Through All an Array's Items Using For Loops
```js
function filteredArray(arr, elem) {
  let newArr = [];
  // change code below this line
  let tryElem;

  for (let i=0 ; i<arr.length; i++){
      tryElem = true;     
    for (let j=0;j<arr[i].length;j++){
      console.log(arr[i][j]);
      console.log(elem);   
      if (arr[i][j] == elem){
       tryElem =false;
      }
     if(tryElem && (j == arr[i].length-1))
      newArr.push(arr[i]);
    }
  }
  // change code above this line
  return newArr;
}
// change code here to test different cases:
console.log(filteredArray([[10, 8, 3], [14, 6, 23], [3, 18, 6], [10, 8, 3]], 9));
```
## Create complex multi-dimensional arrays
```js
let myNestedArray = [
  // change code below this line
  ['unshift', false, 1, 2, 3, 'complex', 'nested'],
  ['loop', 'shift', 6, 7, 1000, 'method'],
  ['concat', false, true, 'spread', 'array',["deep"]],
  ['mutate', 1327.98, 'splice', 'slice', 'push', [["deeper"]]],
  ['iterate', 1.3849, 7, '8.4876', 'arbitrary', 'depth', [[["deepest"]]] ]
  // change code above this line
];
```
## Add Key-Value Pairs to JavaScript Objects
```js
let foods = {
  apples: 25,
  oranges: 32,
  plums: 28
};
// change code below this line
foods.bananas=13;
foods.grapes = 35;
foods.strawberries=27;
// change code above this line

console.log(foods);
```
## Modify an Object Nested Within an Object
```js
let userActivity = {
  id: 23894201352,
  date: 'January 1, 2017',
  data: {
    totalUsers: 51,
    online: 42
  }
};

// change code below this line
userActivity.data.online=45;
// change code above this line
console.log(userActivity);
```
## Access Property Names with Bracket Notation
```js
let foods = {
  apples: 25,
  oranges: 32,
  plums: 28,
  bananas: 13,
  grapes: 35,
  strawberries: 27
};
// do not change code above this line
function checkInventory(scannedItem) {
  // change code below this line
return foods[scannedItem];
}
// change code below this line to test different cases:
console.log(checkInventory("apples"));
```

## Use the delete Keyword to Remove Object Properties
```js
let foods = {
  apples: 25,
  oranges: 32,
  plums: 28,
  bananas: 13,
  grapes: 35,
  strawberries: 27
};
// change code below this line
delete foods.oranges;
delete foods.plums;
delete foods.strawberries;
// change code above this line
console.log(foods);
```
## Check if an Object has a Property
```js
let users = {
  Alan: {
    age: 27,
    online: true
  },
  Jeff: {
    age: 32,
    online: true
  },
  Sarah: {
    age: 48,
    online: true
  },
  Ryan: {
    age: 19,
    online: true
  }
};

function isEveryoneHere(obj) {
  // change code below this line

return (obj.hasOwnProperty('Alan') && obj.hasOwnProperty('Jeff') && obj.hasOwnProperty('Sarah') && obj.hasOwnProperty('Ryan'));
  // change code above this line
}
console.log(isEveryoneHere(users));
```

## Iterate Through the Keys of an Object with a for...in Statement
```js
let users = {
  Alan: {
    age: 27,
    online: false
  },
  Jeff: {
    age: 32,
    online: true
  },
  Sarah: {
    age: 48,
    online: false
  },
  Ryan: {
    age: 19,
    online: true
  }
};
function countOnline(obj) {
  // change code below this line
  let online = 0;
  for (let user in obj) {
      if (obj[user].online) online++;  
  };
  return online;
  // change code above this line
}
console.log(countOnline(users));
```
## Generate an Array of All Object Keys with Object.keys()
```js
let users = {
  Alan: {
    age: 27,
    online: false
  },
  Jeff: {
    age: 32,
    online: true
  },
  Sarah: {
    age: 48,
    online: false
  },
  Ryan: {
    age: 19,
    online: true
  }
};
function getArrayOfUsers(obj) {
  // change code below this line
  return Object.keys(obj);
  // change code above this line
}
console.log(getArrayOfUsers(users));
```
## Modify an Array Stored in an Object
```js
let user = {
  name: 'Kenneth',
  age: 28,
  data: {
    username: 'kennethCodesAllDay',
    joinDate: 'March 26, 2016',
    organization: 'freeCodeCamp',
    friends: [
      'Sam',
      'Kira',
      'Tomo'
    ],
    location: {
      city: 'San Francisco',
      state: 'CA',
      country: 'USA'
    }
  }
};

function addFriend(userObj, friend) {
  // change code below this line  
   userObj.data.friends.push(friend);
   return userObj.data.friends;
    // change code above this line
}
console.log(addFriend(user, 'Pete'));
```


