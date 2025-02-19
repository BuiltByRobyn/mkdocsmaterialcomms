# Project Structure

---

## Good Design Practice

Using grids in Figma helps maintain consistency and alignment in your designs. Here’s how to implement and use grids effectively:

### Adding a Grid
1. **Select the Frame**:
   - Click on the frame or canvas where you want to add a grid.

2. **Enable Grid**:
   - Go to the **Design** tab in the right sidebar.
   - Under the **Layout Grid** section, click the **+** button to add a grid.

3. **Customize the Grid**:
   - Choose between **Grid**, **Columns**, or **Rows**.
   - Adjust the grid size, color, and opacity to suit your design needs.

![Grid Example](images/grid%20layout.png)

---

### Types of Layout Grids

Figma supports three types of layout grids:

#### **Grid**
   - A uniform grid with equally spaced horizontal and vertical lines.
   - **Use Case**: Ideal for aligning elements in a structured manner.
   - **Customization**:
     - **Size**: Set the spacing between grid lines.
     - **Color**: Choose a color for the grid lines.
     - **Opacity**: Adjust the visibility of the grid lines.

#### **Columns**
   - A vertical grid system with customizable column widths and gutters.
   - **Use Case**: Perfect for creating responsive layouts for web or mobile designs.
   - **Customization**:
     - **Count**: Set the number of columns.
     - **Gutter**: Define the spacing between columns.
     - **Margin**: Set the spacing around the edges of the frame.

#### **Rows**
   - A horizontal grid system with customizable row heights and gutters.
   - **Use Case**: Useful for aligning content vertically, such as in tables or lists.
   - **Customization**:
     - **Count**: Set the number of rows.
     - **Gutter**: Define the spacing between rows.
     - **Margin**: Set the spacing around the edges of the frame.

---

### Best Practices for Using Grids
- **Consistency**: Use the same grid system across all frames to maintain uniformity.
- **Spacing**: Set grid spacing to multiples of 8 (e.g., 8, 16, 24) for a clean and scalable design.
- **Alignment**: Align all elements to the grid to ensure a polished and professional look.

!!! tip
    Use Figma’s **Snap to Grid** feature to automatically align elements to the grid.


---

### Example: Creating a Responsive Grid for Web Design

1. **Select the Frame**:
   - Choose the frame representing your web page.

2. **Add a Column Grid**:
   - Set the **Count** to 12 (a common standard for web design).
   - Define the **Gutter** as 20px and the **Margin** as 24px.

3. **Add a Row Grid**:
   - Set the **Count** to 6 and the **Gutter** to 16px.

4. **Align Elements**:
   - Use the grid to align buttons, text, and images consistently across the design.

---

## Prototype in Figma

Figma’s prototyping features allow you to create interactive flows that explore how a user may interact with your designs.

Prototypes are a fantastic way to:
- Preview interactions and user flows.
- Share and iterate on ideas.
- Get feedback from collaborators.
- Test interactions with users.
- Present your designs to stakeholders.

!!! tip
     For an even more efficient workflow, you can quickly toggle between the Design and Prototype tabs using the keyboard shortcut **Shift + E**.

---

### Flows and Starting Points
With prototyping in Figma, you can create multiple flows for your prototype in one page to preview a user's full journey and experience through your designs.

A **flow** is the network of frames and connections in a single page. A prototype can map out a user's entire journey through your app or website, or it can focus on a specific segment of it via its own flow. For example:
- Your prototype covers all possible interactions on an eCommerce site.
- Within the prototype, you have flows for creating an account, adding items to a cart, and checking out.

Figma creates a flow starting point when you add your first connection between two frames. There are a few other ways to add a flow starting point to your prototype:
- With the starting frame selected, click **+** in the **Flow starting point** section of the right sidebar.
- Right-click on the frame, then click **Add starting point**.
- Duplicate a frame with an existing starting point.

When it's time to test your designs, you can share the entire prototype or copy the link to a flow starting point.

**Note:** A top-level frame can be part of multiple flows but can only have one starting point. Frames nested within a top-level starting frame can have connections that navigate the user around multiple flows. For example:
- **Log in** and **Sign up** buttons can be nested in the same starting point frame.
- These buttons can then be connected to frames in separate flows for each experience.

---

### Create Connections
1. Select the hotspot for the connection.
2. Click **+** to create the connection.
3. Drag it to the destination.
4. If there are no existing connections, Figma will make the first frame a starting point.

!!! tip
    You can create connections from multiple objects to the same destination frame at the same time—saving you time and effort when building out your prototype flows. To do so:
    - Select multiple starting hotspots on your canvas.
    - Click and drag the **+** icon to the destination.

![Grid Example](images/Anatomy%20of%20a%20connection%20between%20two%20frames%20(2).png)

---

### Create Interactions and Animations
1. Open the **Prototype** tab in the right sidebar.
2. Add interactions.
3. Set interaction details.
4. Apply an animation.
5. Preview your animation.

![Grid Example](images/Create%20interactions%20and%20animations%20(3)%201%20(1).png)
---

### Adjust Prototype Settings
1. Select a **Device and Model**.
2. Preview your prototype.
3. Select **Background color**.
4. Set the prototype's **Starting Frame**.

![Grid Example](images/Prototype%20tab%20of%20right%20sidebar%20with%20device,%20preview,%20background,%20and%20flow%20settings%20(1).png)
---

### Publishing the Prototype
1. **Click the Share button** in the top-right corner of the Figma interface.
2. **Set the sharing permissions** to either **Anyone with the link** or specify particular individuals or teams.
3. **Click Copy Link** to obtain the URL for sharing your prototype.

---

### Presenting the Prototype
1. **Open the prototype link** in your browser by pasting the copied link.
2. **Enter Presentation Mode** by clicking on the full-screen icon, which will display your design in a distraction-free environment.
3. Navigate through frames and interactions to demonstrate the flow.

