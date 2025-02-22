# Good Design Practice

## Types of Layout Grids

Figma supports three types of layout grids:

### Grid

- A uniform grid with equally spaced horizontal and vertical lines.
- **Use Case**: Ideal for aligning elements in a structured manner.
- **Customization**:

  - **Size**: Set the spacing between grid lines.
  - **Color**: Choose a color for the grid lines.
  - **Opacity**: Adjust the visibility of the grid lines.

![Grid Example](images/grid_example.png)

### Columns

- A vertical grid system with customizable column widths and gutters.
- **Use Case**: Perfect for creating responsive layouts for web or mobile designs.
- **Customization**:
  - **Count**: Set the number of columns.
  - **Gutter**: Define the spacing between columns.
  - **Margin**: Set the spacing around the edges of the frame.

![Columns Example](images/column_example.png)

### Rows

- A horizontal grid system with customizable row heights and gutters.
- **Use Case**: Useful for aligning content vertically, such as in tables or lists.
- **Customization**:
  As seen with columns:
- **Count**: Set the number of rows.
- Gutter: Define the spacing between rows.
- Margin: Set the spacing around the edges of the frame.

![Rows Example](images/row_example.png)

---

## Best Practices for Using Grids

- **Consistency**: Use the same grid system across all frames to maintain uniformity.
- **Spacing**: Set grid spacing to multiples of 8 (e.g., 8, 16, 24) for a clean and scalable design.
- **Alignment**: Align all elements to the grid to ensure a polished and professional look.

<div style="border: 2px solid rgb(255, 236, 28); padding: 10px; margin: 10px 0; border-radius: 4px;">
⚠️ <strong>Tip:</strong> Use Figma’s <strong>Snap to Grid</strong> feature to automatically align elements to the grid.
</div>

---

## Creating a Responsive Grid for Web Design

### 1. Select the Frame
Choose the most appropriate frame to represent your web page, ensuring it aligns with the intended screen size and layout.

### 2. Add a Column Grid
Set the count to 12, which is a common standard for web design. This grid structure provides flexibility and ensures a balanced layout across different screen sizes.

### 3. Define the Borders
The gutter, which is the spacing between columns, ensures proper separation of elements and prevents a cluttered appearance. A 20px gutter is commonly used for desktop designs, while 16px is often preferred for mobile layouts.

The margin, which is the space outside the grid, provides breathing room and maintains consistency in spacing. A 24px margin works well for most designs, but 32px can be used for additional whitespace when needed.

### 4. Add a Row Grid
A row count of 6 provides horizontal divisions that structure content effectively. The gutter for rows is typically set at 16px, ensuring a well-organized design without making elements feel too tight or too loose.

### 5. Align Elements
Use the grid to align buttons, text, and images consistently across the design. Proper alignment enhances readability and visual harmony, making the layout more structured and user-friendly.

---

## Additional Good Design Practices

- Ensure sufficient color contrast for readability by using tools like **[Figma’s contrast checker](https://www.figma.com/color-contrast-checker/)**.
- Use descriptive naming for layers and frames to improve accessibility.
- Support keyboard navigation and consider screen reader compatibility.

You now know the theory behind a great design, so lets learn about **[Figma Prototypes!](what-is-prototype.md)**
