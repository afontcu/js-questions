
# JS questions for interviews

Here i collected several JS questions that could be used during a job interview. Also as a tool to learn new stuff.

I think questions are a well balanced list of JS implementation details and general, broader topics.


---

> ### Could you explain what a callback function is? Could you provide a simple example?


---

> ### What does “use strict” do?


---

> ### What are the similarities and differences between Null and Undefined in JS?


---

> ### How would you write a function that allows you to achieve the following snippet?

```js
var addSix = createBase(6)
addSix(10)  // returns 16
addSix(21)  // returns 27
```


---

> ### What is event bubbling? How may you prevent it?


---

> ### What is `let` keyword in JavaScript? How is it different from other similar keywords?


---

> ### How would you check if a number is an integer?


---

> ### What is an IIFE (Immediately Invoked Function Expressions)?


---

> ### How would you compare two objects in JavaScript?


---

> ### Could you explain the main differences between ES5 and ES6?


---

> ### Explain the difference between “undefined” and “not defined” in JS


---

> ### What is the difference between anonymous and named functions?


---

> ### What is a “closure” in JS? Could you provide an example?


---


> ### Explain the Prototype Inheritance in JavaScript


---

> ### Create a function that checks if a number consists only of even digits

```js
evenDigitsOnly(5200)   // false
evenDigitsOnly(4)      // true
evenDigitsOnly(13)     // false
evenDigitsOnly(22410)  // true
```

---

> ### What does “transpiling” mean?


---

> ### What is the output of the following code?

```js
var o = {
  n: 42,
  getN: () => n,
  getValue: function () {
    return this.n
  }
}

console.log(o.n)
console.log(o.getN)
console.log(o.getValue)
console.log(o.n())
console.log(o.getN())
console.log(o.getValue())
```


---

> ### How would you make the following snippet work?

```js
var arr = [1, 2, 3, 4, 5]
var avg = arr.average()
console.log(avg) // => 3
```

---

> ### What is Hoisting in JS? What benefits it gives?


---

> ### Can you name two programming paradigms important for JavaScript developers?


---

> ### JavaScript does not implement the concept of “private” variables. How would you achieve a similar behavior?


---

> ### What’s the output of the following code snippet? Why?

```js
var x = 1

function foo() {
  console.log('x is:', x)
  var x = 2
  console.log('x is:', x)
}

foo()
```


---

> ### What’s the output of the following snippet? 

```js
console.log(c())
console.log(b())
console.log(a())

var a = function() { return 'a' }
var b = () => 'b'
function c() { return 'c' }
```


---

> ### Could you explain Coercion in JS? Use some examples.


---

> ### Could you explain Scoping in JS? Use some examples.


---

> ### What’s the output of the following code snippet? Why?

```js
['1', '2', '3'].map(parseInt)
```


---

> ### Regarding last question: How would you achieve the expected output of `[1, 2, 3]`?


---

> ### What’s the output of the following code snippet? Why?

```js
var a = 1

function b () { 
  a = 10; 
  return; 
  function a() {} 
}

b()
console.log(a)
```


---

> ### What’s the output of the following code? Why? 

```js
const arr = [1, 2, 3, 4]

for (var i = 0; i < arr.length; i++) {
  setTimeout(function() {
    console.log(arr[i])
  }, 1000)
}
```

---

> ### How would you modify the last question to output numbers from 1 to 4, without removing the for loop? Provide at least two examples


---

> ### What is functional programming? What are its pros and cons vs object-oriented programming?


---

> ### What are two-way data binding and one-way data flow, and how are they different?


---

> ### What are the main issues modern JS frameworks (React, Vue, Angular) solve?


---

> ### How would you select all H1 and H2 from a page, and log their content to the console?


---

> ### What are the differences between `Array.prototype.map` and `Array.prototype.reduce`?


---

> ### Is JS a render-blocking or non render-blocking resource? How would you achieve the opposite behavior?


---

> ### What’s the difference between the following code snippets? When should I use one or another?

```js
// 1
var func() {...}
module.exports = func

// 2
var func() {...}
export default func
```


---

> ### Name at least one feature from another programming language that you’d like to see ported to JavaScript


---

> ### How would you assert that a function is working properly, without the aid of a testing library?


---

> ### How would you achieve the following output?

```js
foo.bar === foo.bar  // false
```

---

> ### Write a function `f()` that works in the following scenarios:

```js
f(2, 3)  // 8
f(2)(3)  // 8

var g = f(3)
g(2)  // 9
```

---

> ### How would you define a "pure function"? Can you write some example of pure and impure functions?

---

> ### How would you capture each click on a page, and log a message to the console?

---

> ### What is the difference between the Load event and the DOMContentLoaded event?

---

> ### How could you verify whether one DOM element is child of another?

---
