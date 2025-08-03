# PixEdit - SVG Pixel Art Editor

A simple, browser-based pixel art editor that works with SVG format. Create pixel art directly in your browser with an intuitive interface.

## Features

### Drawing Tools
- **Draw Tool** - Click to place pixels with selected color
- **Erase Tool** - Remove pixels (make transparent)
- **Fill Tool** - Flood fill areas with selected color
- **Color Picker** (C key) - Hold C and click to pick colors from canvas
- **Transparent Eraser** (X key) - Hold X and click to make pixels transparent

### Canvas Features
- Adjustable grid size (8×8 to 64×64 pixels)
- Real-time preview with multiple zoom levels (1x to 16x)
- Upload SVG files for editing
- Shift entire canvas in any direction (↑↓←→ buttons)
- Undo/Redo support (Cmd/Ctrl+Z, Cmd/Ctrl+Shift+Z)

### Preview Options
- Live preview with scalable display
- Upload background images for preview
- Upload foreground images for preview (overlays on top of pixel art)
- Layer system: Background → Pixel Art → Foreground
- Transparent background support with checkerboard pattern

### Export Options
- Download as SVG (optimized for pixel art without grid lines)
- Download as PNG with transparency support

## Usage

1. Open `index.html` in a web browser
2. Select a color from the palette or use the custom color picker
3. Choose a drawing tool (Draw, Erase, or Fill)
4. Click on the canvas to create your pixel art
5. Use the preview panel to see your art at different scales
6. Export your creation as SVG or PNG

## Keyboard Shortcuts

- **Cmd/Ctrl + Z** - Undo
- **Cmd/Ctrl + Shift + Z** - Redo
- **Hold C + Click** - Pick color from canvas
- **Hold X + Click** - Make pixel transparent

## Browser Compatibility

Works in all modern browsers that support SVG and HTML5 Canvas.
