# 🎯 CSS `align-items: center`

The **`align-items`** property in Flexbox defines how flex items are aligned **vertically** (along the cross axis) within a flex container.  
Using **`align-items: center`**, all flex items are **centered vertically** in the container.

---

## 🧠 What It Does
```css
.container {
  display: flex;
  align-items: center;
}
This means:

All items inside the container will align along the vertical center (cross axis).

Even if items have different heights, they are centered relative to the container’s height.

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
  align-items: center;
  background-color: lightgray;
  height: 300px;
}
🎨 Visual Layout
less
Copy code
+---------------------------------------+
|                                       |
|   [Box1] [Box2] [Box3]  ← Centered vertically
|                                       |
+---------------------------------------+
Each box aligns vertically centered within the container.

Their horizontal positions remain in a row (default flex direction).

💡 Summary
Property	Description	Axis	Common Use
align-items	Aligns items vertically	Cross axis	Centering elements of different heights
Value: center	Centers items vertically		

✅ Useful for aligning content vertically in navigation bars, cards, and layouts with mixed-height items.