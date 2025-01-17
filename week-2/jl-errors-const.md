> paste [this markdown](https://raw.githubusercontent.com/janke-learning/error-exercises/master/const.md) into this file and fix the errors!      
> references: [errors & life-cycle](https://github.com/janke-learning/errors-and-life-cycle), [exercise repo](https://github.com/janke-learning/errors)

# Variable Errors


### exercises
* [missing variable name](#missing-variable-name)
* [reassigning to constant](#reassigning-to-constant)
* [unassigned const declaration](#unassigned-const-declaration)

---

### missing variable name

broken code:
```js
const = 5;
```
error message:
```js
Unexpected token =
```
classification:
* creation phase 
* syntax 

the fix:
```js
const five = 5;
```
your notes: The constant must be declared.

[TOP](#variable-errors)

---


## reassigning to constant

broken code:
```js
const a = 9;
a = 0;
```
error message:
```
TypeError: Assignment to constant variable.
```
classification:
* execution phase 
* semanitc 

the fix:
```js
const a = 9;
```
your notes: The constants can't change of value.

[TOP](#variable-errors)

---

## unassigned const declaration

broken code:
```js
const a;
a = 0;
```
error message:
```
SyntaxError: Missing initializer in const declaration.
```
classification:
* creation phase 
* syntax 

the fix:
```js
const a = 0 ;
```
your notes: const   The constants  must be assigned a value when they are declared.

[TOP](#variable-errors)

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
