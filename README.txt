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


Added release: Uttar Para Chala Ami — Humming Dance Mix. Cover: covers/uttar-para-chala-ami-cover.webp. Audio: songs/uttar-para-chala-ami-dj-abhi-remix.mp3.


ADMIN DASHBOARD UPDATE
After signing in at /admin.html, the admin panel now includes the live Global Statistics dashboard (Total Songs, Total Views, Total Downloads) with a Refresh button. It reads song_views and song_downloads from Supabase and adds the 6 built-in website tracks to the admin-added song count. No additional SQL is required for this dashboard update.


EDIT EXISTING SONGS
1. Run EDIT_OLD_SONGS_SETUP.sql once in Supabase SQL Editor.
2. Deploy all files in this ZIP to Cloudflare Workers/Pages.
3. Sign in at /admin.html with funnyvoiceovers34@gmail.com.
4. Use the Edit buttons under Edit Existing Songs. Cover and MP3 replacements are optional.
5. Existing song metadata and optional media replacements are saved to Supabase and applied on the public home page.
