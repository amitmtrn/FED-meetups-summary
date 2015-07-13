# JavaScript: The Ugly Duckling - [event](http://www.meetup.com/FrontEnd-IL/events/221414467/)

## Practical Functional JavaScript, by Ben Katz (Wix)

### FP good for
* stateless
* algorithms
* data analysis and transformation
* handling stream of events

(jone carmeck at quakecon 2013)[]

### concepts
* immutability - objects don't change state
* first class function - function can be passed around like regular variable
  * higher order function - function that return function
  * partial application
  ```
  var add = (a,b) => a + b;
  var inc = add.bind(undefined, 1);
  ```
  * curry
  * higher order function solution is actually pretty cool with arrow functions
  ```
  var add = a => (b => a + b);
  ```

### what do we expect from out functions?
* stateless
* no side effects
* for every x, f(x) will always be the same

### what's the point?
* fore every x,f(x ) will always be the same
* allows optimizations
  * remove unused call
  * memorization
  * parallelization

### pattern matching (es2015)
* reverse

### tail call optimization

### lazy evaluation
* what happens when you need to work with huge collections?
* `function*(){}` function generator
* liberaries - lazy.js, lowdash.js, wu.js

### function chaining is not functional programing
* the concept of functional programming is not that you start with object but with functions
* function that work on this are stateful
* ramda.js

### functional reactive programing

* everything is a stream
* rx.js, bacon.js - allow you to work with events
* let's see an example of stream manipulation
  * we will take a click stream and create a stream of double (or more) clicks only.

### functors

## Bringing Synchronous Semantics to Asynchronous JavaScript, by Dima Abramchaev (Sela)
