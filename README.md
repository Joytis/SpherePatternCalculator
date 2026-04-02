# Sphere Cross-Section Calculator

A browser-based tool for calculating sphere geometry from a cross-sectional measurement, and generating sewing patterns for the resulting spherical cap.

> This project was generated with [Claude](https://claude.ai) (Anthropic).

## What it does

Given a circular cross-section of a sphere and its distance from the sphere's center, the calculator derives:

- **Sphere radius** and **equatorial circumference**
- A **sewing pattern** for the spherical cap above the cross-section — four equivalent curved gore panels that, when sewn together, reconstruct the cap

All inputs are in inches.

## Features

- Linked sliders for cross-sectional circumference, equatorial circumference, and distance from center — changing any value updates the others automatically
- Live SVG visualization of the sphere cross-section with the cap region highlighted in orange
- Sewing pattern canvas showing one gore panel with annotated dimensions:
  - Arc height, base width, seam length, apex angle
  - 3/8" seam allowance with cut line and sew line clearly marked
- Export pattern as PNG (screen resolution) or A4 print-ready PNG (150 DPI) with a 1-inch scale bar

## Usage

Open `index.html` directly in a browser — no build step or server required.

## Deployment

Hosted as a static site via GitHub Pages.
