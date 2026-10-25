# Recipe Calorie Counter

A phone app (web app) for working out calories per portion of a home-cooked recipe.

## Files
Upload ALL of these to the same GitHub repository, in the top level (not inside a folder):
index.html, sw.js, manifest.webmanifest, foods-usda.js, zxing.min.js, icon-192.png, icon-512.png, apple-touch-icon.png

## Updating later
If you change any file, also upload the new sw.js (its VERSION line must change, e.g. rcc-v3 -> rcc-v4). Phones then update by themselves next time the app is opened online, or via ⋯ -> Check for updates.
Recipes saved on the phones are not affected by updates.

## Data sources
- About 220 common UK ingredients (typical values per 100 g).
- USDA National Nutrient Database for Standard Reference, Release 28 (public domain), 6,000+ foods.
- Open Food Facts (openfoodfacts.org), ODbL, for barcodes and shop products (needs internet).
- Barcode reading: ZXing (Apache 2.0).
