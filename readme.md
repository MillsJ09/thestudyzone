# Study Hub

Modern, data-driven site for hosting education PDFs across Geography, Physics, and Maths.

## Structure
- Home and subject pages in `index.html` and `subjects/`.
- Content PDFs in `content/{subject}/{notes|questions}`.
- Data registry in `assets/js/data.js`.
- Styles in `assets/css/styles.css`.

## Add resources
1. Drop your PDF in the appropriate `content` folder.
2. Add an entry in `assets/js/data.js` with the title, file path, tags, and level.

## Develop locally
Open `index.html` in a browser or serve with any static server.

## Deploy
Enable GitHub Pages in the repository settings and use the `main` branch, root.