> paste [this markdown](https://raw.githubusercontent.com/janke-learning/error-exercises/master/objects.md) into this file and fix the errors!    
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/errors_solutions.MD)  (of the old version)  
> references: [errors & life-cycle](https://github.com/janke-learning/errors-and-life-cycle), [exercise repo](https://github.com/janke-learning/errors)
# Object Errors

* [too-far object access](#too-far-object-access)
* [access property directly](#access-property-directly)

---

## too-far object access

broken code:
```js
let a = {b:3};
let b = a.b.3
```
error message:
```
SyntaxError: Unexpected number
```
classification:
* creation phase 
* syntax 

the fix:
```js
SyntaxError: Unexpected number
```
your notes: The number 3 is the value of the property b which belong to the object a. 

[TOP](#object-errors)

---

## access property directly
broken code:
```js
let x = {b:'e'};
let y = b.e;
```
error message:
```
ReferenceError: b is not defined.
```
classification:
* execution phase 
* semanitc 

the fix:
```js
let x = {b:'e'};
let y = x.b;
```
your notes: The way to access to the property b in object x it was incorrect.

[TOP](#object-errors)


___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
