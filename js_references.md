Certainly! Here's the JavaScript cheat sheet formatted as a table for easy export:

| Concept | Description | Example |
| ------- | ----------- | ------- |
| **Variables** | | |
| `var` | Function-scoped or globally-scoped variable, can be re-declared and updated. | `var a = 5;` |
| `let` | Block-scoped variable, can be updated but not re-declared in the same scope. | `let b = 10;` |
| `const` | Block-scoped, cannot be updated or re-declared. | `const PI = 3.14;` |
| **Data Types** | Primitive: Undefined, Null, Boolean, Number, String, Symbol (ES6), BigInt (ES2020). Non-primitive: Object. | |
| **Functions** | | |
| Function Declaration | Named function, hoisted. | `function greet(name) { return \`Hello, ${name}!\`; }` |
| Function Expression | Anonymous function assigned to a variable, not hoisted. | `const greet = function(name) { return \`Hello, ${name}!\`; };` |
| Arrow Function (ES6) | Shorter syntax, does not have its own `this`, not hoisted. | `const greet = (name) => \`Hello, ${name}!\`;` |
| **Arrow Functions vs Traditional Functions** | Arrow functions have a shorter syntax, don't have their own `this`, and are suited for non-method functions. Traditional functions are better for object methods. | |
| **Objects** | | `const person = { name: "Alice", age: 25, greet: function() { return \`Hello, ${this.name}!\`; } };` |
| **Arrays** | | `let fruits = ["apple", "banana", "cherry"];` |
| **Control Structures** | | |
| If-Else | Conditional execution based on a boolean condition. | `if (condition) { /* code */ } else { /* code */ }` |
| Switch | Select one of many code blocks to be executed. | `switch(expression) { case x: /* code */ break; default: /* code */ }` |
| For Loop | Loop with a counter, run for a specified number of times. | `for (let i = 0; i < 5; i++) { console.log(i); }` |
| While Loop | Loop as long as a condition is true. | `let i = 0; while (i < 5) { console.log(i); i++; }` |
| For Let | a for loop where the loop variable is declared using the let keyword. The let keyword provides block scope for the loop variable, which is often desirable for various reasons, including avoiding unintended side effects and errors.| `for (let i = 0; i < someCondition; i++) {
    // Loop body
}
`|
| **Error Handling** | | |
| Try-Catch | Handle exceptions safely. | `try { /* code */ } catch (error) { /* code */ }` |
| **ES6 Features** | | |
| Template Literals | String literals allowing embedded expressions. | ``let greeting = `Hello, ${name}!`;`` |
| Destructuring | Unpack values from arrays, or properties from objects. | `const {name, age} = person;` |
| Spread Operator | Expand an iterable (array, string) into individual elements. | `let newArray = [...fruits, "mango"];` |
| Default Parameters | Set default values for function parameters. | `function greet(name = "Guest") { return \`Hello, ${name}!\`; }` |
| Import/Export Modules | Modularize JavaScript code by exporting and importing parts of it. | `export const add = (a, b) => a + b; import

