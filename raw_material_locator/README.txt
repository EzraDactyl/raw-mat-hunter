RAW MATERIAL LOCATOR - FIRST PROTOTYPE

Features:
- Search by chemical/canonical name, alias/brand name, vendor, or internal item code.
- Multiple stock locations and quantities per raw material.
- Batch quantity checker with compatible mass/volume unit conversion.
- JSON backup/restore and CSV import/export.

Batch input format:
Carbomer 940 | 10 | kg
Glycerin | 25 | kg
Synthalen-K | 5 | lb

CSV columns:
Canonical Name, Aliases, Item Code, Vendor, Location, Quantity, Unit
Separate aliases with semicolons. Use one row per stock location.

Phone installation:
This is a Progressive Web App. Host this folder over HTTPS using a service such as GitHub Pages, Netlify, or Cloudflare Pages. Open it in your phone browser and use Add to Home screen / Install app.

Data warning:
This version stores inventory in the browser on that specific device. Export a JSON backup regularly.

Next upgrade:
Camera/photo OCR for reading a paper batch record and filling Batch Check automatically.
