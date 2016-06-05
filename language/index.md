---
lang: en
layout: default
title: Language Features
---

# Language Features

ECMAScript 2015 introduces a lot of new syntactical language features which are
mostly for convinience. These new features are all designed to be backwards
compatible in that they can be rewritten to have the same functionality in
ECMAScript 5.

While your favorite runtime might support these features nativly it's worth
considering using a compiler to compile it down to ECMAScript 5 for
compatability.

The most popular compiler to date is [Babel](https://babeljs.io) which aims to
be accurate to the specification. There are alternatives that cut some corners
for the sake of simplicity, for example [Bublé](https://buble.surge.sh) which
produces more optimized code and the output looks more like something one would
write by hand.
