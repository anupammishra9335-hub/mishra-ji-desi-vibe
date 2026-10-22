# Mishra ji Desi vibe 🎶

A single-page desi music site: old Bhojpuri geet, folk, and a party playlist of old and new hits. Press play and songs play right on the page through an embedded YouTube player.

## Features
- Mood tabs and search, with a Party Time category
- Song thumbnails, a bottom player bar with progress, a queue drawer
- Keyboard shortcuts: Space, N, P, S, Q, left/right arrows, /
- English and Hindi interface toggle
- Share a single song with `?s=VIDEO_ID`

## Edit songs
Open `index.html` and edit the `songs` list in the script. Each entry has a YouTube video ID (`id`, the part after `v=`), title (`t`), artist or film (`a`) and mood (`m`: yaad, ganga, bhakti, holi or party). Pick videos whose owners allow embedding.

## Deploy
Pure static site, no build step. Served with GitHub Pages from the `main` branch root.
