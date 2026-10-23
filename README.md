# Mondrian-Art

A recreation of a Piet Mondrian style composition using pure HTML and CSS Grid. It is a small practice project for learning CSS Grid layout.

## Overview

The artwork is a fixed 748 x 748 pixel grid with a black background. The black gaps between grid items (`gap: 9px`) form the characteristic lines, and the blocks are coloured red, blue, yellow, near-black, and off-white. Column and row sizes are set explicitly with `grid-template-columns` and `grid-template-rows`, and individual blocks span cells using `grid-column`, `grid-row`, and `grid-area`. The composition is centred in the viewport with Flexbox.

## Contents

| Path | Description |
| --- | --- |
| `index.html` | The complete project: markup plus an embedded `<style>` block with the grid definition and colour classes. |

## Tech stack

- HTML5
- CSS3 (CSS Grid, Flexbox)

## Getting started

No dependencies or build step. Clone the repository and open `index.html` in a web browser.

```bash
git clone https://github.com/TIRK3Y/Mondrian-Art.git
cd Mondrian-Art
# open index.html in a browser
```

## License

No license has been specified for this project.
