> paste [this markdown of exercises](https://raw.githubusercontent.com/janke-learning/function-exercises/master/turtle-shuffle.md) into this file and complete the exercises!   
> references: [javascript.info functions](https://javascript.info/function-basics), [function examples to study](https://github.com/janke-learning/function-exercises/blob/master/examples-to-study.md) 

# Turtle Shuffle

some trickier function exercises before moving on.
* Reading function behavior, and using them correctly
* Defining vs. Calling functions
    * Defining: when you write the funciton -> function name() {}.  This creates the function in memory
    * Calling: using the function to compute new values -> name().  This creates a new frame and returns a new value
* Arguments
* Lexical Scope
* Return Values

### Index
* [completed example](#completed-example)
* exercises
    * [number 1](#1)
    * [number 2](#2)
    * [number 3](#3)
    * [number 4](#4)
    * [number 5](#5)
    * [number 6](#6)
    * [number 7](#7)
    * [number 8](#8)
    * [number 9](#9)

---

## Completed Example

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20turtle%28_1%2C%20_2%2C%20_3%29%20%7B%0A%20%20var%20result%20%3D%20%22%22%3B%0A%20%20var%20the_rest%20%3D%20%22tle%22%3B%0A%20%20result%20%3D%20_1%20%2B%20_2%20%2B%20_3%20%2B%20the_rest%3B%0A%20%20return%20result%3B%0A%7D%0Aconst%20return_val%20%3D%20turtle%28%22t%22%2C%20%22u%22%2C%20%22r%22%29%3B%0Aconsole.assert%28return_val%20%3D%3D%3D%20\'turtle\'%2C%20%221%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
{ // completed example
  function turtle(_1, _2, _3) { 
    var result = "";
    var the_rest = "tle";
    result = _1 + _2 + _3 + the_rest;
    return result;
  }
  const return_val = turtle("t", "u", "r");
  console.assert(return_val === 'turtle', "example: return_val === " + return_val);
};
```

---

## Exercises

### 1

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20turtle%28_1%2C%20_2%2C%20_3%29%20%7B%0A%20%20var%20result%20%3D%20%22%22%3B%0A%20%20var%20the_start%20%3D%20%22tur%22%3B%0A%20%20result%20%3D%20the_start%20%2B%20_1%20%2B%20_2%20%2B%20_3%3B%0A%20%20return%20result%3B%0A%7D%0Aconst%20return_val%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val%20%3D%3D%3D%20\'turtle\'%2C%20%222%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
{  // 1

};
```

### 2

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20turtle%28_1%2C%20_2%29%20%7B%0A%20%20var%20result%20%3D%20%22%22%3B%0A%20%20var%20the_start%20%3D%20%22tu%22%3B%0A%20%20var%20the_end%20%3D%20%22le%22%3B%0A%20%20result%20%3D%20the_start%20%2B%20_1%20%2B%20_2%20%2B%20the_end%3B%0A%20%20return%20result%3B%0A%7D%0Aconst%20return_val%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val%20%3D%3D%3D%20\'turtle\'%2C%20%223%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
{  // 2

};
```

### 3

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20turtle%28_1%2C%20_2%29%20%7B%0A%20%20var%20result%20%3D%20%22t%22%20%2B%20_1%20%2B%20%22r%22%20%2B%20_2%3B%0A%20%20return%20result%3B%0A%7D%0Aconst%20return_val%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val%20%3D%3D%3D%20\'turtle\'%2C%20%224%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
{  // 3

};
```

### 4

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20turtle%28_1%2C%20_2%2C%20_3%29%20%7B%0A%20%20var%20result%20%3D%20%22t%22%20%2B%20_2%20%2B%20%22r%22%20%2B%20_1%20%2B%20_3%3B%0A%20%20return%20result%3B%0A%7D%0Aconst%20return_val_1%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val_1%20%3D%3D%3D%20\'turtle\'%2C%20%225%3A%20return_val_1%20%3D%3D%3D%20%22%20%2B%20return_val_1%29%3B%0A%0Aconst%20return_val_2%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val_2%20%3D%3D%3D%20\'turtle\'%2C%20%225%3A%20return_val_2%20%3D%3D%3D%20%22%20%2B%20return_val_2%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
{  // 4

};
```

### 5

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20turtle%28_1%2C%20_2%2C%20_3%29%20%7B%0A%20%20var%20result%20%3D%20_1%20%2B%20_2%20%2B%20_3%3B%0A%20%20return%20result%3B%0A%7D%0Aconst%20return_val_1%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val_1%20%3D%3D%3D%20\'turtle\'%2C%20%226%3A%20return_val_1%20%3D%3D%3D%20%22%20%2B%20return_val_1%29%3B%0A%0Aconst%20return_val_2%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val_2%20%3D%3D%3D%20\'turtle\'%2C%20%226%3A%20return_val_2%20%3D%3D%3D%20%22%20%2B%20return_val_2%29%3B%0A%0Aconst%20return_val_3%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val_3%20%3D%3D%3D%20\'turtle\'%2C%20%226%3A%20return_val_3%20%3D%3D%3D%20%22%20%2B%20return_val_3%29%3B%0A%0Aconst%20return_val_4%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val_4%20%3D%3D%3D%20\'turtle\'%2C%20%226%3A%20return_val_4%20%3D%3D%3D%20%22%20%2B%20return_val_4%29%3B%0A%0Aconst%20return_val_5%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val_5%20%3D%3D%3D%20\'turtle\'%2C%20%226%3A%20return_val_5%20%3D%3D%3D%20%22%20%2B%20return_val_5%29%3B%0A%0Aconst%20return_val_6%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val_6%20%3D%3D%3D%20\'turtle\'%2C%20%226%3A%20return_val_6%20%3D%3D%3D%20%22%20%2B%20return_val_6%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
{  // 5

};
```

### 6

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20turtle%28_1%2C%20_2%2C%20_3%2C%20_4%2C%20_5%29%20%7B%0A%20%20var%20result%20%3D%20_4%20%2B%20_2%20%2B%20_5%20%2B%20_4%20%2B%20_1%20%2B%20_3%3B%0A%20%20return%20result%3B%0A%7D%0Aconst%20return_val%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val%20%3D%3D%3D%20\'turtle\'%2C%20%227%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
{ // 6

};
```

### 7

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20turtle%28_1%2C%20_2%2C%20_3%2C%20_4%2C%20_5%29%20%7B%0A%20%20var%20result%20%3D%20_2%20%2B%20_1%20%2B%20_4%20%2B%20_2%20%2B%20%22l%22%20%2B%20_3%3B%0A%20%20return%20result%3B%0A%7D%0Aconst%20return_val%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val%20%3D%3D%3D%20\'turtle\'%2C%20%227%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
{ // 7

```

### 8 

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20turtle%28_1%2C%20_2%2C%20_3%2C%20_4%2C%20_5%29%20%7B%0A%20%20_4%20%3D%20_2%3B%0A%20%20_1%20%3D%20_3%3B%0A%20%20var%20result%20%3D%20_4%20%2B%20%22u%22%20%2B%20_1%20%2B%20_4%20%2B%20_5%20%2B%20%22e%22%3B%0A%20%20return%20result%3B%0A%7D%0Aconst%20return_val%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val%20%3D%3D%3D%20\'turtle\'%2C%20%229%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
{ // 8

};
```

### 9

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20turtle%28_1%2C%20_2%2C%20_3%2C%20_4%2C%20_5%29%20%7B%0A%20%20var%20_%20%3D%20_4%3B%0A%20%20_4%20%3D%20_2%3B%0A%20%20_1%20%3D%20_3%3B%0A%20%20_3%20%3D%20_%3B%0A%20%20var%20result%20%3D%20_4%20%2B%20%22u%22%20%2B%20_1%20%2B%20_4%20%2B%20_3%20%2B%20%22e%22%3B%0A%20%20return%20result%3B%0A%7D%0Aconst%20return_val%20%3D%20turtle%28%2F*%20write%20some%20arguments%20*%2F%29%3B%0Aconsole.assert%28return_val%20%3D%3D%3D%20\'turtle\'%2C%20%229%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
{ // 9

};
```

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
