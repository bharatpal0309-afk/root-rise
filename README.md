# Root & Rise
A tree plantation and monitoring app built with HTML, CSS and vanilla JavaScript.

Open dist/index.html in a modern browser. Application source files and the Terms & Conditions page are inside dist/.

Features: tree registration and edits, photos and observation history, search and health filtering, care scheduling and completion, real record-derived statistics, JSON backup and import. IndexedDB stores records in the current browser. Import adds new record IDs and skips existing IDs.

No sample trees or invented statistics are included. Survival = (Healthy + Needs attention) / assessed trees; Not assessed trees are excluded. This reflects the latest recorded status, not a live sensor reading.

Data does not sync between devices. Clearing browser storage removes local records; keep JSON backups. Offline installation, maps, GPS, shared accounts and background notifications are not included in this version.

Validation: JavaScript syntax and core rendering/data-validation checks passed. Browser interaction and visual checks could not be completed because local preview connectivity was unavailable. Hosted publication was blocked by source-upload network/approval restrictions.

The legacy olive-grove browser database and backup identifiers are retained so existing records and backups remain compatible after renaming.

