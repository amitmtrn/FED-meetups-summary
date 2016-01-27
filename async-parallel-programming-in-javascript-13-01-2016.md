# Async & Parallel Programming in JavaScript - eyal vardi
## rx - reactive extensions

* creating pipe one time (observable pattern) and send the events through the pipe

```js
function action() {
  return http.get('/someUrl')
        .map(res => res.json.something());
}

action()
      .subscribe(onSuccess, onFail, onSomething);

```

[rxplayground](jaredforsyth.com/rxvision/examples/playground/)


### Comments:
* split - is sync function that create a lot of string objects
* github plugin - octo tree
* typescript to uml

## webworkers
ui thread + thread

```js
var worker = new Worker('myThread.js');
```

library - operative.js

### angular 2
in the source in github they have `examples` folder and `playground` folder for learning
