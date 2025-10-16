# cosmic-doodle-board

## Summary

Create a mesmerizing Cosmic Doodle Board - draw constellations with your mouse and watch them come alive!

✨ THE MAGIC:
As you drag your mouse across the screen, you paint with glowing stars that twinkle, pulse, and connect with thin constellation lines. It's like painting the night sky.

🌌 VISUAL DESIGN:
- Deep space background: dark blue to black gradient with distant tiny stars
- When you drag mouse: leave a trail of glowing stars (like painting with light)
- Stars you create are larger, colorful, and pulse/twinkle
- Thin glowing lines automatically connect stars as you draw (creating constellations)
- Stars have different colors: white, blue, pink, purple, golden (random)
- Glow effects around each star
- Smooth particle trails follow cursor while drawing

🎨 DRAWING:
- Hold mouse down and drag to draw with stars
- Stars appear along the path you drag (not just one per click)
- Each star twinkles independently with CSS animation
- Lines connect the stars in the order you drew them
- Release mouse to finish current constellation
- Start dragging again to begin a new constellation

🎮 INTERACTIONS:
- Click and hold to draw constellation
- Release to finish constellation  
- Space bar: Clear canvas and start fresh
- C key: Cycle through color themes (cosmic purple, ocean blue, sunset pink, golden)
- Hover near your stars to make them glow brighter

💫 MINIMAL UI (elegant overlay):
- Top center: "Draw your own cosmos" (fades after 3s)
- Bottom right corner: 
  * "Clear (Space)" button
  * Star count: "⭐ 47 stars"
- Color theme indicator (small color dot in corner)

🎪 BONUS EFFECTS:
- Cursor has a glowing trail while drawing
- Stars pulse at slightly different rates (natural feel)
- Constellation lines have subtle glow
- Optional: shooting stars occasionally cross the background
- When you clear, stars explode outward with animation

🌠 STARTING STATE:
- Empty cosmic canvas
- Maybe one example constellation already drawn (like Big Dipper)
- Prompt appears: "Click and drag to paint with stars ✨"

Vibe: Magical, creative, satisfying, like you're an artist painting the universe. Super chill and mesmerizing.

## Features

This application was automatically generated to meet the following requirements:

- Page uses Bootstrap 5 for UI
- Dark cosmic gradient background
- Click and drag creates trail of stars
- Stars twinkle and pulse with animation
- Lines connect stars in draw order
- Stars have multiple colors (white/blue/pink/purple/gold)
- Glow effects on stars and lines
- Space bar clears canvas
- C key cycles color themes
- Shows star count
- Has Clear button
- Cursor has glowing trail while drawing
- Release mouse finishes constellation
- New drag starts new constellation
- Smooth animations at 60fps
- Stars glow brighter on hover
- Responsive full-screen canvas

## Setup

This is a static web application that requires no build process.

### Local Development

1. Clone this repository
2. Open `index.html` in a web browser
3. Or serve with a local server:
   ```bash
   python -m http.server 8000
   ```


## Usage

Simply open the `index.html` file in a modern web browser. The application includes:
- Bootstrap 5 for responsive design
- Inline JavaScript for functionality
- Embedded data for attachments

## Code Explanation

### HTML Structure
- Uses semantic HTML5 elements
- Bootstrap components for UI
- Responsive design that works on all devices

### JavaScript Functionality
- Handles user interactions
- Processes data from attachments
- Updates DOM elements dynamically
- Includes error handling

### Styling
- Bootstrap 5 framework
- Custom CSS for specific requirements
- Mobile-first responsive design

## Deployment

This application is deployed on GitHub Pages and accessible at the URL provided in the repository settings.

## License

MIT License - See LICENSE file for details

## Auto-Generated

This application was automatically generated using AI-powered code generation.
Generated on: cosmic-doodle-board
