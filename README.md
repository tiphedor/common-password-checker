Original work by [__meehow__ ](https://github.com/meehow)at [meehow/common-password](https://github.com/meehow/common-password) ; foked to update the password list.

[![npm version](https://badge.fury.io/js/common-password-checker.svg)](https://badge.fury.io/js/common-password-checker)

**This list is not perfect!** It contains a _lot_ of simple, crappy passwords, but obviously not all of them. You should still use another form of password strengh evaluation, and consider this lib as a fist pass in a password validation process.

**Fell free to open a PR adding more passwords to the list** ❤️

# Installation

````bash
yarn add common-password-checker
# or
npm i --save common-password-checker
````

# Usage

````javascript
const commonPassword = require('common-password-checker')

commonPassword('password') // returns true
commonPassword('21da25b9602747af9a4b7d3d143aae91') // returns false
````
