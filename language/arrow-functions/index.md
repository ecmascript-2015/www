---
lang: en
layout: default
title: Arrow Functions
---

# Arrow Functions

ECMAScript 2015 provides us with a new form of funtions called arrow functions
which use the "fat arrow" notation `=>`, these functions can only be defined as
function expressions bound to a `let`, `const` or `var` binding.

```javascript
let fn = () => {
  console.log('hello world');
};
```

Besides being fewer keystrokes, this new form of functions behave a little bit
different than regular JavaScript functions in a couple of ways that is
important to know about.

Lexical scope for `this`, `super`, `arguments` and `new.target` bindings.
: Arrow functions share the same lexical scope bindings for `this`,
  `arguments`, `super` and `new.target` variable bindings as the function the
  arrow function is declared within.

## Examples

- [Arrow Function Example: Lexical This](example-lexical-this)
