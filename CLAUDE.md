# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Interactive educational web app (in Russian) demonstrating ways to understand the number Pi through visualizations and animations. Pure static HTML — no build tools, no package manager, no server required.

## Architecture

- **index.html** — original version: 7 interactive Pi simulations (rolling wheel, Archimedes polygons, etc.) using Tailwind CSS CDN, Canvas API, and inline JS. Dark theme only.
- **2222.html** — enhanced version: 8 simulations with light/dark theme toggle, sound toggle, and improved styling. Same stack.

Both files are fully self-contained single-file apps (HTML + CSS + JS inlined). No external JS dependencies beyond the Tailwind CDN.

## Development

Open either HTML file directly in a browser — no build step needed. All interactive simulations use `<canvas>` elements with vanilla JS `requestAnimationFrame` loops.

## Key Conventions

- Language: all UI text is in Russian
- Styling: Tailwind CSS via CDN (`cdn.tailwindcss.com`)
- Math rendering: CSS class `.math-font` for formulas (Cambria Math / Times New Roman)
- Canvas sizing: each simulation has its own canvas with hardcoded dimensions
- Animations: driven by `requestAnimationFrame`, controlled via inline `<script>` blocks at the bottom of each file
