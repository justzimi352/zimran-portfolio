# Zimran Arif — Portfolio

Personal portfolio site: medical student, media director, and student leader — work at the intersection of medicine, media, and technology.

**Live:** [zimranarif.netlify.app](https://zimranarif.netlify.app)

## Build

A single hand-written `index.html` — no framework, no build step, no dependencies beyond Google Fonts (Cormorant Garamond, Archivo). "Paper & ink" editorial system: cream paper base, ink chapters, burnished bronze accent. All layout and animation is plain CSS; the work grid degrades to a styled placeholder when a thumbnail is missing, so the page never renders broken.

Work thumbnails are JPEG (~350 KB total). They were PNGs in an earlier revision — do not reintroduce those, they were roughly 5× the weight for no visible gain.

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
