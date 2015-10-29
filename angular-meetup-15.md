# angular meetup 15
http://vmob.me/DE1Q16500Tech

## be ready for angular 2
*yaniv efraim*

### component architecture
* immutable
* well defined public api
* isolated

> need to define the input and the outputs in each component
the component should have:
* interface - definition of inputs and outputs - important for immutability
* template - the design of the component
* logic - the business logic of the component

*bind to controller*

### component tree structure
hierarchical tree with unidirectional data flow
event bubble up and prop drill down

> it's important to remember the single responsibility of each component

*thinking in react*

### es2015 / typescript
Decorator - allow you to add metadata to component

*reactive programing*

https://github.com/yanivefraim/theme-creator-demo-angular-2

## How Angular Can Solve All Your Problems
*Nir Kaufman*

* consider typescript
* solid principles
  * single responsibility - one responsibility one reason to change
  * open / closed - open for extension but closed for modification
  * Liskov substitution - child classes should never break the parent class (inheritance) *recommanded: not to use*
  * interface segregation - many specific interfaces are better than one generic interface
  * dependency inversion - high lever modules should not depend on low lever modules Both should depend on abstractions - create interfaces for each model and directive
