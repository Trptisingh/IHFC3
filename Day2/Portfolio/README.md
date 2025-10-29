# 🌟 Vision Viksit Bharat - About Me Webpage

This project is a simple **HTML + CSS personal webpage** designed for **KV students** participating in the **Vision Viksit Bharat** initiative.  
It showcases basic web design elements such as headers, sections, forms, images, and responsive design using **media queries**.

---

## 🧩 **Project Overview**

The webpage introduces a student, their goals, hobbies, and interests.  
It uses semantic HTML and modern CSS to build a clean, accessible layout suitable for beginners learning web development.

---

## 🎨 **Features Used**

### 🖌️ **1. Basic Page Styling**
- A clean layout with readable fonts and color combinations.  
- `background-color`, `color`, `margin`, and `padding` properties enhance visual appeal.

```css
body {
  font-family: "Trebuchet MS", Arial, sans-serif;
  background-color: #f5f9ff;
  margin: 0;
  padding: 0;
  color: #222;
}
📦 2. Section Styling
Each section is designed using:

White background (#ffffff)

Rounded corners using border-radius

Light blue borders for visual separation

css
Copy code
section {
  background-color: #ffffff;
  margin: 15px;
  padding: 15px;
  border: 1px solid #cce0ff;
  border-radius: 6px;
}
🧍‍♀️ 3. Flexbox for Layout
Images and text are aligned horizontally using Flexbox:

css
Copy code
div {
  display: flex;
  align-items: center;
}
This helps in aligning content neatly side by side, such as an image and caption.

🪶 4. Buttons and Input Styling
All form elements (input, textarea, and buttons) are styled for better usability:

css
Copy code
input, textarea, button {
  font-family: inherit;
  width: 100%;
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 4px;
}
The submit button changes color on hover using:

css
Copy code
input[type="submit"]:hover {
  background-color: #005b99;
}
🧩 5. Media Query for Responsiveness
The page is responsive and adapts well on mobile devices using a media query:

css
Copy code
@media (max-width: 600px) {
  div {
    flex-direction: column;
    text-align: center;
  }

  img {
    margin: 0 0 10px 0;
  }
}
This ensures that on smaller screens, elements stack vertically for readability.

🧠 Concepts Demonstrated
Concept	Description
Semantic HTML	Uses <header>, <section>, <footer>, <blockquote>, <details>, and <summary>
Forms	Demonstrates use of text inputs, email inputs, textarea, and submit button
Flexbox	Aligns image and text side-by-side
Media Queries	Makes the webpage mobile-friendly
Color & Typography	Enhances readability using color contrast and simple fonts
