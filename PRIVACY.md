# Privacy

**The Domain-Ramp Workbook collects nothing.**

- **No server.** `workbook.html` is a single static file. There is no backend, no API, no form submission. Open it from your own disk and it works fully offline.
- **No storage.** Everything you type lives in an in-memory JavaScript variable for the life of the browser tab. There is **no `localStorage`, no cookies, no `sessionStorage`, no IndexedDB**. Close or reload the tab and the data is gone. Export to Markdown first if you want to keep it.
- **No analytics, no tracking, no telemetry.** The page loads no third-party scripts, fonts, pixels, or beacons. It makes no network requests of any kind.
- **No data leaves your machine.** The "Export to Markdown" button renders text into a box in the same page for you to copy. Nothing is transmitted.

The Python generator (`generate_workbook.py`) reads the local template and writes a local HTML file. It uses the standard library only and makes no network calls.

Because the worked example is built entirely from **public** information (higher-ed enrollment marketing — published trade terms, public regulations, named public companies), there is no proprietary or personal data anywhere in this repo.

If you fill the workbook in with confidential information about your own domain, that information stays in your browser tab and your exported file. Treat the exported Markdown the way you'd treat any internal document — but know that nothing about it touched a network on the way out.

— Jeff Pinto · https://jeffpinto.com
