# Operators in JavaScript

JavaScript provides various operators that are used to perform different operations on values, variables, and literals. These operators can be classified into different categories such as arithmetic operators, logical operators, bitwise operators, and many more.

In this document, we will explore **arithmetic** and **logical** operators in JavaScript with examples.

## Arithmetic Operators

Arithmetic operators are used to perform mathematical operations on numerical values. The following table shows the arithmetic operators in JavaScript:

| Operator | Description |
| --- | --- |
| + | Addition |
| - | Subtraction |
| * | Multiplication |
| / | Division |
| % | Modulus |
| ++ | Increment |
| -- | Decrement |

Here are some examples of using arithmetic operators in JavaScript:

```jsx
let x = 10; // this is assigning value so it is an Assignment operator
let y = 5;

console.log(x + y); // Output: 15
console.log(x - y); // Output: 5
console.log(x * y); // Output: 50
console.log(x / y); // Output: 2
console.log(x % y); // Output: 0
console.log(++x);   // Output: 11
console.log(--y);   // Output: 4

// x = x + 1 is same as x++ and it is an increment operator
// x = x - 1 is same as x-- and it is an decrement operator
```

JavaScript also allows for **string concatenation** using the `+` operator.

When used with strings, the `+` operator concatenates the strings together.

Here is an example:

```jsx
let firstName = "John";
let lastName = "Doe";

console.log(firstName + " " + lastName); // Output: "John Doe"

```

In addition to the arithmetic and logical operators discussed earlier, the `+` operator can be used to concatenate strings in JavaScript.

In JavaScript, the `**` operator can be used to perform exponentiation, which means raising a number to a power.

Here is an example:

```jsx
let x = 2;
let y = 3;

console.log(x ** y); // Output: 8

```

In this example, `x ** y` raises `x` to the power of `y`, which is 2 to the power of 3. The output is 8.

## Logical Operators

Logical operators are used to perform logical operations on values that can be either true or false. The following table shows the logical operators in JavaScript:

| Operator | Description |
| --- | --- |
| && | Logical AND |
| || | Logical OR |
| ! | Logical NOT |

Here are some examples of using logical operators in JavaScript:

```jsx
let x = 10;
let y = 5;

console.log(x > y && y < x);  // Output: true
console.log(x < y || y > x);  // Output: false
console.log(!(x == y));      // Output: true

```

## Conclusion

These operators are essential in performing **mathematical** and **logical** operations in JavaScript. It is important to understand these operators and how to use them effectively in your code.
