# Grass and Flowers - Hyperfy V2 App

A sophisticated grass and flower generation system for Hyperfy V2 worlds. This app creates natural-looking vegetation with both clustered and scattered distribution patterns.

## What it does

When you drop this app into your Hyperfy world, it will:
- Generate multiple grass and flower models with random positioning
- Create natural clusters of vegetation in addition to scattered pieces
- Apply random scales, rotations, and distribution patterns
- Place all vegetation at ground level (Y = 0)

Perfect for creating meadows, gardens, fields, or adding natural vegetation to any outdoor scene.

## UI Configuration Options

### Clone Count
- **What it does**: Controls the total number of grass and flower pieces generated
- **Range**: 1 to 10,000 pieces
- **Default**: 20 pieces
- **Tip**: Higher numbers create denser vegetation but may impact performance

### Area Width (X meters)
- **What it does**: Sets the width of the area where vegetation will be distributed
- **Range**: 1 to 100 meters
- **Default**: 10 meters
- **How it works**: Vegetation is placed randomly between -X and +X on the X-axis

### Area Depth (Z meters)
- **What it does**: Sets the depth of the area where vegetation will be distributed
- **Range**: 1 to 100 meters
- **Default**: 10 meters
- **How it works**: Vegetation is placed randomly between -Z and +Z on the Z-axis

### Minimum Clone Size
- **What it does**: Sets the smallest possible scale for any vegetation piece
- **Range**: 0.01 to 5.0 (1% to 500% of original size)
- **Default**: 0.2 (20% of original size)
- **Tip**: Use smaller values for more variety, larger values for more consistent sizing

### Maximum Clone Size
- **What it does**: Sets the largest possible scale for any vegetation piece
- **Range**: 0.1 to 5.0 (10% to 500% of original size)
- **Default**: 2.0 (200% of original size)
- **Tip**: Combine with minimum size to create size variation in your vegetation

### Percentage of Grass in Clusters
- **What it does**: Controls what percentage of vegetation is placed in clusters vs scattered
- **Range**: 0 to 100%
- **Default**: 30%
- **How it works**: This percentage of vegetation will be grouped into clusters, the rest scattered randomly
- **Tip**: Higher percentages create more natural-looking vegetation patterns

### Cluster Size (radius in meters)
- **What it does**: Sets the radius of each vegetation cluster
- **Range**: 0.1 to 10 meters
- **Default**: 1 meter
- **How it works**: Vegetation within a cluster is placed randomly within this radius
- **Tip**: Smaller clusters create tight groups, larger clusters create spread-out patches

### Cluster Density (grass per m²)
- **What it does**: Controls how many vegetation pieces are placed per square meter in clusters
- **Range**: 1 to 20 pieces per m²
- **Default**: 5 pieces per m²
- **How it works**: Determines how dense the clustered vegetation will be
- **Tip**: Higher density creates thicker vegetation patches

## How it works

1. **Dual Distribution**: Vegetation is placed using both clustered and scattered patterns
2. **Random Selection**: Each piece randomly selects from available grass and flower models
3. **Natural Variation**: Random scales, rotations, and positions create natural-looking results
4. **Performance**: Efficient cloning system handles large numbers of vegetation pieces

## Usage Tips

1. **Performance**: Start with lower clone counts (100-500) and increase as needed
2. **Cluster Planning**: Use clusters to create natural vegetation patches
3. **Size Variation**: Different min/max sizes create more realistic vegetation
4. **Area Planning**: Consider the relationship between area size and vegetation density

## Technical Details

- **Distribution**: Hybrid clustered and scattered placement system
- **Scaling**: Uniform scaling maintains proportions
- **Rotation**: Random Y-axis rotation for natural orientation
- **Ground Placement**: All vegetation placed at Y = 0 for ground contact

## Author

**Gert-Jan Akerboom**
- Twitter: [@GertJanAkerboom](https://x.com/GertJanAkerboom)
- License: MIT
- Copyright (c) 2025 Gert-Jan Akerboom 