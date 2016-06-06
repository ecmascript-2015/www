---
lang: en
layout: default
title: >
  Arrow Function Example: Expression
---

# Arrow Functions Example: Expressions

Arrow functions can be expressed as expressions without a function body,
previously we would have to let even the simplest transformation functions span
over several lines.

```javascript
var numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9];
var values = numbers.map(function(n) {
  return n * n;
}));
```

This can now be rewritten into actual one liners.

```javascript
let numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9];
let values = numbers.map(n => n * n);
```
