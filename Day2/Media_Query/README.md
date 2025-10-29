# 📱 CSS Media Queries — Desktop, Tablet, and Mobile

**Media Queries** in CSS allow you to make your website responsive — meaning it adjusts its layout and style based on the **device screen size**.

This example demonstrates how the layout changes for:
- **Mobile phones**
- **Tablets**
- **Desktops**

---

## 🧠 What Are Media Queries?

A **media query** checks for specific conditions (like screen width) and applies CSS only when those conditions are true.

### Basic Syntax:
```css
@media (condition) {
  /* CSS rules here */
}
🧩 Example Code
css
Copy code
/* Mobile (max-width: 600px) */
@media (max-width: 600px) {
  .container {
    grid-template-columns: 1fr;
  }
}

/* Tablet (601px to 992px) */
@media (min-width: 601px) and (max-width: 992px) {
  .container {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Desktop (993px and above) */
@media (min-width: 993px) {
  .container {
    grid-template-columns: repeat(3, 1fr);
  }
}
🎨 Layout Behavior
Device	Screen Width	Layout	Background
📱 Mobile	≤ 600px	1 column	Peachpuff
💻 Tablet	601–992px	2 columns	Light Goldenrod
🖥️ Desktop	≥ 993px	3 columns	Light Gray

🧩 Visual Representation
Mobile (1 Column):

csharp
Copy code
[Box 1]
[Box 2]
[Box 3]
Tablet (2 Columns):

css
Copy code
[Box 1] [Box 2]
[Box 3]
Desktop (3 Columns):

css
Copy code
[Box 1] [Box 2] [Box 3]
💡 Summary
Concept	Description
@media	Defines conditions for applying specific styles
max-width	Applies styles up to a certain screen width
min-width	Applies styles above a certain screen width
Responsive Design	Ensures your layout adapts to different devices

✅ Tip: Always test your layout using browser developer tools (mobile/tablet/desktop view) to ensure responsiveness.