`rules.js` is the save server's rules bundle (built by `tools/build_server.mjs` in the source repo). The `save-game`
edge function imports it from here pinned to a commit, so a deploy only has to send a one-line re-export.
These rules are the same checks the game already ships to every browser.
