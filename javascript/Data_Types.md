
# Data Types in JavaScript

In JavaScript, there are seven data types that are classified into two categories:

1. **Primitive Data Types**
    - String
    - Number
    - Boolean
    - Null
    - Undefined
    - Symbol (new in ECMAScript 6)
2. **Object Data Types**
    - Object

## Primitive Data Types

### 1. String

A string is a collection of characters that are enclosed within single or double quotes. For example,

```js
let myString = "Hello World";

```

### 2. Number

A number is a numeric value. It can be an integer or a floating-point number. For example,

```js
let myNumber = 10;
let myFloat = 3.14;

```

### 3. Boolean

A boolean value is either true or false. For example,

```js
let myBoolean = true;

```

### 4. Null

Null is a special keyword in JavaScript that represents no value or an empty value. For example,

```js
let myNull = null;

```

### 5. Undefined

Undefined is a special keyword in JavaScript that represents a variable that has not been assigned a value. For example,

```js
let myUndefined;

```

### 6. Symbol

Symbol is a new data type introduced in ECMAScript 6. It is used to create unique identifiers for objects. For example,

```js
let mySymbol = Symbol('mySymbol');

```

## Reference Data Types

Reference data types are also known as object data types. They are called reference data types because they are not stored directly in a variable, but rather they are stored in the heap and accessed by reference.

In JavaScript, there is only one reference data type, which is the `Object`. An object is a collection of properties, where each property is a key-value pair. For example,

```js
let myObject = {
    name: 'John',
    age: 30,
    address: {
        street: '123 Main St.',
        city: 'New York',
        state: 'NY'
    }
};

```

In the example above, `myObject` is an object that has three properties: `name`, `age`, and `address`. The `address` property is also an object that has three properties: `street`, `city`, and `state`.

When you create an object in JavaScript, you are actually creating a reference to that object. For example,

```js
let myObject1 = {
    name: 'John',
    age: 30
};

let myObject2 = myObject1;

```

In the example above, `myObject1` is an object that has two properties: `name` and `age`. When you assign `myObject1` to `myObject2`, you are actually creating a reference to `myObject1`. This means that any changes you make to `myObject2` will also affect `myObject1`.

To access a property of an object, you can use dot notation or bracket notation. For example,

```js
let myObject = {
    name: 'John',
    age: 30
};

console.log(myObject.name); // Output: John
console.log(myObject['age']); // Output: 30

```

In the example above, `myObject.name` and `myObject['age']` both access properties of the `myObject` object.

In JavaScript, arrays and functions are also reference types. When you create an array or a function in JavaScript, you are actually creating a reference to that array or function. This means that any changes you make to the array or function will also affect other variables that reference the same array or function. However, arrays and functions are not considered separate data types in JavaScript; they are still classified as **objects**.

## Typeof Operator

JavaScript provides the `typeof` operator to determine the data type of a variable. For example,

```js
let myString = "Hello World";
console.log(typeof myString); // Output: string

let myNumber = 10;
console.log(typeof myNumber); // Output: number

let myBoolean = true;
console.log(typeof myBoolean); // Output: boolean

let myNull = null;
console.log(typeof myNull); // Output: object

let myUndefined;
console.log(typeof myUndefined); // Output: undefined

let mySymbol = Symbol('mySymbol');
console.log(typeof mySymbol); // Output: symbol

let myObject = {
    name: 'John',
    age: 30
};
console.log(typeof myObject); // Output: object

```

## Conclusion

In JavaScript, data types are used to represent different kinds of data. They are classified into two categories: primitive data types and object data types. JavaScript also provides the `typeof` operator to determine the data type of a variable, and type coercion for automatic conversion of one data type to another data type. Understanding data types is important for writing efficient and bug-free JavaScript code.
