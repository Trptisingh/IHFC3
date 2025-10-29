# 💻 Inline JavaScript — Complete Guide

This example demonstrates how to use **Inline JavaScript** within an HTML document.  
Inline JavaScript means writing JS code **directly inside the HTML file**, either using event attributes or inside the `<script>` tag.

---

## ⚙️ What is Inline JavaScript?

Inline JavaScript allows you to:
- Add small scripts directly to HTML elements.
- Execute functions or actions when a user interacts with the page (e.g., clicks a button).
- Avoid creating a separate `.js` file for very short scripts.

---

## 🧠 Syntax Overview

### ✅ 1. Using Event Attributes
Inline JS can be placed directly inside HTML tags using event attributes like `onclick`, `onmouseover`, etc.

Example:
```html
<button onclick="alert('Hello World!')">Click Me</button>
When the user clicks the button, the alert box appears immediately.

✅ 2. Using the <script> Tag
You can also embed JavaScript directly inside the HTML using a <script> tag.

Example:

html
Copy code
<script>
  document.write("This message is written by inline JavaScript!");
</script>
This script runs as soon as the browser reads it.

📄 Example Explanation
In this example:

The button uses inline JS with onclick:

html
Copy code
<button onclick="alert('Hello! This message is triggered by Inline JavaScript 🎉');">Click Me</button>
A script tag at the bottom of the HTML writes a message to the document:

⚠️ Best Practices
While inline JavaScript is useful for small tasks and demonstrations, it’s not recommended for large or production projects because:

It mixes HTML and JavaScript, making code harder to maintain.

It may cause security issues (e.g., XSS vulnerabilities).

It reduces reusability and readability.

✅ For larger projects, always use External JavaScript files linked using:

html
Copy code
<script src="script.js"></script>