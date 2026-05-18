# Speian Space Group — Official Website

The official website for the Speian Space Group (SSG), a fictional space agency from a Kerbal Space Program playthrough.

Live site: [speian-space-group.vercel.app](https://speian-space-group.vercel.app)

---

## About

This site serves as the in-universe public face of the SSG. It covers the agency's mission, history, active programs, defense posture, shareholders, and long-term vision. The design uses a dark, editorial aesthetic with crimson and gold as primary colors, serif/condensed type pairing, and CSS-only animations.

---

## Tech Stack

- Pure HTML and CSS, no frameworks or build tools
- Single file: `index.html` (2,477 lines)
- Fonts via Google Fonts (Cormorant Garamond, Barlow Condensed, Barlow)
- Deployed on Vercel

---

## Structure

The page is divided into these sections:

- Hero with floating station visual
- Scrolling marquee bar
- Mission and stats
- History timeline (scroll-triggered)
- Programs grid (active and classified)
- Values and agency statement
- Shareholders and partners
- Defense record
- Vision roadmap

---

## Running Locally

No build step required. Open `index.html` directly in a browser.

```bash
git clone https://github.com/debug-cli/speianspacegroup-web.git
cd speianspacegroup-web
open index.html
```

Or serve it with any static file server:

```bash
npx serve .
```

---

## Deployment

The site deploys automatically to Vercel on push to `main`. No configuration needed beyond connecting the repo.

---

## Contributing

This is a personal/creative project tied to a specific KSP save. Issues and PRs are welcome for bug fixes or design improvements, but major content changes will stay lore-accurate to the playthrough.

---

## License

No license specified. All rights reserved by the author.
