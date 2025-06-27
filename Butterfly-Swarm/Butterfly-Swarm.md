# Butterfly Swarm - Hyperfy V2 App

A dynamic butterfly swarm system for Hyperfy V2 worlds. This app creates a realistic swarm of animated butterflies with flapping wings and natural flight patterns.

## What it does

When you drop this app into your Hyperfy world, it will:
- Generate multiple animated butterflies with realistic wing flapping
- Distribute them randomly across a configurable area
- Apply random scales, rotations, and flight speeds
- Create natural-looking butterfly movement patterns
- Hide the original butterfly model (optional)


## UI Configuration Options

### Original Butterfly Visible
- **What it does**: Controls whether the original butterfly model is visible
- **Options**: True/False
- **Default**: True
- **Tip**: Set to False to hide the original model and only show the swarm

### Spawn Area
- **What it does**: Sets the size of the area where butterflies will spawn
- **Range**: 1 to 1000 meters
- **Default**: 10 meters
- **How it works**: Butterflies spawn randomly within a square area of this size
- **Tip**: Larger areas create more spread-out swarms

### Spawn Height
- **What it does**: Sets the maximum height where butterflies can spawn
- **Range**: 1 to 1000 meters
- **Default**: 10 meters
- **How it works**: Butterflies spawn between ground level (1m) and this height
- **Tip**: Higher values create more vertical distribution

### Butterfly Amount
- **What it does**: Controls how many butterflies are created
- **Range**: 1 to 5000 butterflies
- **Default**: 50 butterflies
- **Tip**: Higher numbers create denser swarms but may impact performance

### Scale Range
- **What it does**: Sets the minimum and maximum size for butterflies
- **Scale Min**: 0.1 to 10 (10% to 1000% of original size)
- **Scale Max**: 0.1 to 10 (10% to 1000% of original size)
- **Default**: Min 0.1, Max 0.5
- **Tip**: Use different min/max values for size variety

### Flap Speed Range
- **What it does**: Controls how fast the butterfly wings flap
- **Flap-speed Min**: 1 to 50 (flaps per second)
- **Flap-speed Max**: 1 to 50 (flaps per second)
- **Default**: Min 8, Max 15
- **Tip**: Higher values create faster wing movement

### Fly Speed Range
- **What it does**: Controls how fast butterflies move through the air
- **Fly-speed Min**: 0.1 to 20 (units per second)
- **Fly-speed Max**: 0.1 to 20 (units per second)
- **Default**: Min 0.1, Max 1
- **Tip**: Lower values create slower, more graceful movement

## How it works

1. **Spawn System**: Butterflies spawn randomly within the configured area and height
2. **Animation**: Each butterfly has independent wing flapping and movement
3. **Physics**: Butterflies move with realistic physics including drift and rotation
4. **Performance**: Uses efficient cloning and animation systems

## Usage Tips

1. **Performance**: Start with fewer butterflies (50-100) and increase as needed
2. **Area Planning**: Consider the relationship between spawn area and butterfly count
3. **Height Settings**: Use spawn height to create different flight patterns
4. **Scale Variety**: Different min/max scales create more natural-looking swarms

## Technical Details

- **Wing Animation**: Realistic sine-wave based flapping motion
- **Movement**: Random flight patterns with drift and rotation
- **Spawn System**: Random distribution within configured bounds
- **Performance**: Optimized for large numbers of butterflies

## Author

**Gert-Jan Akerboom**
- Twitter: [@GertJanAkerboom](https://x.com/GertJanAkerboom)
- License: MIT
- Copyright (c) 2025 Gert-Jan Akerboom 