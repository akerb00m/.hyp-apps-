# Neon Sign - Hyperfy V2 App

A customizable neon sign system for Hyperfy V2 worlds. This app creates glowing text signs with adjustable colors, sizes, and alignment options.

## What it does

When you drop this app into your Hyperfy world, it will:
- Display customizable text as a glowing neon sign
- Support letters, numbers, and special characters (see list below)
- Allow adjustment of color, size, spacing, and alignment
- Create realistic neon glow effects
- Position text at configurable heights

Perfect for creating signs, labels, titles, or any text-based lighting in your world.

## UI Configuration Options

### Enter Text
- **What it does**: Sets the text displayed on the neon sign
- **Type**: Text input
- **Default**: "**HYPERFY**"
- **Supported**: Letters (A-Z), numbers (0-9), and special characters

### Letter Spacing
- **What it does**: Controls the space between individual letters
- **Range**: 0.1 to 5.0
- **Default**: 1.5
- **Step**: 0.1
- **Tip**: Higher values spread letters apart, lower values bring them closer

### Scale
- **What it does**: Controls the overall size of the neon sign
- **Range**: 0.1 to 5.0 (10% to 500% of original size)
- **Default**: 1.0 (100% of original size)
- **Step**: 0.1
- **Tip**: Use larger scales for prominent signs, smaller for subtle labels

### Height
- **What it does**: Sets the vertical position of the sign above ground
- **Range**: 1 to 10 meters
- **Default**: 1 meter
- **Step**: 0.1
- **Tip**: Position signs at eye level or higher for best visibility

### Glow Intensity
- **What it does**: Controls the brightness of the neon glow effect
- **Range**: 0 to 20
- **Default**: 1
- **Step**: 0.1
- **Tip**: Higher values create brighter, more intense glow effects

### Color
- **What it does**: Sets the color of the neon sign
- **Range**: 0 to 1 (color spectrum)
- **Default**: 0.5
- **Step**: 0.01
- **Tip**: Experiment with different values to find your desired color

### Text Alignment
- **What it does**: Controls how the text is positioned relative to the sign's center
- **Options**: Left, Center, Right
- **Default**: Center
- **How it works**: 
  - Left: Text starts from the left edge
  - Center: Text is centered (default)
  - Right: Text ends at the right edge

## Supported Characters

### Letters
- All uppercase letters (A-Z)
- Automatically converts lowercase to uppercase

### Numbers
- All digits (0-9)

### Special Characters
- @ (at)
- ? (question)
- & (ampersand)
- # (hash)
- ! (exclamation)
- / (slash)
- ( ) (parentheses)
- { } (curly braces)
- [ ] (brackets)
- * (asterisk)
- - (minus)
- _ (underscore)
- " (quote)
- : (colon)
- = (equals)

## How it works

1. **Character Mapping**: Each character in your text is mapped to a corresponding 3D mesh
2. **Text Rendering**: Individual letter meshes are positioned and scaled according to your settings
3. **Glow Effects**: Neon materials with emission properties create the glowing effect
4. **Alignment**: Text positioning is calculated based on letter spacing and alignment choice
5. **Dynamic Updates**: Changes to settings immediately update the sign appearance

## Usage Tips

1. **Color Selection**: Use the color slider to find the perfect neon hue
2. **Scale and Height**: Consider the viewing distance when setting size and height
3. **Glow Intensity**: Higher values create more dramatic effects but may impact performance
4. **Alignment**: Center alignment works best for most applications

## Technical Details

- **Character Support**: 26 letters + 10 numbers + 18 special characters
- **Dynamic Positioning**: Automatic text centering and spacing calculation
- **Performance**: Efficient mesh cloning and material sharing

## Author

**Gert-Jan Akerboom**
- Twitter: [@GertJanAkerboom](https://x.com/GertJanAkerboom)
- License: MIT
- Copyright (c) 2025 Gert-Jan Akerboom 