# html-3d-template

Bahasa Indonesia version: [readme.id.md](readme.id.md)

Self-contained HTML template with Three.js + CSS 3D elements — a starting point for web projects.

## Features

- A single self-contained `index.html` file — no build step and no dependencies to install
- Full-viewport Three.js scene (Three.js r128 via CDN): an animated icosahedron with ambient and directional lighting
- CSS 3D elements: a spinning cube (`.scene` / `.cube`) with a 12-second rotation animation
- Theme colours via CSS variables in `:root`, with automatic light/dark mode from `prefers-color-scheme`

## Usage

Open `index.html` in a browser (an internet connection is needed to load Three.js from the CDN).

To start a new project from this template, copy `index.html` and edit it: change the theme colours in the `:root` CSS variables, replace the Three.js geometry/material, or add your own content to the CSS 3D section.

## Project Structure

```
index.html  # the whole template: styles, Three.js scene, and CSS 3D elements
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file.
