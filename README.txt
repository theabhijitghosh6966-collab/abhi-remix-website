ABHI REMIX — Website deployment files

Includes: index.html, robots.txt, sitemap.xml, songs/ and covers/.
Google Search Console HTML-tag verification meta tag is included in index.html.

Cloudflare Workers & Pages: open your abhiremix project, choose New deployment / Upload static files, and upload the contents of this folder (not the outer folder itself). Keep the songs and covers folders with their files. Deploy, then return to Google Search Console and use HTML tag verification / request indexing as needed.

Only upload or distribute music and artwork you own or have permission to use.


Monetag integration notes:
- Monetag verification meta tag is present in index.html.
- The supplied tag.min.js script was added before </head>.
- sw.js was recreated from the configuration visible in the user screenshot (domain 5gvci.com, zoneId 12125644). If Monetag downloaded a different service-worker file, use the exact downloaded file instead.
- Cloudflare Workers static assets may need an explicit route/config to serve /sw.js from the site root; the ZIP alone does not deploy or guarantee Monetag installation verification.


UPDATE 2026-10-29: Added “De Signal — 8K JBL Bass” to Latest Releases, including a Play Track button, Download link, and the DJ ABHI REMIX cover. Audio file: songs/de-signal-8k-jbl-bass.mp3. Cover: covers/de-signal-dj-remix-cover.png.


For Supabase song play views, follow SUPABASE_SONG_VIEWS_SETUP.txt.
