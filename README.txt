LEGO Inventory Verifier - Diagon Alley 76444 Bag 3

Open index.html in any static web host (GitHub Pages, Netlify, Cloudflare Pages, etc.).

Mobile workflow:
- Check a part only when catalog image + color + quantity are exact.
- Checking automatically records Exact and verified quantity = claimed quantity.
- Progress autosaves in localStorage.
- Save Results downloads JSON that can be uploaded back to ChatGPT.
- Save CSV downloads a spreadsheet-friendly results file.
- Restore JSON can reload a previous exported results file.

All catalog images are embedded in index.html, so no API key is required.

iPhone note (2026-10-01):
- On iPhone, Save Results / Save CSV open a copy screen instead of downloading a
  file (iOS Safari ignores the download attribute). Tap Copy, then paste the
  text into Notes or Files.
- The "Actual quantity" field only accepts digits.
