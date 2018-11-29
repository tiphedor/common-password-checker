Original work by [__meehow__ ](https://github.com/meehow)at [meehow/common-password](https://github.com/meehow/common-password) ; foked to update the password list.

[![npm version](https://badge.fury.io/js/common-password-checker.svg)](https://badge.fury.io/js/common-password-checker)

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
