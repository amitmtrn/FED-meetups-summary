# GDG Rashlatz - react

## An Introduction to ReactJS - Dan Shappir

* react is **only** the view of the MVC
* work with flux

### Re-render everything on every up update
* no data binding
* no observers
* no model dirty chacking
* no state mutations

* **make things easy to reason about**
* **simple api**

### Virtual DOM
* emulate real DOM using javascript object
  * fast and lightweight
* Regenerate on every change
* Diff with previous virtual DOM
* compoute minimal set of changes
* put changes in a queue
* batch render all changes to real DOM

Example 1:
```js
var root - document.querySelector('div');
React.render(React.createElement('div', null, 'Hello world'), root);
```

### jsx
* embed HTML elements into javascript code
  * no strings
* compiled to javascript
  * dynamically or ahead of time
* accessibility of templates and the power of javascript

```jsx
React.render(<div>Hello world</div>, root);
```

### react components

```jsx
var root = document.getElementById('root');
var HelloWorld = React.createClass({
  render: function () {
    return <div>Hello World</div>;
  }
});

React.render(<HelloWorld></HelloWorld>, root);
```

passing argument to components
* using HTML attirbure syntax
* accessed using this.props
* immutable

```jsx
var Hello = React.createClass({
  getDefaultProps: function () {
    return {name: 'world'};
  },
  render: function () {
    var name = this.props.name;
    return <div>Hello <b>{name}</b></div>;
  }
});

React.render(<Hello></Hello>, root);
```

* using {} for defining javascript in the html

### state
```jsx
getInitialState: function () {
  return {acending: true};
}
```

## Brining ReactJS into AngularJS. Flux, immutable and performance - Boris Dinkevich

### using react with AngularJS

> The basic is to create directive in angular that create react component

### keywords:
* ngReact
* ngRepeat - trackby
* react-templates

## Reasoning about code: how to save your soul with React - Juan Lulkin
* patterns over frameworks
* concepts over implementations
* skill over tools

Things we need to understand
* DOM mutation
