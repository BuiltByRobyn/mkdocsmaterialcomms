# Troubleshooting

---

### Grid Issues

If you're experiencing issues with Figma's Layout Grid, use this guide to identify and resolve common problems related to grid size, spacing, margins, and visibility.

#### Grid Not Visible

- **Frame Selection**: Ensure the correct frame is selected when enabling the grid.

<div style="border: 2px solid #ff0000; padding: 10px; margin: 10px 0; border-radius: 4px;">
❌ Error: No grid has been placed on the frame.
</div>

![No Grid Example](images/framenogrid.png)

<div style="border: 2px solid #00cc00; padding: 10px; margin: 10px 0; border-radius: 4px;">
✅ Success: A correctly applied grid will appear like this on the frame.
</div>

![Grid Example](images/framegrid.png)

- **Toggle Grid Visibility**: Click the **Grid icon** or **Eye icon** in the right panel to show/hide the grid.

<div style="position:relative; width:100%; height:0px; padding-bottom:56.098%"><iframe allow="fullscreen;autoplay" allowfullscreen height="100%" src="https://streamable.com/e/ijn3bx?autoplay=1&muted=1" width="100%" style="border:none; width:100%; height:100%; position:absolute; left:0px; top:0px; overflow:hidden;"></iframe></div>

- **Zoom Level**: Adjust the zoom level to see the grid clearly. You can adjust the zoom by **clicking on the zoom percent**.

  ![Zoom Example](images/zoom.png)

#### Grid Settings

- **Check the Grid Type**: In the Layout Grid panel, ensure that you're using the correct type.

  ![Grid Options Example](images/grid_options.png)

- **Verify Grid Spacing**

  - **Click** the dropdown (currently "Grid 8px") and confirm the spacing value is correct.
  - If it’s too dense or too sparse, **adjust it manually**.

  ![Set Grid Example](images/layoutgrid.png)

- **Snap to Pixel Grid**: Enable **Snap to Pixel Grid** to ensure elements align perfectly with the grid lines. Just like adjusting the view, you can find snap to grid under the **zoom percentage**.

  ![Snap To Fit Example](images/snaptofit.png)

---

## Prototype Issues

Prototyping in Figma allows for interactive mockups, but sometimes things don’t work as expected. Below are common issues and their solutions to help you troubleshoot efficiently.

### Prototype Not Working

If interactions are unresponsive or not functioning as expected, check the following:

- **Check Connections**: **Open Prototype Mode** and ensure that all frames are properly linked with interaction arrows.
<div style="border: 2px solid #00cc00; padding: 10px; margin: 10px 0; border-radius: 4px;">
✅ Success: A correctly applied connection will appear like this on the prototype.
</div>

![Grid Example](images/connection.png)

Click on each connection and verify the interaction settings (e.g., _On Click,_ _While Hovering,_ etc.).

<div style="position:relative; width:100%; height:0px; padding-bottom:56.250%"><iframe allow="fullscreen;autoplay" allowfullscreen height="100%" src="https://streamable.com/e/9pvq8w?autoplay=1&muted=1" width="100%" style="border:none; width:100%; height:100%; position:absolute; left:0px; top:0px; overflow:hidden;"></iframe></div>

If a frame is missing a connection, re-add it manually by **dragging the blue arrow to the target frame**.

<div style="position:relative; width:100%; height:0px; padding-bottom:56.098%"><iframe allow="fullscreen;autoplay" allowfullscreen height="100%" src="https://streamable.com/e/vm4odi?autoplay=1&muted=1" width="100%" style="border:none; width:100%; height:100%; position:absolute; left:0px; top:0px; overflow:hidden;"></iframe></div>

- **Device Preview**: Test the prototype on different devices to ensure responsiveness.

<div style="position:relative; width:100%; height:0px; padding-bottom:56.098%"><iframe allow="fullscreen;autoplay" allowfullscreen height="100%" src="https://streamable.com/e/6u4k9a?autoplay=1&muted=1" width="100%" style="border:none; width:100%; height:100%; position:absolute; left:0px; top:0px; overflow:hidden;"></iframe></div>
---

## Sharing Issues

- **Link Expiry**: Ensure the shared link has not expired or been revoked.

- **Permissions**: Verify that the sharing settings allow access for the intended audience. You can access share setting in [**Share**] -> [**Anyone**].

![Change Permissions Example](images/permissions.png)

---

## Additional Support

If you continue to experience issues, consider checking Figma’s official documentation or experimenting with different settings to refine your design process. Figma also has excellent customer support available for those who need further assistance. You can visit the Community Forum and reach out with questions [here](https://help.figma.com/hc/en-us/articles/360041057214-Get-help-with-Figma#:~:text=The%20best%20way%20to%20contact,browser%2C%20or%20the%20Figma%20Community.&text=At%20the%20bottom%20of%20the,topic%20in%20the%20field%20provided).