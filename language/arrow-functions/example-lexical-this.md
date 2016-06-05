---
lang: en
layout: default
title: >
  Arrow Function Example: Function Body
---

# Arrow Functions Example: Lexical This 

Arrow functions use the same lexical scope as their enclosing function body,
which means in cases you previously had to capture and store the value of
`this`.

```javascript
function Greeter(greeting) {
  this.greeting = greeting;

  var self = this;
  setTimeout(function() {
    console.log(self.greeting);
  });
}
```
{: title=legacy }

Can be rewritten and made simpler with the use of arrow functions.

```javascript
function Greeter() {
  this.greeting = greeting;

  setTimeout(() => {
    console.log(this.greeting);
  });
}
```
{: title=modern }
