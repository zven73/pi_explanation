# Universe of Pi

Interactive educational web app demonstrating 8 ways to understand the number Pi through visualizations and real-time animations.

## Simulations

1. **Rolling Wheel** — circumference unrolling shows C = pi * d
2. **Archimedes' Method** — inscribed/circumscribed polygons squeeze Pi (up to 500 sides)
3. **Monte Carlo** — click to throw darts, estimate Pi from hit ratio
4. **Buffon's Needle** — matchstick drops on a ruled floor approximate 2/pi
5. **Pizza Pi** — slicing a circle into a rectangle proves S = pi*R^2
6. **Onion Method (Kepler)** — unrolling concentric rings into a triangle
7. **Block Collisions** — elastic collisions count digits of Pi (mass ratios 1:1, 100:1, 10000:1)
8. **Infinite Series** — Leibniz and Nilakantha series converge to Pi on a live graph

## Features

- Light/dark theme toggle
- Sound effects (Web Audio API)
- Retina/HiDPI canvas support
- Lazy animation via IntersectionObserver (only visible simulations run)
- Fully self-contained single HTML file — no build step, no dependencies

## Live Demo

View it here: https://zven73.github.io/pi_explanation/

## License

MIT
