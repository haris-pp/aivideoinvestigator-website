# AI Video Investigator: product website

Showcase page for **AI Video Investigator**, a video recorder with AI search that runs entirely on one PC
(C++ / Qt 6, YOLOv8 on ONNX Runtime, CLIP visual search, local LLM, WebRTC live view, FFmpeg, SQLite).

Live site: https://haris-pp.github.io/aivideoinvestigator-website/

The application's source code is private; this repository only holds the website.

## Contents

- `index.html`: the whole page (inline CSS and JS, no build step).
- `assets/video/`: the 1-minute demo (plays in the hero), the full 1 min 41 s tour and its poster.
- `assets/og.jpg`: link preview image (1200x630).
- `screenshots/`: dashboard screenshots taken from the running app in demo mode (`*-crop.jpg`: the part shown on the page).
- `assets/fonts/`: Manrope and DM Mono, served from this site (SIL Open Font License, licence files alongside).

## Publishing

GitHub Pages, branch `main`, folder `/` (root). `.nojekyll` makes Pages serve the files as they are.

## Credits

Demo footage: contains video from the MEVA dataset by Kitware Inc. and IARPA (https://mevadata.org),
CC BY 4.0. Clips cut and re-encoded. The People and face screenshots contain video from Intel IoT DevKit
sample-videos (https://github.com/intel-iot-devkit/sample-videos), CC BY 4.0, re-encoded.

The number plate footage used in testing isn't cleared for publishing, so no picture of it is on the site.

© 2026 Haris P P
