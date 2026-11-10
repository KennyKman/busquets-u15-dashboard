# My #6 Development – Busquets Learning Lab

A single-page player-development tracker for U15 defensive midfielders.

## How it works
- Everything is in `index.html` — no build step, no server code, no database.
- Each player's ratings and notes are saved **only in their own browser** (localStorage).
  Nothing is sent to or stored on the server.
- Players share progress with the coach by using **Export progress (.json)**.
- The page asks search engines not to index it (`noindex`).

## Deploying on Render
This repo includes `render.yaml`, so Render sets it up as a free Static Site automatically
(New → Blueprint → pick this repo). Every push to `main` redeploys the site.

## Updating
Edit `index.html`, commit, and push. Render redeploys within a minute or two.
