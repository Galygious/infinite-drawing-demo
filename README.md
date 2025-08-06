# Infinite Drawing Demo

An interactive visualization that allows you to zoom through the scales of the universe while drawing at any scale. This demo combines a cosmic scale viewer with a multi-tier drawing system that adapts to your current zoom level.

## Features

- **Cosmic Scale Navigation**: Zoom from the Planck length to the observable universe
- **Multi-Tier Drawing System**: Draw at 5 different scales that automatically adapt to your zoom level
- **Scale-Aware Brush**: Brush size scales with zoom to maintain consistent visual appearance
- **Persistent Strokes**: Your drawings remain visible across zoom transitions
- **Wikimedia Image Integration**: Real images from Wikimedia Commons for each scale

## Controls

### Drawing
- **Left Mouse**: Draw on the canvas
- **Keys 0-4**: Switch between drawing tiers
- **`[` and `]`**: Decrease/increase brush size
- **`U`**: Undo last stroke in current tier
- **`C`**: Clear all strokes in current tier

### Navigation
- **Mouse Wheel**: Zoom in/out through the scales

## Technical Details

The demo uses a five-tier coordinate system where each tier represents approximately 13 orders of magnitude:
- **Tier 0**: Planck scale (quantum)
- **Tier 1**: Atomic scale
- **Tier 2**: Planetary scale
- **Tier 3**: Stellar scale
- **Tier 4**: Galactic scale

The drawing system automatically selects the appropriate tier based on your current zoom level, ensuring your strokes are always visible and properly scaled.

## Getting Started

Simply open `index.html` in a modern web browser. The demo will automatically load images from Wikimedia Commons and you can start drawing immediately.

## Browser Compatibility

Requires a modern browser with support for:
- Canvas 2D API
- Pointer Events
- ES6+ JavaScript features
- CORS-enabled image loading
