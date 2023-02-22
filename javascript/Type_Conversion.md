# Type Conversion in JavaScript

Type conversion, also known as typecasting, is the process of converting a value from one data type to another.

In this document, we will explore the different types of type conversions in JavaScript.

## Implicit Type Conversion

Implicit type conversion, also known as **type coercion**, is an **automatic** conversion that happens when an operator is applied to values of different data types.

JavaScript automatically converts one of the values to a common data type to perform the operation. For example:

```js
var num = 10;
var str = "20";
console.log(num + str); // Output: "1020"

```

In the above example, JavaScript converts the `num` variable to a string type and concatenates it with the `str` variable.

## Explicit Type Conversion

Explicit type conversion, also known as **type casting**, is a **manual** conversion that converts a value from one data type to another. JavaScript provides several methods for explicit type conversion, including:

### 1. Number()

The `Number()` method converts a value to a number data type. If the value cannot be converted to a number, it returns NaN (Not a Number). For example:

```js
var str = "10";
console.log(Number(str)); // Output: 10

```

### 2. String()

The `String()` method converts a value to a string data type. For example:

```js
var num = 10;
console.log(String(num)); // Output: "10"

```

### 3. Boolean()

The `Boolean()` method converts a value to a boolean data type. The following values are converted to false:

- false
- 0
- "" (empty string)
- NaN
- null
- undefined

All other values are converted to true. For example:

```js
var num = 0;
console.log(Boolean(num)); // Output: false

```

## Conclusion

Type conversion is an essential concept in JavaScript that allows developers to manipulate data effectively.
