Axisora Forge — Static Website
================================

This is a fully static export (HTML + CSS + images) of the original site.
No server, no build step, no Node.js required.

Files:
  index.html              -> Home
  about.html              -> About
  programs.html           -> Programs
  program-directions.html -> Program Directions (linked as "Directions" in nav)
  mentors.html            -> Mentors
  support.html            -> Support
  assets/                 -> CSS and image assets
  fonts                   -> Loaded from Google Fonts CDN (requires internet)

How to deploy (pick any one — all are free):
  1. GitHub Pages: push this folder to a repo, enable Pages on main branch.
  2. Netlify Drop: drag-and-drop this folder onto https://app.netlify.com/drop
  3. Cloudflare Pages: upload the folder via the dashboard.
  4. Local: just open index.html in a browser, or run:
        python3 -m http.server 8000
     then visit http://localhost:8000

Notes:
  - All inter-page links use relative .html paths, so it works from any subdirectory.
  - Fonts (Inter + Fraunces) load from Google Fonts CDN at runtime.
  - The original site was a TanStack/React app; this export is the pre-rendered HTML.
