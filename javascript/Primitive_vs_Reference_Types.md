# Primitive vs Reference Types

In JavaScript, there are two main data types: primitive types and reference types.

## Primitive Types

Primitive types are simple data types that are immutable, which means their value cannot be changed once they are created. There are six primitive types in JavaScript:

1. **Number**: represents numeric values.
2. **String**: represents a sequence of characters.
3. **Boolean**: represents a logical entity and can have two values, true or false.
4. **Undefined**: represents a variable that has been declared but has not been assigned a value.
5. **Null**: represents a deliberate non-value.
6. **Symbol**: represents a unique identifier.

When we create a variable and assign a primitive value to it, the variable contains the actual value of the primitive type. This value is stored in the stack memory of the computer.

An example of a primitive type in JavaScript is a string. If we create a variable and assign a string to it, the variable will contain the actual value of the string. For example:

```js
let myString = "Hello World";

```

In this case, the variable `myString` contains the string "Hello World". Since strings are a primitive type, their value is stored in the stack memory of the computer.

## Reference Types

Reference types are more complex data types that are mutable, which means their value can be changed after they are created. There are three main reference types in JavaScript:

1. **Object**: represents a collection of properties.
2. **Array**: represents a collection of values.
3. **Function**: represents a reusable set of statements.

When we create a variable and assign a reference value to it, the variable actually contains a reference to the value, not the value itself. The **reference is stored in the stack memory** of the computer, but the **value it points to is stored in the heap memory**.

An example of a reference value in JavaScript is an object. If we create an object and assign it to a variable, the variable actually contains a **reference to the object**, not the object itself. For example:

```js
let myObject = {
  name: "John",
  age: 30
};

```

In this case, the variable `myObject` contains a reference to the object `{ name: "John", age: 30 }`. The reference to the object is stored in the stack memory, while the object itself is stored in the heap memory.

## Stack and Heap Memory

Stack and heap memory are two regions of memory used by programs. Stack memory is used for static memory allocation, while heap memory is used for dynamic memory allocation.

In the case of primitive types, their values are stored in the stack memory, which is faster to access than heap memory. However, in the case of reference types, the reference to the value is stored in the stack memory, while the actual value is stored in the heap memory. This is because reference types can have varying sizes and can be dynamically allocated at runtime.

![https://imgs.search.brave.com/hdhYgmF93eORbQ2L99Np29ASBLgE6qVJWD9jR99Ncrw/rs:fit:451:231:1/g:ce/aHR0cHM6Ly93d3cu/amF2YXNjcmlwdHR1/dG9yaWFsLm5ldC93/cC1jb250ZW50L3Vw/bG9hZHMvMjAyMi8w/MS9KYXZhU2NyaXB0/LWhlYXAtbWVtb3J5/LnN2Zw.svg](https://imgs.search.brave.com/hdhYgmF93eORbQ2L99Np29ASBLgE6qVJWD9jR99Ncrw/rs:fit:451:231:1/g:ce/aHR0cHM6Ly93d3cu/amF2YXNjcmlwdHR1/dG9yaWFsLm5ldC93/cC1jb250ZW50L3Vw/bG9hZHMvMjAyMi8w/MS9KYXZhU2NyaXB0/LWhlYXAtbWVtb3J5/LnN2Zw.svg)

As you can see in the image above, the stack memory is used to store primitive values, reference variables, and function calls. The heap memory is used to store complex data structures like objects and arrays.

In conclusion, understanding the differences between primitive types and reference types in JavaScript is crucial for writing efficient and effective code. By knowing where and how these types are stored in memory, you can optimize your code and avoid common pitfalls.
