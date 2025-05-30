# 3. Reusable Accordion module
Reusable accordion module (expand/collapse)

## 📄 Code Overview

This project implements a **custom accordion component** with dynamic theming. It is built using **vanilla HTML, CSS, and JavaScript**, with an emphasis on simplicity and readability.

### 🧱 HTML Structure

- The layout consists of:
  - A `<div class="controls">` section containing four color pickers that allow live customization of the accordion's appearance.
  - A `<div class="accordion">` with three collapsible items, each containing:
    - A button serving as the accordion header
    - A content panel that toggles visibility

### 🎨 CSS Styling

- CSS variables are used to define and update the accordion's design:
  - `--header-bg`: Header background color
  - `--content-bg`: Content background color
  - `--border-color`: Border color
  - `--text-color`: Text color
- These variables are updated in real-time using JavaScript.
- Key layout and design choices:
  - Centered alignment of controls and accordion
  - Rounded corners and spacing for a clean look
  - Responsive design with a maximum width

### ⚙️ JavaScript Functionality

- **Accordion Toggle**:
  - A simple `onclick` handler toggles the `.show` class on the content panel to show/hide it.
- **Color Picker Controls**:
  - Four `<input type="color">` elements allow users to dynamically update the accordion's theme.
  - A helper function `setVar(id, name)` reduces repetitive code by attaching input listeners to each color control.

### ✅ What Was Done
  - Used minimal and clean toggling to control accordion visibility
  - Kept styles minimal for better maintainability

### 📦 Final Result

- A **lightweight, responsive accordion** with real-time color customization.
- Fully self-contained using **HTML, CSS, and JavaScript only**.
- Easy to copy, reuse, or adapt in other web projects.
