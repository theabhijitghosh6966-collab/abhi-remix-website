ABHI REMIX - REMIX NAME FEATURE

What changed:
- Admin > Add New Song: enter a Remix Name / Version.
- Admin > Edit Existing Songs: add or change Remix Name / Version.
- Public website song cards display the Remix Name under the song title.
- Remix name is stored in Supabase in site_songs and site_song_overrides.

Setup:
1. Supabase SQL Editor > New query.
2. Paste and run REMIX_NAME_FEATURE_SETUP.sql.
3. Deploy all files from this folder to the existing Cloudflare Worker.
4. Open /admin.html, sign in, add or edit a remix name.
5. Refresh the public website to see it on the song card.

No password or Supabase service-role key is included.
