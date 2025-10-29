# 🎯 CSS `justify-content: flex-start`

The **`justify-content`** property aligns flex items **along the main axis** (horizontal by default).

When set to **`flex-start`**, all items are placed **at the beginning** of the flex container.

---

## 🧠 What It Does
```css
.container {
  display: flex;
  justify-content: flex-start;
}
All items are grouped on the left side of the container (default alignment).

🧩 Example
html
Copy code
<div class="container">
  <div class="box1">Box 1</div>
  <div class="box2">Box 2</div>
  <div class="box3">Box 3</div>
</div>
css
Copy code
.container {
  display: flex;
  justify-content: flex-start;
  background-color: lightgray;
  height: 200px;
}
🎨 Visual Layout
css
Copy code
[Box 1] [Box 2] [Box 3]               
All boxes are aligned to the left side (start) of the container.

💡 Summary
justify-content controls horizontal alignment in a flex container.

justify-content: flex-start aligns items to the start (left) of the main axis.

This is the default alignment in Flexbox.