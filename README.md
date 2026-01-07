## Responsive Navigation Bar
This README provides an overview of the **Hey! Sanzu** responsive navigation bar project. This implementation features a standard horizontal desktop menu that transforms into a toggleable sidebar for mobile devices.

### Project Overview:
The project consists of a clean, modern navigation system designed to be fully responsive. It uses a glassmorphism effect for the mobile sidebar and smooth transitions for user interaction.

### Key Features:

* **Responsive Design:** Automatically switches between a full-width desktop menu and a mobile-friendly hamburger menu at a width of `780px`.
* **Mobile Sidebar:** A slide-in navigation drawer with a `backdrop-filter (blur)` effect for a modern aesthetic.
* **Full-Screen Mobile Support:** On devices smaller than `400px`, the sidebar expands to cover the full width of the screen.
* **Interactive Elements:** Includes hover states for links and functional SVG icons for opening and closing the menu.

### File Structure:

| File | Description |
| --- | --- |
| `index.html` | Defines the structure of the navigation bar and the hidden sidebar. |
| `style.css` | Handles the layout, glassmorphism effects, and media queries for responsiveness. |
| `script.js` | Contains the logic to toggle the visibility of the mobile sidebar. |

### Technical Implementation:

**1. JavaScript Functionality:**
The navigation relies on two simple functions to manipulate the DOM:

* **`showSidebar()`**: Locates the `.sidebar` element and sets its display property to `flex`.
* **`hideSidebar()`**: Sets the display property back to `none`.

**2. Responsive Breakpoints:**

* **780px:** Hides standard menu items (`.hideOnMobile`) and displays the menu button (`.menu-button`).
* **400px:** Adjusts the sidebar width to `100%` for better usability on small phones.

**3. Styling:**

The design uses a clean white background for the desktop nav with a subtle box shadow. The mobile sidebar uses a translucent background with a `10px blur` to create a `glass effect` against the page background.

### How to Use:

1. Ensure all three files (`index.html`, `style.css`, `script.js`) are in the same directory.
2. Open `index.html` in any modern web browser.
3. Resize the browser window to see the transition between the desktop and mobile views.
---
Credit: `heysanzu`
