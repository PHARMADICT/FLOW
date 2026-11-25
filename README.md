# VYSAKH Master Sales Tracker (PWA Bundle)

A mobile-first, offline-ready Progressive Web App built with HTML5, CSS3, and vanilla JavaScript.

## Included Files
- `index.html` — Complete application UI, styles, state history (Undo/Redo), store management, and ledger logic
- `manifest.json` — PWA metadata and icon configuration
- `sw.js` — Service worker for offline caching
- `README.md` — Deployment and usage instructions

## Key Features
- **Clean Start & Full Undo/Redo**: Starts with a clean ledger and supports up to 100 undo/redo steps across edits, additions, deletions, and store updates.
- **Customizable Store Bar**: Switch between working stores, add new stores, or double-tap any store tab to rename it.
- **1/4 Compact Grid & Brand Filters**: Filter by `W-H`, `K-V`, `H-A`, `P-P`, `PAX`, and `G-R`, tap to add with a 450ms double-tap guard, and adjust via the reconfirm bar.
- **Master Ledger, Paste Importer & Exports**: Edit rows inline, paste TSV/CSV rows, export in the `STORE / DATE / ITEM / QTY / UNIT PRICE (AED) / TOTAL (AED) / INCENTIVE / DAY SALES / SOLD PLACE` format, save JPG snapshots, or share directly to WhatsApp.
- **Payment Reconciliation**: Track `REPORT SENT UP TO DATE`, `AMOUNT RECEIVED (AED)`, and auto-calculated `PENDING` balances.

## Hosting
Deploy `index.html`, `manifest.json`, `sw.js`, and `README.md` to GitHub Pages, Netlify, Vercel, or serve locally via `python -m http.server 8000`.
