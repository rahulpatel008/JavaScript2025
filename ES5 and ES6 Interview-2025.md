
## ES5 and ES6 Interview Questions and Answers



1. What is the difference between var, let, and const?

- var: Function-scoped or globally-scoped. Can be re-declared and updated.
- let: Block-scoped. Cannot be re-declared within the same scope but can be updated.
- const: Block-scoped. Cannot be re-declared or updated, but the contents of objects/arrays can be modified.

2. How do ES6 arrow functions differ from ES5 functions?
- Arrow functions provide a shorter syntax and lexically bind the this value, meaning they inherit this from the parent scope.

3. What are template literals in ES6 and how do they work?
- Template literals are enclosed by backticks (`) and allow for embedded expressions using ${expression}. They support multi-line strings and string interpolation.

4. Explain destructuring assignment in ES6.
- Destructuring assignment allows for extracting values from arrays or objects into distinct variables. Example:
const [a, b] = [1, 2];
const {name, age} = {name: "John", age: 25};

5. What is the spread operator and how is it used in ES6?
-The spread operator (...) is used to expand an array or object. It can be used to copy arrays, concatenate arrays, or spread elements into a new array/object.

6. How do default parameters work in ES6?
- Default parameters allow parameters to have a default value if no value is provided. Example:
function add(a = 5, b = 10) {
  return a + b;
}

7. What are let and const best practices in ES6?
- Use const by default unless the variable needs to be reassigned, in which case use let. Avoid var to prevent scope-related issues.

8. How does the ES6 for...of loop differ from the ES5 for...in loop?
- for...of iterates over iterable objects like arrays and returns values of each property. for...in iterates over the keys of an object.

9. What are Promises in ES6 and how do they work?
- Promises represent asynchronous operations, providing then, catch, and finally methods to handle resolved or rejected states.

10. Describe how ES6 modules work compared to ES5 module patterns.
- ES6 modules use import and export keywords for module functionality, allowing for easier and more efficient code organization compared to ES5 module patterns like IIFE or CommonJS.

11. What is the purpose of the ES6 Map and Set objects?
- Map is a collection of key-value pairs where keys can be any type. Set is a collection of unique values. Both provide useful methods for managing data.

12. Explain how classes work in ES6.
- ES6 classes are syntactical sugar over JavaScript's prototype-based inheritance. They provide a clearer and more concise syntax for creating constructor functions and dealing with inheritance.

13. How does ES6 handle asynchronous operations with async and await?
- async functions return a Promise. await pauses the function execution until the Promise is resolved, making asynchronous code easier to read and write.

14. What are generators in ES6 and how do they function?
- Generators are functions that can be paused and resumed, using the function* syntax and yield keyword. They are useful for managing asynchronous operations or creating iterators.

15. Can you explain the concept of Symbol in ES6?
- Symbols are unique and immutable primitives used to create unique property keys, preventing property name conflicts in objects.