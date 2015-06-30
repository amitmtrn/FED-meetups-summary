# You gotta love frontend
## Lea Verou - The missing piece

Pie charts challenge

good CSS solution
* flexibility
  * possible to change
  * dry code
* extensibility
  * can I have multiple segments?
  * possible (but painful) to animate
  * some effect possible
* maintainability
  * how much code?
  * extra elements?
  * straightforward?

### static interpolation

```css
div {
  background: #f06;
  animation: 100s color forword;
  animation-play-state: paused;
}

@keyframes color {
  to {background: gold;}
}

.p25 {
  animation-delay: -25s;
}
```

### Conic gradient

### How good is a pie chart?
Eduard thuffe


Keyword
* Turn units
* currentColor property
* animate step-end
* inherit from parent

## Benjamin Gruenbaum - io.js and the future of server side js

Implementation of es6 in io.js

Open Governance

### how to help the community
* pull request
* writing documentation
* opening issues
* feature request
* stack overflow, gitter, chats
* try the beta branch

### how to start contribute
* babel - Call for contributors!

keyword
* specification


## Matthieu Mayran Catching fire base
mayran@google.com

### Fire base approch
manage everything on the client and sync it with the server (both ways) using websoket.

* Real time database
* User management
* Hosting

### steps to install firebase
* open an account firebase
* download client library
* setup authentication

## Alexander Kotliarskyi - React Native under the hood

* runtime
* base components
* call native object

core function in react
* create
* update
* delete

The bridge
* native
  * evebt
  * collect data
* bridge
  * serualized payload
* javascript
  * process event
  * call native app

keyword
* fatch js
* massage queue

## Alex wolkov
give developers the opportunity to make side project

### chat ops
Deploy from inside your chat

### interfaces
* 10 feet rule (make sure that the dashboard visiable from 10 feet)
* don't reinvent the wheel
* design for TV size

### extend the web
chrome extension

keyword
* dashboard
  * dasing.io
  * bless-contrib
  * sidlee
* hu-bots


## Or hiltch - binary data adventures in browser

bitwise operators

* type system
  * blob
  * arraybuffer
  * typedarry
* inputs
  * XHR
  * file API
  * canvas
  * websockets
  * webrtc
* output
  * canvas
  * MSE
  * websocket
  * webgl


typed array
* native interfaces
* endianness
* dataview adopter

streaming video with js
* MSE
* arraybuffer
* video source extension


### asm.js
a subset of js for handling number faster
* MEM8 - asm js heap

### webgl
* vertex shader
* defragment shader
* webgl inspector

## Yigal steklov - leanding your dream job as a FED

share knowledge
* codepen
* github

## Eran Zinman - Boom preference

be optimistic - assume that the request succeed.

* typeahead.js
* lunr.js
* ladda.js

### perceived performance

### gradual rendering
