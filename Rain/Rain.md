# Rain - Hyperfy V2 App

A rain particle system for Hyperfy V2 worlds. This app creates dynamic rain effects with customizable physics and particle counts.

## What it does

When you drop this app into your Hyperfy world, it will:
- Generate realistic falling raindrops with physics
- Create a splash effect when raindrops hit surfaces
- Allow customization of rain intensity, area, and particle properties

Perfect for creating atmospheric weather effects, moody scenes, or adding environmental ambiance to your world.

## UI Configuration Options

### Move Cube
- **What it does**: Controls visibility of the positioning cube used to move the rain effect around the world
- **Options**: Show/Hide
- **Default**: Show
- **Tip**: Use the cube to position the rain where you want it, then hide it to only show the particle effects

### Max Particles
- **What it does**: Sets the maximum number of raindrops that can exist simultaneously
- **Range**: 1 to 5000 particles
- **Default**: 1000 particles
- **Step**: 50
- **Tip**: Higher numbers create denser rain but may impact performance

### Spawn Rate (per sec)
- **What it does**: Controls how many new raindrops are created per second
- **Range**: 1 to 3000 particles per second
- **Default**: 200 particles per second
- **Step**: 10
- **Tip**: Higher rates create more intense rainfall

### Rain Area (meters)
- **What it does**: Sets the radius of the rectangular area where rain falls
- **Range**: 1 to 300 meters
- **Default**: 20 meters
- **Step**: 1
- **How it works**: Rain spawns randomly within this rectangular area
- **Tip**: Larger areas create wider rain coverage

### Min Particle Size
- **What it does**: Sets the smallest possible size for raindrops
- **Range**: 0.01 to 0.1
- **Default**: 0.02
- **Step**: 0.01
- **Tip**: Smaller values create finer rain droplets

### Max Particle Size
- **What it does**: Sets the largest possible size for raindrops
- **Range**: 0.02 to 0.2
- **Default**: 0.05
- **Step**: 0.01
- **Tip**: Larger values create heavier rain drops

### Rain Physics

#### Min Speed
- **What it does**: Sets the slowest possible fall speed for raindrops
- **Range**: 1.0 to 10.0 units per second
- **Default**: 3.0
- **Step**: 0.5
- **Tip**: Lower values create slower, more gentle rain

#### Max Speed
- **What it does**: Sets the fastest possible fall speed for raindrops
- **Range**: 2.0 to 20.0 units per second
- **Default**: 6.0
- **Step**: 0.5
- **Tip**: Higher values create faster, more intense rain

#### Gravity
- **What it does**: Controls the gravitational force applied to raindrops
- **Range**: 0.5 to 5.0
- **Default**: 2.0
- **Step**: 0.1
- **Tip**: Higher values make raindrops fall faster and more realistically

## How it works

1. **Particle Pool**: Creates a pool of reusable raindrop meshes for performance
2. **Spawn System**: Continuously spawns new raindrops within the configured area
3. **Physics Simulation**: Applies gravity and movement to each raindrop
4. **Splash Effects**: Creates splash animations when raindrops hit surfaces
5. **Performance Optimization**: Efficient particle recycling and management

## Usage Tips

1. **Performance**: Start with lower particle counts (500-1000) and increase as needed
2. **Area Planning**: Consider the size of your scene when setting rain area
3. **Intensity**: Balance spawn rate with particle count for desired rain density
4. **Physics**: Adjust gravity and speed for different rain intensities (light drizzle vs heavy storm)
5. **Size Variation**: Use different min/max sizes for more realistic rain variation

## Technical Details

- **Particle System**: Efficient pool-based particle management
- **Physics**: Realistic gravity and movement simulation
- **Splash Effects**: Dynamic splash animations on impact
- **Performance**: Optimized for large numbers of particles

## Rain Effects

### Light Rain
- **Particles**: 500-1000
- **Spawn Rate**: 100-200 per second
- **Speed**: 2-4 units per second
- **Size**: 0.02-0.04

### Moderate Rain
- **Particles**: 1000-2000
- **Spawn Rate**: 200-400 per second
- **Speed**: 4-8 units per second
- **Size**: 0.03-0.06

### Heavy Rain
- **Particles**: 2000-5000
- **Spawn Rate**: 400-1000 per second
- **Speed**: 6-15 units per second
- **Size**: 0.04-0.1

## Author

**Gert-Jan Akerboom**
- Twitter: [@GertJanAkerboom](https://x.com/GertJanAkerboom)
- License: MIT
- Copyright (c) 2025 Gert-Jan Akerboom 