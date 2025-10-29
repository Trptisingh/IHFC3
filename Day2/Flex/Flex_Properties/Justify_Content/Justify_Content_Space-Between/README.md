# 🎯 CSS `justify-content: space-between`

The **`justify-content`** property in Flexbox defines how flex items are distributed along the **main axis**.  
Using **`space-between`**, items are spaced evenly — the **first item** is placed at the start, and the **last item** is placed at the end of the container.  
All remaining items are evenly distributed in between.

---

## 🧠 What It Does
```css
.container {
  display: flex;
  justify-content: space-between;
}
This ensures:

The first flex item is aligned to the start.

The last flex item is aligned to the end.

Equal space between all other items.

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
  justify-content: space-between;
  background-color: lightgray;
  height: 200px;
}
🎨 Visual Layout
css
Copy code
[Box 1]      [Box 2]      [Box 3]
Boxes are spread out evenly with equal space between them.

No space is added before the first or after the last box.

💡 Summary
justify-content → aligns items horizontally (main axis).

space-between → places first item at start, last item at end, equal spacing in between.

Great for navigation bars, toolbars, or footer layouts.