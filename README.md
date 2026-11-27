# GEOMETRYRUNSU!

A self-contained rhythm runner: Geometry Dash-style jumps + timing notes + combo scoring.

## Play locally
Open `index.html` in a modern browser. No build step, dependencies, or server required.

## Controls
- **Space / ↑ / W** — jump over obstacles
- **F** — hit the note nearest the timing line
- **P / Esc** — pause or resume
- **Pointer / touch** — tap a note, or tap the left side of the game field to jump
- Mobile buttons are available below the game field.

## Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. The included workflow deploys the site automatically after pushes to `main`. You can also start it from the **Actions** tab.
4. The published address will appear in the **Settings → Pages** section. It normally follows the form `https://larpewryipewr.github.io/geometryrunsu/`.

The game is a single HTML file and uses Canvas + Web Audio API. The best score is saved in browser local storage.
