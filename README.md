# Brick AI Static Prototype

Static HTML prototype for a Brick AI recommendation flow and property detail experience. The project is GitHub Pages compatible and uses only plain HTML, CSS, and a small amount of inline JavaScript.

## Structure

- `brick-recommendation-ui.html`: recommendation list page with responsive cards, mobile sticky actions, and Decision Dock.
- `property-detail.html`: property detail page with hero media, recommendation breakdown, risk cards, and CTA block.

## Local Run

Open either HTML file directly in a browser, or serve the folder with a simple static server.

Examples:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/brick-recommendation-ui.html`.

## Notes

- No build step.
- No framework dependencies.
- Suitable for GitHub Pages by publishing the repository root.
