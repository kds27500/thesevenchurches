# The Seven Churches of Revelation — Digging Deeper

Interactive teaching prototype. React + Vite, designed for Netlify.

## Run
npm install
npm run dev

## Build
npm run build

## Prototype
Ephesus and Smyrna: Past, Present, Prophecy panels; guided navigation; discussion prompts; mobile responsiveness.

Scene images, video and narration are pending integration. All biblical figure portraits are artistic representations. Historicist prophetic interpretations are identified as interpretations.

Netlify: build command npm run build; publish dist.

## Ephesus locked-content integration (draft)
The approved Ephesus JSON and schema are preserved byte-for-byte in `efiles/repo_files_for_github.zip`. The build extracts them without rewriting or shortening research.

Run:
```sh
npm install
npm run prepare:content
npm run dev
npm run build
```
The build script automatically extracts the approved archive before Vite builds. The archive also supplies `vite.config.js` with `base: './'`.

Four lenses, 12 scenes, Class Path, evidence reveals, labeled teaching points, claims/sources, research panels, and BibleGateway Scripture links are implemented. Cinematic images and MP4 files are NOT yet installed; visible content-needed placeholders are intentional.

Offline: The JavaScript application and JSON are bundled locally. External BibleGateway links require internet, and missing video/images cannot be played. A complete offline browser test remains outstanding.
