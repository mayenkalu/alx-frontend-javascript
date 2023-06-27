# ECMAScript

Lets talk about ES6

## What ES6 is?

ES6 (ECMAScript 2015) is the sixth major version of the ECMAScript language specification, which is the standardized scripting language for web browsers. It introduced significant enhancements and new features to JavaScript, making it more powerful and expressive.

## New features introduced in ES6

ES6 introduced several new features, including:

- Arrow functions
- Template literals (string templating)
- Destructuring assignment
- Default function parameters
- Rest and spread operators
- Modules
- Classes and inheritance
- Promises
- Iterators and generators
- Symbol data type
- Enhanced object literals, and more.

## The difference between a constant and a variable

In JavaScript, a variable is a named storage location that can hold a value, and its value can change during the program's execution. On the other hand, a `constant` is a variable that cannot be reassigned after its initial value is set. It remains fixed throughout the program.

## Block-scoped variables

ES6 introduced block-scoped variables using the `let` and `const` keywords. Unlike variables declared with `var`, block-scoped variables are only accessible within the block (enclosed by curly braces) where they are defined. This helps in avoiding unintended variable hoisting and scope-related issues.

## Arrow functions and function parameters default to them

Arrow functions are a concise syntax introduced in ES6 for writing functions. They have a shorter syntax and lexical `this` binding. Additionally, ES6 introduced the ability to set default values for function parameters. This allows parameters to have a default value if no argument is provided when the function is called.

## Rest and spread function parameters

ES6 introduced the rest parameter (...) and the spread operator (...) for function parameters. The rest parameter allows a function to accept any number of arguments as an array. The spread operator allows an array or iterable to be expanded into individual elements when used as function arguments or array literals.

## String templating in ES6

ES6 introduced template literals, which are enclosed by backticks (`/`) instead of single or double quotes. Template literals allow embedding expressions and variables directly within the string using the `${}` syntax. This provides a more readable and flexible way to concatenate strings.

## Object creation and their properties in ES6

ES6 introduced enhanced object literals, providing a shorter syntax for creating objects. It allows defining properties and methods more conveniently, using concise property names, computed property names, shorthand methods, and more.

## Iterators and `for-of` loops

ES6 introduced the concept of iterators and the `for-of` loop. An iterator is an object that provides a sequence of values, one at a time, using the `next()` method. The `for-of` loop allows iterating over iterable objects, such as arrays or strings, in a simpler and more readable way.
