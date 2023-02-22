# Variables & Constants in JavaScript

In JavaScript, variables and constants are used to store and manipulate data. They are declared using the keywords `var`, `let`, `const`.

## Variables

A variable is a container that holds a value. The value can be changed at any time during the runtime of the program.

### Declaring variables

```js
// using var
var age = 20;

// using let
let name = "John";

// using var without initializing it
var x;

```

### Naming variables

- Variable names can contain letters, digits, underscores, and dollar signs.
- The first character must be a letter, underscore, or dollar sign.
- Variable names are case sensitive.
- Avoid using reserved keywords such as `if`, `else`, `while`, `break`, etc.

### Assigning values to variables

```js
// assigning a value to a variable
var x = 10;

// updating the value of a variable
x = 20;

```

## Constants

A constant is a container that holds a value that cannot be changed during the runtime of the program.

### Declaring constants

```js
// using const
const PI = 3.14;

// using uppercase letters for constants
const MAX_VALUE = 100;

```

### Naming constants

- Constant names should be in uppercase letters.
- Use underscores to separate words in the constant name.

### Assigning values to constants

```js
// assigning a value to a constant
const PI = 3.14;

// trying to update the value of a constant throws an error
PI = 3.14159; // throws an error

```

## Conclusion

Variables and constants are used to store and manipulate data in JavaScript. Variables can hold values that **can be changed** during the runtime of the program, while constants hold values that **cannot be changed**. It's important to follow the naming conventions and use the appropriate keywords when declaring and assigning values to variables and constants.
