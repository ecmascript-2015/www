---
lang: en
layout: default
title: Block Bindings
---

# Block Bindings

ECMAScript 6 provides us with new variable bindings that are scoped to a block
level through the `const` and `let` keywords.

The key differences between variables declared with these and `var` are:

No hoisting
: Variables declared with `const` and `let` live are bound to the block they
  are declared within, and will not be hoisted to the top of the
  function scope like variables declared with `var` would.

## Examples

- [Arrow Function Example: Const](example-const)
