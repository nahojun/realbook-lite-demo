# Third-Party Notices

This document lists the main third-party open-source software used to build or run the REALBOOK Lite public demo package.

REALBOOK-owned code, interface design, page stack interaction, page curl visual behavior, documentation, and distribution packaging are not third-party software and are not released under these third-party licenses.

## Runtime Dependencies Included in the Public Demo

| Package | Version checked locally | Purpose | License |
| --- | ---: | --- | --- |
| React | 19.2.7 | UI runtime | MIT |
| React DOM | 19.2.7 | Browser rendering | MIT |
| PDF.js / `pdfjs-dist` | 5.7.284 | PDF parsing and rendering | Apache-2.0 |
| Workbox | 7.4.1 | PWA service worker support | MIT |

## Build Tooling Used to Produce the Public Demo

These tools are used to build the static JavaScript distribution. They are not a license for REALBOOK-owned code.

| Package | Version checked locally | Purpose | License |
| --- | ---: | --- | --- |
| Vite | 6.4.3 | JavaScript build tool | MIT |
| `@vitejs/plugin-react` | 4.7.0 | React build integration | MIT |
| `vite-plugin-pwa` | 1.3.0 | PWA manifest and service worker generation | MIT |
| TypeScript | 5.9.3 | Type checking and build-time language tooling | Apache-2.0 |

## License Boundary

Third-party dependencies remain under their own license terms. REALBOOK Lite itself is governed by `LICENSE-DEMO.md`.

Do not confuse third-party permissions with permission to commercially use, repackage, redistribute, or white-label REALBOOK Lite.

## Source Notices

Before publishing a release, preserve upstream license texts in the private release archive or compliance record. Do not remove notices that are required by third-party licenses.

