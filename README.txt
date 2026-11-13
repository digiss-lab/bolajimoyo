Nigeria Under Tinubu: The Pains, the Gains, and the Evidence
Website for bolajimoyo.com · Edition 2026-11-11.9 · By Bolaji Moyo

WHAT IS IN THIS FOLDER
  index.html                 Interactive dashboard (the home page)
  report.html                Full report, mobile-friendly
  data.html                  Open-data page listing the CSV files
  data/*.csv                 All data behind the report and dashboard
  assets/d3.v7.9.0.min.js    Charting library (stored locally, no outside calls)
  assets/data.js             The dashboard's data, embedded so pages load fast
  assets/whatsapp-card.png   The 1080x1350 WhatsApp card

The site is plain static files: no server code, no database, no logins.
It works on any static host and opens in any phone browser.

PUTTING IT ONLINE (pick one; all have free tiers - check their current terms)
  - Cloudflare Pages, Netlify or GitHub Pages: upload or connect this folder,
    then add bolajimoyo.com as a custom domain in the host's settings and
    update your domain's DNS records as the host instructs.
  - Upload the whole folder, keeping its structure. index.html must be at the top level.

UPDATING FOR A NEW EDITION
  Replace the CSV files in data/ and regenerate assets/data.js (Claude can do
  this as part of each edition refresh), then upload the folder again.

CORRECTIONS AND RIGHT OF REPLY: why9ija@gmail.com
