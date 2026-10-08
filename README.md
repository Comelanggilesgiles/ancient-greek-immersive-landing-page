# The Greek World

An immersive, scroll-driven journey through Ancient Greece, built with plain HTML, CSS and JavaScript.

![Screenshot placeholder](docs/screenshot.png)

> Replace `docs/screenshot.png` with a real screenshot of the page (see "Add your screenshot" below).

## About

The Greek World is a single-page, cinematic landing page that teaches the story of Ancient Greece through scrolling. Visitors move through 12 sections covering history, an interactive timeline, the city-states, philosophy, mythology, architecture, wars, Alexander the Great and the legacy of Greece. There is no framework and no build step: open it in a browser and it runs.

## Key Features

- Cinematic hero section with parallax layers and atmospheric particles
- Scroll-driven storytelling using `IntersectionObserver` and `requestAnimationFrame`
- Interactive timeline with live content transitions (vertical on small screens)
- Athens vs Sparta side-by-side comparison with an animated divider
- Scroll-expanding campaign map for Alexander the Great
- Animated counters, staggered reveals and text-reveal effects
- Magnetic buttons, custom cursor, gold glow accents and a scroll progress bar
- Full-screen animated mobile menu
- Accessibility: skip link, keyboard navigation, visible focus states and `prefers-reduced-motion` support
- Responsive layouts designed for both desktop and mobile

## Quick Start (about 5 minutes)

### Requirements

- Any modern browser (Chrome, Edge, Firefox or Safari)
- An internet connection (fonts and photos load from Google Fonts and Pexels)
- Optional: Git, and either Python 3 or Node.js to run a local server

### 1. Get the code

```bash
git clone https://github.com/Comelanggilesgiles/ancient-greek-immersive-landing-page.git
cd ancient-greek-immersive-landing-page
```

No Git? Download the repository as a ZIP from GitHub, unzip it and open the folder.

### 2. Run it

Choose one option.

**Option A: open the file directly**

Double-click `index.html`.

**Option B: local server with Python**

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

**Option C: local server with Node.js**

```bash
npx serve .
```

Then open the address shown in the terminal.

### 3. Explore

- Scroll down to move through the story.
- Use the top navigation (or the menu button on mobile) to jump to a section.
- Click the timeline entries to change the displayed era.

## Project Structure

```
.
├── index.html        # Markup for all 12 sections
├── css/
│   └── style.css     # Design tokens, layout and animations
├── js/
│   └── script.js     # Scroll engine, observers and interactions
└── README.md
```

## Customize

- Text and sections: edit `index.html`
- Colors, fonts and spacing: edit the design tokens at the top of `css/style.css`
- Behavior and animation: edit `js/script.js`
- Photos: replace the Pexels image URLs in `index.html` with your own files or links

## Add Your Screenshot

1. Open the page in your browser and take a screenshot.
2. Create a `docs` folder in the project and save the image as `docs/screenshot.png`.
3. Commit and push it. The image at the top of this README will appear automatically.

## Tech Stack

- HTML5 (semantic markup)
- CSS3 (custom properties, grid, flexbox, animations)
- JavaScript (vanilla, ES6+)
- Google Fonts: Cinzel, Cormorant Garamond, Inter
- Photography from Pexels (hot-linked)

## Browser Support

Latest versions of Chrome, Edge, Firefox and Safari.

## Credits

Photos are provided by [Pexels](https://www.pexels.com) and remain the property of their respective photographers.
