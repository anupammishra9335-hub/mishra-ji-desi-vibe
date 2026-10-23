# Mishra ji Desi Vibe — Audio edition

A buildless, ad-free instrumental music player for GitHub Pages. No accounts, advertising SDKs, API keys, or backend.

## Features

- Three credited CC BY 4.0 recordings by Kevin MacLeod: Dhaka, Carefree, Easy Lemon.
- HTML audio playback, pause, previous/next, seeking, volume, shuffle and repeat off/all/one.
- A playback queue captured when a track is selected; browsing/searching does not interrupt it. Previous returns through listening history, including while shuffling.
- Search, browser-local favourites, English/Hindi text, responsive layout and accessible native controls.
- Honest loading/error states with a retry button. Playback begins only after user interaction.

## Files and hosting

`index.html` contains the page and styles. `app.js` contains the player and catalogue. `MUSIC-CREDITS.md` records attribution and source links.

Serve this repository root with a static server, or use GitHub Pages from the main branch root. No build step is needed. Audio streams directly from incompetech.com; an internet connection and a reachable artist host are required. Browser/OS restrictions can affect volume and background playback. There is no offline playback or cross-device syncing.

## Adding music

Add only recordings whose licence permits this use. Add title, artist, audio URL, source and licence credits to the code and visible credits. Do not paste YouTube links into the audio source or remove required attribution. The starter tracks share one artist/licence; extend the data structure and credit renderer for other artists/licences.

The audio edition replaces the previous YouTube catalogue. Earlier versions remain in Git history.
