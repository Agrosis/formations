Formations [![Build Status](https://travis-ci.org/Agrosis/formations.svg?branch=master)](https://travis-ci.org/Agrosis/formations)
=============================
A simple and complete server-side and client-side validations library in ES6 JavaScript.

Influence
-----------------------------
Play Framework 2.x.x allows easily defined and testable form validations.

Features
-----------------------------
+ Easily transformable constraints i.e. `number.min(10).max(56)` or `text.matches("[A-Za-z]")`
+ Makes no assumption of client/server
+ Validates JSON forms
+ `"true"` and `true` will both validate as booleans (same with other validation types)
+ Validate on your own "types" by writing `text` constraints

Usage
-----------------------------
You can validate on `number`, `float`, `boolean`, and `text`. If there is a validation type we don't have, just write a `string` validation for it with the appropriate tests.



Contributing
-----------------------------
Open pull requests and issues whenever needed!
