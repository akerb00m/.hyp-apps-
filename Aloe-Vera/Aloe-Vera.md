# Aloe Vera - Hyperfy V2 App

A generative aloe vera plant system for Hyperfy V2 worlds. This app automatically creates multiple instances of aloe vera plants with randomized positions, rotations, and sizes to create natural-looking plant clusters.

## What it does

When you drop this app into your Hyperfy world, it will:
- Take your aloe vera GLB model (named "Cube" in the model)
- Create multiple clones based on your settings
- Distribute them randomly across a specified area
- Apply random rotations and sizes for natural variation
- Place all plants at ground level (Y = 0)

Perfect for creating lush aloe vera gardens, desert landscapes, or adding natural vegetation to your world.

## UI Configuration Options

### Clone Count
- **What it does**: Controls how many aloe vera plants are generated
- **Range**: 1 to 100 plants
- **Default**: 20 plants
- **Tip**: Start with a lower number for performance, increase for denser gardens

### Area Width (X meters)
- **What it does**: Sets the width of the area where plants will be distributed
- **Range**: 1 to 50 meters
- **Default**: 10 meters
- **How it works**: Plants are placed randomly between -X and +X on the X-axis

### Area Depth (Z meters)
- **What it does**: Sets the depth of the area where plants will be distributed
- **Range**: 1 to 50 meters
- **Default**: 10 meters
- **How it works**: Plants are placed randomly between -Z and +Z on the Z-axis

### Minimum Clone Size
- **What it does**: Sets the smallest possible scale for any plant
- **Range**: 0.1 to 5.0 (10% to 500% of original size)
- **Default**: 0.2 (20% of original size)
- **Tip**: Use smaller values for more variety, larger values for more consistent sizing

### Maximum Clone Size
- **What it does**: Sets the largest possible scale for any plant
- **Range**: 0.1 to 5.0 (10% to 500% of original size)
- **Default**: 2.0 (200% of original size)
- **Tip**: Combine with minimum size to create size variation in your garden

## Usage Tips

1. **Performance**: Higher clone counts may impact performance on slower devices
2. **Area Planning**: Consider the total area size - larger areas with fewer plants will look sparse
3. **Size Variation**: Set minimum and maximum sizes close together for uniform gardens, or far apart for wild, natural looks
4. **Placement**: All plants are placed at ground level (Y = 0), so position your app where you want the garden to appear

## Author

**Gert-Jan Akerboom**
- Twitter: [@GertJanAkerboom](https://x.com/GertJanAkerboom)
- License: MIT
- Copyright (c) 2025 Gert-Jan Akerboom 