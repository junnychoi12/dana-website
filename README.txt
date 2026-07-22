danA Wellness — Website Files
==============================

WHAT'S INCLUDED
  index.html        Home page
  treatments.html   Treatments (Wellness / Aesthetics / Special Offers / Signature)
  book.html         Book Appointment page
  contact.html      Contact page
  style.css         Shared styles — required by all pages
  script.js         Shared behavior (nav, tabs, forms) — required by all pages
  preview.html       Single-file interactive preview (for quick viewing only — not needed for deployment)

HOW TO DEPLOY
  1. Keep all 6 files (the 4 .html pages + style.css + script.js) together in the
     same folder — the pages link to style.css and script.js by relative path.
  2. Upload the whole folder to any static host:
       - Netlify / Vercel: drag-and-drop the folder
       - GitHub Pages: push the folder to a repo and enable Pages
       - Any traditional web host: upload via FTP/cPanel file manager
  3. Make sure index.html is set as the homepage/entry file.
  4. No build step, server, or database is required — it's a static site.

BEFORE GOING LIVE
  - Clinic hours are still a placeholder ("[Add clinic hours here]") on the
    Book Appointment and Contact pages — search each file for that text and
    fill in your real hours.
  - The booking and contact forms open the visitor's email client (mailto:)
    pre-filled with their details — there is no backend/database. If you'd
    like real online booking (calendar availability, confirmations, etc.),
    that would need a booking service (e.g. Acuity, Vagaro) wired in instead.
  - Photos on the home page are sourced from Unsplash (free license, no
    attribution required) — swap in your own clinic/treatment photography
    whenever you have it for a more personal feel.
