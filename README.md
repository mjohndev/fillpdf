# FillPDF.app

Fill a PDF online free — right in the browser. Add text, checkmarks,
dates, signatures, highlights, shapes and images, then download the
completed PDF.

## Local development

Just open `index.html` in a browser, or run a local server:

    python3 -m http.server 8000

Then visit http://localhost:8000

## Deployment

This site is deployed on GitHub Pages from the `main` branch.

## Pages

- `index.html`   — Main app
- `privacy.html` — Privacy Policy
- `terms.html`   — Terms of Service
- `404.html`     — Custom 404 page

## Configuration

- **Google Analytics:** replace `G-XXXXXXXXXX` in `index.html` with your real GA4 ID.
- **Search Console:** replace `YOUR_VERIFICATION_CODE` in the `<meta name="google-site-verification">` tag.
- **Custom domain:** edit the `CNAME` file.

## Features

- Text, checkmark, date, signature tools
- Highlight, freehand draw, rectangle, arrow, whiteout, image insertion
- Auto-detection of AcroForm fields
- Page rotate and delete
- Undo/redo, duplicate (Ctrl+D), arrow-key nudge
- 100% browser-side processing — files never leave the device
- Lazy-loaded pdf-lib (only fetched on Download) for fast first paint

## License

MIT
