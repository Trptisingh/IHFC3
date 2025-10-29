# 🌐 External JavaScript — Complete Guide

This project demonstrates how to use an **external JavaScript file** in an HTML webpage using the `<script>` tag.

---

## ⚙️ What Is External JavaScript?

Instead of writing JavaScript directly inside the HTML file, you can store it in a **separate `.js` file** and link it to your HTML.  
This makes your code **cleaner**, **easier to maintain**, and **reusable** across multiple pages.

Example:
```html
<script src="script.js"></script>
🧩 How It Works
Create a JavaScript File
Example: script.js

javascript
Copy code
function greet() {
  alert("Hello from external JS!");
}
Link It in the HTML File

html
Copy code
<script src="script.js"></script>
Call the Function from HTML

html
Copy code
<button onclick="greet()">Click Me</button>
When you click the button, the function in the external file runs — showing an alert box.

🚀 Why Use External JavaScript?
Benefit	Description
✅ Clean Code	Keeps HTML and JS separate
🔁 Reusability	Use the same JS file on multiple pages
⚡ Better Performance	Browsers can cache JS files
🧭 Easier Maintenance	Update one file instead of multiple HTML pages

🧱 Example Explanation
In this project:

HTML File:
external-script-example.html
Contains a button that triggers the showAlert() function defined in the JS file.

External JS File:
script.js
Contains the function:

javascript
Copy code
function showAlert() {
  alert("Hello! This alert is from an external JavaScript file 🎉");
}
When you click the button, the function runs and displays an alert.

⚙️ The defer Attribute
In the <head> section:

html
Copy code
<script src="script.js" defer></script>
🧠 defer ensures the script is downloaded immediately but executed only after the HTML is fully parsed.
This prevents errors when scripts try to access elements that haven’t loaded yet.

🧮 Summary Table
Attribute	Description	Example
src	Specifies the external JS file	<script src="script.js"></script>
defer	Runs the script after HTML parsing	<script src="script.js" defer></script>
async	Runs the script as soon as it loads (not in order)	<script src="app.js" async></script>