# Kids Activity Spinner — "I'm Bored!" Wheel

A zero-infrastructure, single-file HTML web application designed to help kids (specifically tailored for an 8-year-old boy) beat boredom. By gamifying activity selection with a colorful spinning wheel and celebratory confetti, it encourages screen-free, creative, and active play.

## 🎡 Features

- **HTML5 Canvas Spinning Wheel**: Dynamically draws colorful segments for all activities with auto-wrapped text.
- **Realistic Spin Easing**: Utilizes physics-based angular deceleration (`requestAnimationFrame`) for a realistic slowing down feel, accompanied by physical pointer bumping animations.
- **Vibrant Confetti Celebrations**: Features a custom 2D canvas particle-simulation confetti shower when the wheel stops.
- **Dynamic Activity Customization**: Includes a slide-up options drawer to add, delete, or reset activities directly from the browser.
- **Local Persistence**: Saves all your custom activity lists inside browser `localStorage` so changes persist across refreshes.
- **Mobile First & PWA-Lite**: Optimized for mobile viewports, touch-friendly tap targets, and supports adding to the device home screen for a native feel.

## 🚀 How to Run

Since the application requires no backend or build steps, you can run it instantly:

1. **Directly in Browser**:
   Open the [index.html](index.html) file directly in any modern desktop or mobile browser.
   
2. **Local HTTP Server**:
   If you want to test PWA features or access it via your local network, start a web server in the directory:
   ```bash
   # Python 3
   python3 -m http.server 8080
   
   # Node.js
   npx http-server -p 8080
   ```
   Then open `http://localhost:8080` in your browser.

## 📝 Curated Starter Activities

The app is pre-seeded with 20 engaging activities suitable for an 8-year-old boy:
- Build a LEGO fortress
- Draw a comic book page
- Design a new superhero
- Build a blanket fort
- Set up an indoor obstacle course
- Make paper airplanes & fly them
- Have a 1-minute dance party
- Do a scavenger hunt
- Play a card or board game
- Read a chapter of a book
- Do a science experiment
- Do 20 jumping jacks
- Draw with sidewalk chalk
- Make a cardboard box creation
- Solve a puzzle
- Learn a magic trick
- Play catch or bounce a ball
- Write a short funny story
- Do some origami folding
- Go on a nature walk outside

## 🛠️ Technology Stack

- **Markup & Layout**: Semantic HTML5
- **Styling**: Vanilla CSS3 (Custom Variables, Flexbox, Keyframes, Backdropl Filters, Responsive Scale)
- **Logics & Physics**: Vanilla JavaScript (Canvas API, requestAnimationFrame, localStorage)
