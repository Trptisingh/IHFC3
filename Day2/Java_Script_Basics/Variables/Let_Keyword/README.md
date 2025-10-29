# 💻 JavaScript `let` Declaration Example

This example demonstrates how to **declare variables using `let`** in JavaScript and view the output in the browser console.

---

## 🧠 What is `let`?

`let` is used to **declare block-scoped variables** in JavaScript.  
It was introduced in **ES6 (ECMAScript 2015)** to fix some of the issues with `var`.

Example:
```javascript
let fruit = "Apple";
console.log(fruit);
📂 Files in This Example
index.html → Basic webpage linking the JavaScript file.

script.js → Contains JavaScript code using let.

⚙️ How to Run the Example
Save both files (index.html and script.js) in the same folder.

Open index.html in your web browser.

Right-click → Inspect → Console tab.

You’ll see output like:

mathematica
Copy code
The temperature in Bangalore is 27°C.
Updated temperature: 30°C
📘 Key Points About let
Feature	Description
Scope	Block-scoped (only accessible inside { } where defined).
Redeclaration	❌ Cannot be redeclared in the same scope.
Reassignment	✅ Can be updated with a new value.
Hoisting	Variables are hoisted but not initialized — accessing before declaration causes an error.