# Assignment 2 — Flexbox and CSS Grid

**Student:** Adilzhan Kuandykov  
**Group:** SE-2526

A simple personal website made with HTML and CSS. All nine images were supplied by the student. No frameworks, JavaScript or build tools are required.

## Published website

- Website: https://adilzhandev.github.io/assignment2-frontend/
- Repository: https://github.com/adilzhandev/assignment2-frontend

## Pages

- `index.html` — Task 0: Flexbox navigation; Task 1: three equal-height hobby cards with images, titles, descriptions and button-style links.
- `layout.html` — Task 2: named Grid areas for the header, left sidebar, main content and footer.
- `gallery.html` — Task 3: nine images in a responsive Grid gallery. Hover or focus an image to reveal an overlay; select it to open the original.
- `portfolio.html` — Task 4: Flexbox navigation, a Grid projects/sidebar layout and Flexbox inside project cards.
- `style.css` — shared styles and responsive media queries.
- `images/` — the nine supplied photographs.

## Open locally

Open `index.html` directly in a browser, or run this command in the project directory:

```sh
python3 -m http.server 5173
```

Then open http://localhost:5173. Use the navigation links to visit all four pages.

## Responsive layout

The design uses CSS custom properties for colours, spacing and shadows, so the light palette is defined in one place at the top of `style.css`.

The gallery has three columns on desktop, two below 750px and one below 500px. The page layout and portfolio stack into one column below 750px. Navigation wraps, and the hobby cards stack on small screens.

## Publish with GitHub Pages

In the repository settings, select **Pages → Deploy from a branch**, then select the `master` branch and the `/ (root)` folder. Save and wait for deployment to finish.

