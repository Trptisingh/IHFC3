# 🔒 JavaScript `const` Declaration Example

This example demonstrates how to **declare constants using `const`** in JavaScript and view the output in the browser console.

---

## 🧠 What is `const`?

The **`const`** keyword is used to declare **constants** — variables whose values **cannot be changed or reassigned** once defined.  
It was introduced in **ES6 (ECMAScript 2015)**.

Example:
```javascript
const country = "India";
console.log(country);
📂 Files in This Example
index.html → A simple webpage linking the JavaScript file.

script.js → JavaScript file showing const in action.

⚙️ How to Run the Example
Save both files (index.html and script.js) in the same folder.

Open index.html in a web browser.

Right-click → Inspect → Console tab to view the output.

Expected output:

pgsql
Copy code
Country: India
Capital: New Delhi
Error: You cannot reassign a 'const' variable.
📘 Key Points About const
Feature	Description
Scope	Block-scoped (like let)
Reassignment	❌ Cannot be reassigned after initialization
Redeclaration	❌ Cannot be redeclared in the same scope
Initialization	✅ Must be initialized at the time of declaration
Hoisting	Variables are hoisted but not initialized (Temporal Dead Zone applies)

✅ Example Recap: