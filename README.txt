ALEC COACH — OFFLINE STRENGTH & NUTRITION APP

Files:
- index.html: the complete app
- manifest.json: installable PWA metadata
- sw.js: offline caching

Use:
1. Put these files on a web host (GitHub Pages, Netlify, your own domain, etc.).
2. Open the site on your phone.
3. On iPhone Safari: Share -> Add to Home Screen.
4. On Android Chrome: browser menu -> Install app / Add to Home screen.

Data:
- Meals and weight are stored in browser localStorage.
- Use Progress -> Export JSON to make a backup.
- Import that JSON backup on another browser/device.
- CSV export is useful for spreadsheets.

The starting targets in the app are 2,200 kcal, 120 g protein, 270 g carbs and 60 g fat.
These are configurable in the source code if your coach later changes them.

FOOD SEARCH
- Nutrition includes an Open Food Facts search for foods and brands.
- Search requires an internet connection; the rest of the app remains locally stored.
- Product values are database data, so check package labels when accuracy matters.
