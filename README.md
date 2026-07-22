# REALBOOK Lite

REALBOOK Lite is free for personal, educational, research, and non-commercial use. Commercial use requires a paid license.

Korean documentation: [README.ko.md](./README.ko.md)

REALBOOK Lite is a public demo and evaluation build of the REALBOOK reader interface. It opens local PDF files in the browser and provides a spatial reading surface with spread view, page stacks, page curl feedback, page thumbnails, PDF outline navigation, mouse zoom, Reading Lamp, and Previous / Next / Return controls.

This repository is a static JavaScript distribution package. It is not the REALBOOK source repository. TypeScript source files, internal development documents, tests, calibration data, replay traces, private package metadata, and source maps are intentionally not included.

## Usage

Open `index.html` through a static web server or GitHub Pages. Use **Open PDF** to select a local PDF from your device. The PDF is processed in your browser.

No Node.js runtime, backend server, database, OCR service, upload server, or PDF rendering server is required for deployment.

## Non-Commercial Use

You may use REALBOOK Lite for:

- Personal reading
- Education
- Research
- Non-commercial evaluation
- Non-commercial individual evaluation

## Commercial Use Requires a Paid License

Commercial use requires a separate paid license from SODEC.

Examples include company use, institutional use, internal review, internal testing, internal evaluation, proof-of-concept, R&D use, customer delivery, agency work, paid reports, catalogs, brochures, brand books, WordPress plugin bundles, SaaS integration, white-label products, publishing platform integration, SDK use, resale, and redistribution.

See [COMMERCIAL_USE.md](./COMMERCIAL_USE.md).

## License

REALBOOK Lite is not released under MIT, Apache, BSD, GPL, or another open-source license. SODEC retains rights to the REALBOOK code, interface, visual behavior, documentation, and distribution package except for third-party dependencies listed in [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md).

See [LICENSE-DEMO.md](./LICENSE-DEMO.md).

## GitHub Pages Deployment

1. Create a public repository named `realbook-lite` or `realbook-lite-demo`.
2. Copy the contents of this folder to the repository root.
3. Commit and push to GitHub.
4. In GitHub, open **Settings -> Pages**.
5. Select **Deploy from a branch**.
6. Select the `main` branch and `/root`.
7. Open the generated GitHub Pages URL.

The package uses relative asset paths so it can run from a GitHub Pages project path such as:

```text
https://OWNER.github.io/realbook-lite-demo/
```

## Included Files

```text
README.md
README.ko.md
LICENSE-DEMO.md
LICENSE-DEMO.ko.md
COMMERCIAL_USE.md
THIRD_PARTY_NOTICES.md
index.html
assets/
manifest.webmanifest
registerSW.js
sw.js
workbox-*.js
icon-192.svg
icon-512.svg
```

## Privacy

REALBOOK Lite opens local PDFs through the browser file picker. This static demo does not upload the selected PDF to a REALBOOK server.

## Third-Party Software

Third-party software remains under its own license terms. See [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md).



## Contact

Commercial inquiries: nahojun@sodec.co.kr
