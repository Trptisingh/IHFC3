# 🧠 Using `<script>` Tag in `<head>` and `<body>` — Complete Guide

This project demonstrates how the **`<script>` tag** works when placed inside the `<head>` and `<body>` sections of an HTML document.

---

## ⚙️ What is the `<script>` Tag?

The `<script>` tag in HTML is used to include **JavaScript code** inside a web page.  
It can either:
- Contain **inline JavaScript** code directly, or  
- Reference an **external JavaScript file** using the `src` attribute.

Example:
```html
<script src="script.js"></script>
🧩 Placement of Script Tag
JavaScript code can be placed in two main areas:

✅ 1. Inside the <head> Tag
Placing scripts in the <head> executes them before the page content loads.

Example:

html
Copy code
<head>
  <script>
    console.log("Head script runs before the body loads");
  </script>
</head>
🧠 Use this when:

You’re defining functions or global variables used later in the page.

You don’t need to manipulate elements that aren’t yet loaded.

⚠️ Note: Scripts in <head> may delay page rendering if they perform heavy operations.

✅ 2. Inside the <body> Tag
Scripts placed inside <body> (usually near the end) execute after the page content is loaded.

Example:

html
Copy code
<body>
  <button onclick="showMessage()">Click Me</button>

  <script>
    function showMessage() {
      alert("This message is from the body script!");
    }
  </script>
</body>
🧠 Use this when:

The script interacts with HTML elements (e.g., buttons, paragraphs).

You want faster page load before scripts execute.

🧱 Example Explanation
In the provided HTML file:

Head Script

html
Copy code
<script>
  console.log("Script inside <head> executed before the body loads.");
</script>
➜ This runs as soon as the browser reads the <head> section.

Body Script

html
Copy code
<script>
  function showMessage() {
    alert("Hello! This message is from the <body> script section 🎉");
  }
</script>
➜ This runs only after the page content has loaded, and defines a function used by the button.

When the user clicks the button, the showMessage() function triggers an alert message.

🧮 Summary Table
Location	Executes When	Common Use Case	Advantage
<head>	Before content loads	Function declarations, metadata setup	Prepares logic early
<body>	After content loads	DOM manipulation, event handling	Faster visible rendering

⚡ Best Practice
Place scripts just before the closing </body> tag unless you need them to run immediately.
This improves performance and ensures all page elements are available.

