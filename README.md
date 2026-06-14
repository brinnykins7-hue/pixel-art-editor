# PixelForge — Pixel Art Editor

A free, browser-based pixel art editor inspired by Aseprite. Built with vanilla HTML, CSS & JavaScript — no frameworks, no build tools, no dependencies.

![PixelForge](https://img.shields.io/badge/PixelForge-Pixel%20Art%20Editor-e94560?style=for-the-badge)

## ✨ Features

- **9 Drawing Tools**: Pencil, Eraser, Line, Rectangle, Ellipse, Fill, Eyedropper, Selection, Move
- **Layer System**: Add, delete, duplicate, merge, reorder layers with blend modes and opacity
- **Animation**: Frame-based timeline, onion skinning, adjustable FPS playback
- **Color Picker**: Full HSL/RGB/Hex picker with 5 preset palettes (PICO-8, Endesga 32, Game Boy, Sweetie 16, AAP-64)
- **Export**: PNG, animated GIF, spritesheet
- **Auto-Save**: Your work is saved in the browser automatically
- **Keyboard Shortcuts**: Full shortcut support for all tools
- **Templates**: 10 built-in templates for characters, tilesets, and icons
- **Symmetry Mode**: Horizontal & vertical mirror drawing
- **No Internet Required**: Works completely offline once loaded

---

## 🖥️ Use Locally (Recommended for Beginners)

**Just double-click to open!** No installation needed.

1. Download this folder to your computer
2. Open the `index.html` file in your browser (Chrome, Firefox, or Edge)
3. Start drawing!

Your work auto-saves in your browser. If you close the tab and re-open the file, it'll ask if you want to resume.

> **Tip:** You can also drag `index.html` into your browser window to open it.

---

## 🌐 Deploy to GitHub Pages (No Terminal Needed!)

Want to share your editor online? Follow these steps — **all from your web browser**, no git commands required:

### Step 1: Create a GitHub Account
If you don't have one, go to [github.com](https://github.com) and sign up (it's free).

### Step 2: Create a New Repository
1. Go to [github.com/new](https://github.com/new)
2. Name it something like `pixel-art-editor`
3. Make sure **Public** is selected
4. **Don't** check "Add a README" (we already have one)
5. Click **Create repository**

### Step 3: Upload the Files
1. On your new empty repo page, click **"uploading an existing file"** (or go to `github.com/YOUR-USERNAME/pixel-art-editor/upload/main`)
2. **Drag and drop** the entire contents of this folder into the upload area:
    - `index.html`
    - `style.css`
    - `script.js`
    - `README.md`
3. Scroll down and click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Go to your repo's **Settings** tab
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Under "Branch", select **main** and **/ (root)**
5. Click **Save**

### Step 5: Visit Your Site!
After a minute or two, your pixel art editor will be live at:
```
https://YOUR-USERNAME.github.io/pixel-art-editor/
```

🎉 **That's it!** Share the link with anyone.

---

## ⌨️ Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Pencil | `B` |
| Eraser | `E` |
| Line | `L` |
| Rectangle | `U` |
| Ellipse | `O` |
| Fill Bucket | `G` |
| Eyedropper | `I` |
| Selection | `M` |
| Move | `V` |
| Undo | `Ctrl+Z` |
| Redo | `Ctrl+Y` |
| Swap Colors | `X` |
| Brush Size Up/Down | `]` / `[` |
| Toggle Grid | `Ctrl+'` |
| Zoom In/Out | `Ctrl+=` / `Ctrl+-` |
| New Frame | `Alt+N` |
| Next/Prev Frame | `.` / `,` |
| Play/Pause | `Enter` |
| Show Shortcuts | `?` |

---

## 📁 Project Structure

```
pixel-art-editor/
├── index.html          ← Open this file!
├── css/
│   └── style.css       ← Dark theme & styling
├── js/
│   ├── state.js        ← Shared state & utilities
│   ├── canvas.js       ← Canvas rendering engine
│   ├── tools.js        ← Drawing tools
│   ├── layers.js       ← Layer management
│   ├── palette.js      ← Color picker & palettes
│   ├── animation.js    ← Timeline & animation
│   ├── history.js      ← Undo/redo
│   ├── templates.js    ← Built-in templates
│   ├── storage.js      ← Auto-save & file I/O
│   ├── export.js       ← PNG/GIF/spritesheet export
│   ├── shortcuts.js    ← Keyboard shortcuts
│   ├── ui.js           ← UI interactions
│   └── app.js          ← Main entry point
└── README.md
```

---

## 🛠️ Tech

- **Zero dependencies** — pure vanilla JavaScript
- **No build step** — works directly from the filesystem
- **No internet required** — works completely offline (except Google Fonts, which falls back gracefully)
- **IndexedDB** for persistent auto-save
- **Canvas API** for pixel-perfect rendering
- **Built-in GIF encoder** — no external libraries

---

Made with ❤️ and pixels.
