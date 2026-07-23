# REALBOOK Lite

REALBOOK Lite is free for personal, educational, academic research, and individual non-commercial evaluation use. Commercial use requires a paid license.

Korean documentation: [README.ko.md](./README.ko.md)

REALBOOK Lite is a public demo and evaluation build of the REALBOOK reader interface. It opens local PDF files in the browser and provides a spatial reading surface with spread view, page stacks, page curl feedback, page thumbnails, PDF outline navigation, mouse zoom, Reading Lamp, and Previous / Next / Return controls.

This repository is a static JavaScript distribution package. It is not the REALBOOK source repository. TypeScript source files, internal development documents, tests, calibration data, replay traces, private package metadata, and source maps are intentionally not included.

## Usage

Open `index.html` through a static web server, GitHub Pages, or the SODEC website. Use **Open PDF** to select a local PDF from your device. The PDF is processed in your browser.

No Node.js runtime, backend server, database, OCR service, upload server, or PDF rendering server is required for deployment.

## Non-Commercial Use

You may use REALBOOK Lite for:

- Personal reading
- Education
- Academic or technical research
- Individual non-commercial evaluation

## Commercial Use Requires a Paid License

Commercial use requires a separate paid license from SODEC.

Commercial use includes, without limitation, company use, institutional use, internal review, internal testing, internal evaluation, proof-of-concept, R&D use, customer delivery, agency work, paid PDF publishing, paid reports, catalogs, brochures, brand books, WordPress plugin bundles, SaaS integration, white-label products, publishing platform integration, SDK use, resale, redistribution, and bundling REALBOOK Lite with a paid product or service.

See [COMMERCIAL_USE.md](./COMMERCIAL_USE.md).

## License

REALBOOK Lite is not released under MIT, Apache, BSD, GPL, or another open-source license. SODEC retains rights to REALBOOK-owned code, interface, visual behavior, documentation, and distribution packaging, except for third-party dependencies listed in [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md).

See [LICENSE-DEMO.md](./LICENSE-DEMO.md).

## Demo Distribution

The official demo may be provided through GitHub Pages or the SODEC website. Cloning, copying, redistributing, or deploying this package does not remove the license restrictions described in [LICENSE-DEMO.md](./LICENSE-DEMO.md) and [COMMERCIAL_USE.md](./COMMERCIAL_USE.md).

## Included Files

- README.md
- README.ko.md
- LICENSE-DEMO.md
- LICENSE-DEMO.ko.md
- COMMERCIAL_USE.md
- THIRD_PARTY_NOTICES.md
- index.html
- assets/
- manifest.webmanifest
- registerSW.js
- sw.js
- workbox-*.js
- icon-192.svg
- icon-512.svg

## Privacy

REALBOOK Lite opens local PDFs through the browser file picker. This static demo does not upload the selected PDF to a REALBOOK server.

## Third-Party Software

Third-party software remains under its own license terms. See [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md).

## Contact

Commercial inquiries: nahojun@sodec.co.kr
