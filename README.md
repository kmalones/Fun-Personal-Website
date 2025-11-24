# Fun-Personal-Website


This folder contains the source files for a simple personal/home page used for INST377 assignment work.

## What’s in this folder

- `home.html` — The main page for the assignment (view this in a browser).
- `home.css` — Stylesheet for the page (updated to a modern, responsive design).
- `contact_page.html`, `contact.css` — Contact page assets.
- `games.html`, `games.css` — Example pages used in the assignment.
- `success_form_page.html` — A success page shown after form submission.

## How to view locally

Option 1 — Open the HTML file directly in your browser:

- Double-click `home.html` or right-click and choose "Open With → Browser".

Option 2 — Run a tiny local HTTP server (recommended for consistent behavior):

If you have Python 3 installed, run from the `Assignment 1` directory:

```bash
# macOS / zsh
python3 -m http.server 8000
```

Then open `http://localhost:8000/home.html` in your browser.

## Notes about the stylesheet

- `home.css` has been restyled to be responsive and use a simple two-column layout on larger screens.
- It uses CSS variables for color theming — tweak values in the `:root` at the top of the file to change colors globally.
- The layout avoids float-based positioning and uses flexbox for better responsiveness.

## Customization ideas

- Replace fonts by adding a web font link in the HTML head (e.g., Google Fonts).
- Add images to the hero area or within subsections to make the page more visual.
- Add more semantic HTML (sections, article) for accessibility improvements.

## Running checks

- To preview your changes, edit `home.css` and refresh the browser.
- If you want me to further update the page (color palette, fonts, or add a navigation highlight), tell me which direction you'd like (minimal changes, modern/flat, playful, or professional).

---

If you want, I can also:

- Add a small `README` to the project root instead.
- Commit these changes to git with a descriptive message.
- Apply a consistent font via Google Fonts and update the HTML head.

Tell me what you'd like next.

