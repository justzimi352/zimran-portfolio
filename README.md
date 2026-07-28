# Zimran Arif — Portfolio

Personal portfolio site: medical student, media director, and student leader — work at the intersection of medicine, media, and technology.

**Live:** [zimranarif.netlify.app](https://zimranarif.netlify.app)

## Build

A single hand-written `index.html` — no framework, no build step, no dependencies beyond Google Fonts (Bebas Neue, Archivo, JetBrains Mono). All layout and animation is plain CSS; the work grid degrades to a styled placeholder when a thumbnail is missing, so the page never renders broken.

## Structure

```
index.html          the whole site
assets/             work thumbnails (work-1…5)
```

`assets/README.txt` documents which thumbnail maps to which project card.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```
