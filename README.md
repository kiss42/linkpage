# linkpage

A personal link hub for Steven Pierre: a black and gold anime pass on a lanyard. Drag it, flip it, and the links are on the back.

## Files

- `index.html` is the whole site. GitHub Pages serves it as is.
- `src/page.html` is the same page without the `<html>` wrapper. It is what gets published as a Claude artifact.

## Publish with GitHub Pages

1. Open the repo's **Settings > Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Pick the **main** branch and the **/ (root)** folder, then **Save**.
4. After about a minute the site is live at https://kiss42.github.io/linkpage/

## Edit

- Links: the `LINKS` list near the top of the script.
- "Get your own pass" button: it opens the visitor's email app with a pre-filled message. The address is assembled in the `addr()` function when someone clicks, so it is never printed on the page.
