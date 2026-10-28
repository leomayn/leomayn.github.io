# Leo Maynard-Zhang's website

A static GitHub Pages website adapted from [Jon Barron's academic website](https://github.com/jonbarron/jonbarron.github.io).

Edit `index.html` for the homepage and `stylesheet.css` for the shared layout. The homepage includes the biography, research interests, publications, and teaching. Keep the publication and teaching content in `publications.html` and `teaching.html` in sync with the homepage; those URLs are retained for existing links.

The `.jemdoc` files, `MENU`, `MENU.html`, and `jemdoc.css` are legacy sources retained for reference. The site now uses hand-edited HTML; running jemdoc would overwrite the new layout.

To preview locally, run `python3 -m http.server 8000 --bind 127.0.0.1` from this directory and open http://127.0.0.1:8000. No build step or JavaScript is required. Lato loads from Google Fonts, with system font fallbacks.
