# Yushinkai Project

## Overview
This repository contains a lightweight static web project for Yushinkai content, with a primary landing page and a dedicated training page styled through a shared CSS file.

## Page descriptions
- `index.html`: Main entry page for the site and high-level navigation.
- `training.html`: Training-focused page for class/practice details and drill content.
- `styles.css`: Global stylesheet shared by all pages.
- `images/*`: Image and icon assets consumed by pages/components.

## Local open instructions
Because this is a static site, you can open files directly in a browser or run a simple local server.

### Option 1: Direct open
1. Open `index.html` in your browser.
2. Navigate to `training.html` using in-page links or direct file open.

### Option 2: Local server (recommended)
From the repository root:

```bash
python3 -m http.server 8000
```

Then visit:
- `http://localhost:8000/index.html`
- `http://localhost:8000/training.html`

## Asset credits
- `images/*`: Add each asset's author/source URL and license here as assets are introduced.

Example credit format:
- `images/dojo-hero.jpg` — Photo by <Name>, <Source URL>, License: <License name>.

## Refactor follow-up note (400+ line rule)
No files currently exceed ~400 lines. If any file grows beyond this threshold, split by concern:
- HTML: extract repeated sections into reusable includes/components (if build tooling is introduced).
- CSS: split into base/layout/components files and keep a clear import order.
