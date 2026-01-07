<p align="center">
  <img src="path/to/your/thumbnail.png" alt="Hey! Sanzu Nav Bar Thumbnail" width="800">
</p>

## Responsive Navigation Bar

This project features a clean, modern navigation system designed for high usability across all devices. It implements a standard horizontal desktop menu that transforms into a sleek, toggleable sidebar for mobile users.

### Project Overview
Created by **Hey! Sanzu**, this implementation focuses on a "Mobile First" logic using a glassmorphism effect and smooth transitions to provide a premium user experience.

### Key Features

* **Responsive Design:** Seamlessly switches layouts at a `780px` breakpoint.
* **Glassmorphism UI:** Mobile sidebar features a `backdrop-filter (blur)` for a modern aesthetic.
* **Full-Screen Support:** Optimized for small devices (< `400px`) by expanding the sidebar to full width.
* **Lightweight Logic:** Built with vanilla JS for maximum performance.

### File Structure

| File | Description |
| --- | --- |
| `index.html` | Semantic structure of the nav and hidden sidebar. |
| `style.css` | Layout, media queries, and glassmorphism styling. |
| `script.js` | Logic for toggling sidebar visibility. |

### Technical Implementation

#### 1. JavaScript Logic
The navigation uses two lightweight functions to manipulate the DOM:
* **`showSidebar()`**: Displays the `.sidebar` element using `flex`.
* **`hideSidebar()`**: Reverts the display property to `none`.

#### 2. Responsive Breakpoints
* **`780px`**: Triggers the hamburger menu (`.menu-button`) and hides desktop links.
* **`400px`**: Forces the sidebar to `100%` width for small-screen accessibility.

#### 3. Styling & Effects
The design utilizes a subtle `box-shadow` for the desktop view and a **10px blur** glass effect for the mobile drawer, ensuring content remains legible over any background.

### How to Use

1. Ensure `index.html`, `style.css`, and `script.js` are in the same directory.
2. Open `index.html` in your preferred browser.
3. Resize the window to test the responsive transition.

---
Credit: [heysanzu](https://github.com/heysanzu)
