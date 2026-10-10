Wipeout — Arizer XQ2 Session Log
A mobile-friendly, static web app for recording Whip (direct draw), Elbow (cyclone bowl) and Baggins (balloon bag) sessions.
What's included
Session timer, temperature, duration and Baggins bag counter
End-of-session 0–10 ratings for Wipeout (obliteration), Bud Char, Base Cleanliness and Flavour; no combined score
Dashboard trend chart with all four lines, a thicker/highlighted Wipeout line, session-type and date-range filters
Alcohol entries per session: drink type, optional name, ABV, ml quantity and number of drinks; estimates pure alcohol in grams and UK units
Session history, edit/delete, tags, material/setup notes and session notes
Summary statistics and simple descriptive insights
CSV export, JSON backup and JSON import
Local browser storage; no account or server required
Publish/update with GitHub Pages (Android-friendly)
Download and extract the ZIP on your device.
Open your GitHub repository named wipeout (or create one).
Upload/replace index.html in the repository root. README.md is optional.
Commit the change. If GitHub Pages is already enabled, it should redeploy automatically.
If Pages is not enabled: repository Settings → Pages → Deploy from a branch → main → /(root) → Save.
Open the Pages URL shown by GitHub, usually https://YOUR-USERNAME.github.io/wipeout/, in Brave on Android. Use the browser menu's Add to Home screen for an app-like shortcut.
Existing data compatibility
This version deliberately keeps the original localStorage key, wipeout.sessions.v1, and preserves the existing id, type, duration, temperature, bags, load, notes, and createdAt fields. Older sessions remain in history; ratings and alcohol data will be blank for those records unless edited. Updating the deployed index.html does not delete the existing browser data. Export a JSON backup before making major changes as a precaution.
Data and privacy
Sessions are stored in localStorage for this exact site and browser profile. They do not automatically sync between devices and may be lost if site data is cleared. Use Backup JSON for a restorable copy or Export CSV for spreadsheets. Alcohol estimates use 0.789 g/ml ethanol density and UK units (8 g of pure alcohol per unit); estimates depend on the ABV and quantities entered.
Limitations
This is a manual logging tool. It does not connect to or control the Arizer XQ2, and it does not provide medical or safety assessments.
