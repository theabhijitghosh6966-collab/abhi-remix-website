ABHI REMIX — PUBLIC SONG DISPLAY FIX

1. In Supabase Dashboard, open SQL Editor and run PUBLIC_SONGS_ACCESS_FIX.sql once.
   This allows anonymous website visitors to READ song rows and public song media only.
   It does not grant public insert, edit, or delete access.
2. Deploy the contents of this ZIP to your existing website hosting, replacing the current website files.
3. Open the public website in a private/incognito tab or hard-refresh it.
4. New songs saved in Admin Panel > Add Song should now appear under Latest Releases.

The updated index.html also shows a visible diagnostic message below the song grid if Supabase rejects the public read request.
Existing song rows, media, views, downloads, and Admin Panel files are preserved.
