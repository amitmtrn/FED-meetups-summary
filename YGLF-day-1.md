# You gotta love frontend

## Douglas Crockford - Upgrading the web

Security of the web

> rfc 1738
//user:password@host:port/url-path

what's wrong with the web?
* insecure
* complex

http
* container for key:value pairs
* request/resoponse protocol

DNS - domain name system
* overleap with the trade mark system
* DNS poison

SSL - secure soket layer
* base certi cate authorities

HTML

Temeplating
* venerable to xss

CSS
* layout of technical documents

javascript

### Helper App
if you tired to open a file that the browser didn't know how to open it would suggest a app that will work with the app.

### Transition Plan
* convince one progressive browser maker to itegrate.
* convince one secure site to require its customers to use that browser.
* risk mitigation will compel the other secure sites.
* Competitive pressure will move the other browser makers.
* The world will follow for improved security and faster application development.
* nothing break

**Strong Cryptography**
* ECC 521 - public key as unique identifiers
* AES 256
* SHA 3-256

Zooko Triangle
* Human Meaningful
* Securely Unique
* Global: Decentralized

Douglas method
* replace HTML with secure JSON over TCP
* web: publickey@ipaddress/capability
* trust management - petnames
* vat - container
* Qt??

ES6
* proper tail calls
* ellipsis operator

keyword
* noscipt - available in firefox
* Viperware

## Gil Tayar - A vision of Backend and Frontend

ES6 modules

```js
export function greet (name) {
  return 'hello' + name;
}
```

```js
import {aFunction} from './aModule'
```

keyword:
* HTTP/2 Channel
* HTTP/2 Push Mode
* message queue

## Phil Nash

Web API
* Push Notification
* geo location
* accelerometer

Service worker

`jakearchibald.github.io`


## Shay Chen - Creepy frontend mistakes

access DOM XSS wiki

* History (saving get parameters in order to hack the account)
* auto complete (fields with autocomplete)
* caching on dynamic content
* click jacking + type jacking
* hacking the DOM (xss)
* webSQL injection

Softwares
* Burp Suite

## Efim Dimenstein & Itai Chejanovsky - large scale SPA

Divide & Conquer
* Main App/ Framework
  * Context
  * Common lib
  * Mini App
  * Components
  * Routing
* Mini App

Tech Stack
Select small library that do only one thing

CROS micro services

transporter
* cross Domain
* client only
* XHR behavior
* Bach

Manager (For Mini Apps)
* parent <-> Child
* internal
* Child <-> Child
* Child <-> "Friend"

Take Away
* Define your problem space first
* Be very clear what you are building
* Plan to scale
* Architect & design
* Tooling and technology
* do not believe the hype

## serge krul - Leading a large scale team

Leadership
* Let go
* Let grow

Team
* Boundaries
* Respect
* Empathy
* Confidence
* Support

## Vladimir & Ilana (yandex) - BEM

Naming convention:
> Block__Element_Modifier

Some bem principles
* No css outside a block
* avoid cacede

All the blocks sit in a library (lega)

open source library
* BEM core
* BEM components

## Martin Kleppe - the alef

[aem1k.com]()

If we use id in element we can access to id from the js

```html
<body id=b onload=b.innerHTML=1>
```

```js
with (Math) {

}
```

How special code done
* Escape Sequences
  `a = \u0061` - in Unicode
  `a = \x` - in hex
  `a = \141` - octal

```js
[]["map"]["constructor"]

///

Function()
```
equal to eval()

* scrabble

```js
![] = false
!![] = true
```

Keyword
* game of life algorithm
* if Hemingway write JavaScript
* js1k competition
* 140 bytes project
* shadertoy
