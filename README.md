Vinyl Wallpaper - integrated Spotify version

This package combines the supplied Spotify PKCE login, playback polling, LRCLIB synced lyrics, clock, progress, album art and vinyl animation.

Deploy index.html on GitHub Pages path. In Spotify Developer Dashboard, add the exact published page URL (including path, without query/hash) as a Redirect URI. CLIENT_ID is in CONFIG near the top of the script. Do not add a client secret to this static site.

For the one-time Plash refresh-token transfer flow, use the page URL with ?setup, connect Spotify, then copy the URL it displays into Plash. Treat the resulting refresh-token URL as private.

Current bug fixes needed:
 - Pink bars on lyrics
 - Songs with no lyrics fade to black