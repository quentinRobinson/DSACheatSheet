# C# DSA Pattern Recognition Cheat Sheet

An interactive, single-page study desk for recognizing common data structures and algorithms patterns in C#. It combines quick-reference material, reusable code templates, practice problems, and video walkthroughs in one self-contained HTML page.

## Features

- Pattern recognition matrix with signals, C# tooling, complexity, and common traps
- Constraint triage and a rapid decision tree
- C# collections and syntax reference
- Reusable templates for sliding windows, two pointers, BFS, dynamic programming, and more
- Search and pattern-based filtering
- Collapsible, syntax-highlighted code samples
- Practice checklists with progress saved in `localStorage`
- Light and dark themes
- Responsive sidebar navigation for desktop and mobile

## Run Locally

No installation or build step is required. Open `index.html` in a browser.

For a local HTTP server, run one of the following commands from the repository root:

```powershell
python -m http.server 8000
```

or:

```powershell
npx serve .
```

Then visit `http://localhost:8000` (or the URL printed by `serve`).

## Project Structure

```text
.
|-- index.html   # Content, styles, and client-side behavior
`-- README.md
```

## Notes

- Prism.js is loaded from jsDelivr for C# syntax highlighting, so highlighting requires an internet connection.
- Practice links and video walkthroughs point to external sites.
- Practice progress is stored only in the current browser under the `dsa-practice-completed` key.
- The initial theme follows the operating system preference. It can also be set with `?scoutTheme=light` or `?scoutTheme=dark`.

## Customization

All content and behavior live in `index.html`. Edit the HTML sections to add study material, the CSS variables near the top to adjust the theme, and the final script block to change interactions.