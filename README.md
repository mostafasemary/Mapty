`logo.png`

# Mapty

Mapty is a small training project It demonstrates a workout-tracking UI with a Leaflet map. This repository contains the starter files (HTML, CSS, JS) you can use to build the full app.

## Demo

- Open `index.html` in your browser, or serve the folder with a simple HTTP server (recommended) and visit `http://localhost:8000`.

## Features (starter)

- Map area prepared using Leaflet (CDN scripts/styles included in `index.html`).
- Sidebar UI with a hidden form to add workouts (distance, duration, cadence/elevation).
- Responsive layout and basic styling in `style.css`.

## Setup

No build tools or package manager are required for the starter. The project uses CDN versions of Leaflet.

Recommended ways to run locally:

1. Open directly in a browser (double-click `index.html`).
2. Serve via a static server (recommended to avoid some browser restrictions):

   - With Python 3 (from project folder):

     ```
     python -m http.server 8000
     ```

   - Then open `http://localhost:8000` in your browser.

## Usage

- Click on the map (once the map is initialized) to trigger the workout form.
- Choose a workout type (running or cycling), fill the fields and submit to create a workout entry and a map popup (full behavior is implemented in the course solution).

Note: This is the starter template — some interactive behavior (initializing the map, handling form submissions, storing workouts) is implemented in the course solution. Use `script.js` to implement the app logic as you follow the course.

## File Structure

- `index.html` : Main HTML file, includes Leaflet and `script.js`.
- `style.css` : Styles for the sidebar, form and map.
- `script.js` : Starter JavaScript file (app logic goes here).
- `logo.png`, `icon.png` : Assets referenced by `index.html`.

## Built With

- Leaflet (via CDN) — interactive maps.
- Vanilla HTML/CSS/JavaScript — no frameworks in the starter.

## Credits

This starter comes from the course by Jonas Schmedtmann. The sidebar copy in `index.html` references the course author; please keep that credit.

## License

This repository is provided for learning purposes. Check the course terms and respect the original author's rights. If you add your own content, choose an appropriate license.
