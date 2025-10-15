# Assets Directory

This directory contains assets for the Electron application.

## Required Files

### iconTemplate.png

- **Purpose**: System tray icon
- **Specifications**:
  - Size: 16x16 pixels (will be scaled automatically)
  - Format: PNG with transparent background
  - Style: Monochrome (black with transparency for light mode, white for dark mode)
  - Template naming: The "Template" suffix tells macOS to treat this as a template image

### How to create the icon:

1. Create a 16x16 or 32x32 pixel PNG image
2. Use a simple, recognizable symbol (e.g., a focus symbol, eye, or abstract shape)
3. Make it monochrome black on transparent background
4. Save as `iconTemplate.png` in this directory

### Alternative approach:

You can also create different sizes:

- `icon.png` (for general use)
- `icon@2x.png` (for retina displays)
- `iconTemplate.png` (for tray - monochrome)
- `iconTemplate@2x.png` (for retina tray)
