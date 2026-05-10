# PixelEdit

PixelEdit is a responsive browser-based image editor built with HTML, CSS, JavaScript, Bootstrap, Bootstrap Icons, and Cropper.js. It provides a clean SaaS-style interface for uploading, editing, cropping, adjusting, previewing, and exporting images directly in the browser.

---

## Features

### Responsive Editor Interface

* SaaS-style responsive layout
* Sidebar tools aligned with the image workspace
* Scrollable image canvas area
* Auto-fit uploaded image to the canvas
* Smooth scrolling when zoomed in

### Image Upload

* Click-to-upload support
* Drag-and-drop image upload
* File name preview after upload

### Editing History

* Undo changes
* Redo changes
* Reset all edits

### Export

* Export edited image as PNG
* Final image rendered using the Canvas API

---

# Transform Tools

### Crop Tools

Powered by Cropper.js

* Enter crop mode
* Apply crop
* Cancel crop
* Crop opens at the current visible image size

### Rotate & Flip

* Rotate left
* Rotate right
* Flip horizontally
* Flip vertically

---

# Zoom Tools

* Zoom in
* Zoom out
* Live zoom percentage display
* Initial image fit based on available workspace size
* Scrollable workspace when image exceeds the visible area

---

# Presets

PixelEdit includes multiple built-in image presets:

* Black and White
* Invert
* Dramatic
* Retro
* Cinematic
* Cool
* Warm
* Fade

Preset buttons include custom colors for a polished editor interface.

---

# Adjustments

Live adjustment sliders included for:

* Brightness
* Contrast
* Saturation
* Grayscale
* Sepia
* Invert
* Hue
* Blur

All slider values update in real time while editing.

---

# Collapsible Panels

The following sections are collapsible to keep the interface clean:

* Presets
* Adjustments

Users can open only the tools they need.

---

# Tech Stack

* HTML5
* CSS3
* JavaScript
* Bootstrap 5
* Bootstrap Icons
* Cropper.js
* Canvas API

---

# Project Structure

```bash
project-folder/
├── src/
│   ├── index.html
│   ├── styles.css
│   └── editor.js
```

---

# How To Run

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Upload an image.
4. Start editing.

No backend or installation is required.

---

# CDN Dependencies

This project uses CDN links for:

* Bootstrap
* Bootstrap Icons
* Cropper.js

Make sure you are connected to the internet when opening the project unless you download these libraries locally.

---

# Usage

1. Click **Choose File** to upload an image.
2. Use the zoom controls to adjust preview size.
3. Use **Enter Crop Mode** to crop the image.
4. Apply presets or manually adjust image settings.
5. Use undo and redo to navigate edit history.
6. Click **Export Image** to download the final PNG.

---

# Export Output

The edited image is exported as:

```bash
edited-image.png
```

---

# Live Demo

[PixelEdit Live Demo](https://image-editor-inky-six.vercel.app/?utm_source=chatgpt.com)

---

# License

This project is open source and available for personal and educational use.
