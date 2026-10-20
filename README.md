# The Legend of Skylarr

A pocket-sized monster-taming adventure that runs in the browser. Play it at
**https://skylarr12227.github.io/legend-of-skylarr/**

This is the online version: it adds **VERSUS** battles against other players (find someone waiting in the lobby, or
make a room and share its 4-letter code). Battles connect through Supabase Realtime; nothing is stored on a server,
and your save stays in your own browser.

`site/index.html` is the whole game in one file. It's built from the game's source and deployed by
`.github/workflows/pages.yml` on every push to `main`.
