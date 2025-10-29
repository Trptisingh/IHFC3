# 🧩 CSS Grid — `grid-template-columns` and `grid-template-rows`

The **CSS Grid Layout** provides a powerful way to arrange elements in rows and columns.  
It’s ideal for building two-dimensional layouts (both horizontal and vertical).

---

## 🧠 What These Properties Do

### `display: grid`
Turns a container into a **grid layout**. Its child elements become **grid items**.

### `grid-template-columns`
Defines how many **columns** the grid will have and their **width**.

Example:
```css
grid-template-columns: 150px 150px 150px;
➡ This creates 3 columns, each 150px wide.

grid-template-rows
Defines how many rows the grid will have and their height.

Example:

css
Copy code
grid-template-rows: 100px 100px;
➡ This creates 2 rows, each 100px tall.

🧩 Example
html
Copy code
<div class="container">
  <div class="box1">Box 1</div>
  <div class="box2">Box 2</div>
  <div class="box3">Box 3</div>
  <div class="box4">Box 4</div>
  <div class="box5">Box 5</div>
  <div class="box6">Box 6</div>
</div>
css
Copy code
.container {
  display: grid;
  grid-template-columns: 150px 150px 150px;
  grid-template-rows: 100px 100px;
}
This creates a 3×2 grid (3 columns, 2 rows) that automatically places each box in a grid cell.

🎨 Visual Layout
diff
Copy code
+--------------------------------------------+
| Box1 | Box2 | Box3 |
| Box4 | Box5 | Box6 |
+--------------------------------------------+
3 columns × 2 rows grid

Each cell fits one grid item

Gaps and padding make spacing clearer

💡 Summary
Property	Purpose	Example	Description
display: grid	Turns element into grid container	—	Makes child elements grid items
grid-template-columns	Defines columns	150px 150px 150px	3 columns, each 150px
grid-template-rows	Defines rows	100px 100px	2 rows, each 100px

✅ Use Case: Perfect for creating dashboards, galleries, or layout sections where elements need both row and column structure.