# Rounded Corners POC

An interactive proof-of-concept demonstrating the mathematical relationship between parent and child border-radius values in nested containers.

## Overview

This POC showcases how child elements should calculate their border-radius based on their parent container's border-radius and padding to create visually harmonious nested rounded corners.

## Formula

```
child_radius = max(0, parent_radius - padding)
```

This formula ensures that the curves of nested elements align perfectly, creating a smooth, continuous visual flow.

## Features

- 🎚️ Interactive sliders to adjust parent border radius (0-100px)
- 📏 Adjustable padding/gap between elements (0-50px)
- 🎨 Real-time visual updates
- 📱 Responsive design that works on mobile and desktop
- 🧮 Live calculation display for each child element

## Usage

Simply open `index.html` in your web browser. No build process or dependencies required!

## Demo

The POC includes:
- A large parent container with adjustable rounded corners
- 4 child elements arranged in a 2x2 grid
- Each child element displays its calculated border-radius value
- Interactive controls to experiment with different values

## How It Works

When you have a container with rounded corners and padding, the inner elements should have a border radius equal to the parent's radius minus the padding. This creates a visually harmonious nested effect where the curves align perfectly.

Try it yourself by adjusting the sliders and watching how the child elements automatically adapt!

