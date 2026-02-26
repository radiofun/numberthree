# numberthree

An interactive particle animation experiment built with React and HTML5 Canvas. The third iteration of the *Organic Particles* series and the basis for the Gemini-refined [numberthreegemini](https://github.com/radiofun/numberthreegemini) version.

## Overview

1,500 particles float across a full-screen dark canvas. Moving the mouse repels nearby particles, which then elastically return to their original positions. Clicking cycles through three color themes.

## Features

- **1,500 particle simulation** — each particle has its own position, velocity, and size
- **Mouse repulsion** — particles within 100 px of the cursor are pushed away
- **Elastic return** — particles spring back using lerp with return speed 0.008 and friction 0.95
- **Three color themes** — Nebula Fire, Oceanic Depth, Forest Spirit
- **Formation animation** — 4000 ms easeInOutCubic formation on load
- **Theme indicator** — frosted-glass overlay pill shows the current theme
- **Zero dependencies** — React 18 via CDN + Babel standalone

## Tech Stack

- **HTML / JavaScript** — single-file app (`index.html`)
- **React 18** — UI and state management (via CDN)
- **HTML5 Canvas** — 2D particle rendering

## Running Locally

Open `index.html` directly in any modern browser — no build step required.

```bash
open index.html
```
