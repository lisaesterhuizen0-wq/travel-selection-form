# Travel Selection Form

A single-page travel-options selector built during a RAY AI bootcamp exercise. The user picks from curated options across multiple sections (flights, hotels, activities), and the form composes a summary email of the choices and opens it in the user's mail client via `mailto:`.

**Live demo:** https://lisaesterhuizen0-wq.github.io/travel-selection-form/

## Why I built this

The bootcamp scenario was about capturing a busy executive's input efficiently. Give them a clean list of pre-vetted options to pick from, and make the "send your selections back" step take one tap. The `mailto:` send keeps the whole thing portable: no backend, no auth, no third-party form service.

## What's in this repo

- `index.html`: a self-contained page (HTML + inline React via CDN, no build step). Trip options live in a config object near the top of the file, so the form can be retargeted to a new trip by editing one block.

## Tech

- HTML
- React 18 (loaded inline via CDN, no build tooling)
- `mailto:` for the "send selections" handoff

## How to view locally

Open `index.html` in any browser, or visit the live demo link above.

## Notes

Trip data and the destination email (`assistant@example.com`) are placeholders. Swap them in the config block near the top of `index.html` to retarget the form to a real trip.

---

*Part of my AI automation & enablement portfolio (github.com/lisaesterhuizen0-wq)*
