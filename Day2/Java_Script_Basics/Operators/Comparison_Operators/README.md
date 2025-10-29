# 🔍 JavaScript Comparison Operators

Comparison operators in JavaScript are used to **compare two values** and return a **boolean** (`true` or `false`).

---

## 📂 Files

- **index.html** — Basic webpage linked to an external JavaScript file  
- **script.js** — Contains examples demonstrating all comparison operators  

---

## ⚙️ How to Run

1. Save both files in the same folder.  
2. Open **index.html** in your browser.  
3. Right-click → **Inspect → Console tab** to see the output.

---

## 🧠 What Are Comparison Operators?

They are used to **compare values** in JavaScript.  
The result is either **true** or **false**.

Example:

```javascript
let a = 10;
let b = 20;

console.log(a > b); // false
console.log(a < b); // true
📘 Comparison Operators List
Operator	Description	Example	Result
==	Equal to (checks value only)	10 == "10"	✅ true
===	Strict equal to (checks value + type)	10 === "10"	❌ false
!=	Not equal to (checks value only)	10 != 20	✅ true
!==	Strict not equal to (checks value + type)	10 !== "10"	✅ true
>	Greater than	15 > 10	✅ true
<	Less than	5 < 10	✅ true
>=	Greater than or equal to	10 >= 10	✅ true
<=	Less than or equal to	8 <= 6	❌ false