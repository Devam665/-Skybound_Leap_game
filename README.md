# -Skybound_Leap_game
# Skybound Leap 🌤️💎

A 3D platformer built with [Three.js](https://threejs.org/) — pure HTML/JS, no build step, no engine install required. Leap across drifting sky-islands, collect crystals, dodge moving platforms, and reach the portal before time runs out.

**Controls:** WASD / Arrow keys to move, Space to jump (tap twice for a double jump). Touch controls appear automatically on mobile.

## Hosting it on GitHub Pages (free, ~5 minutes)

1. **Create a new repository**
   Go to [github.com/new](https://github.com/new), give it a name (e.g. `skybound-leap`), keep it Public, and click **Create repository**.

2. **Upload the file**
   On your new repo's page, click **Add file → Upload files**, drag in `index.html` from this folder, and click **Commit changes**.
   *(Only `index.html` is required — it's fully self-contained, everything else loads from CDNs.)*

3. **Turn on GitHub Pages**
   Go to **Settings → Pages** (left sidebar). Under "Build and deployment", set **Source** to **Deploy from a branch**, pick branch **main** and folder **/ (root)**, then click **Save**.

4. **Get your link**
   Wait about 1–2 minutes, then refresh the Pages settings screen — it'll show a live URL like:
   `https://your-username.github.io/skybound-leap/`

   That's your playable game, shareable with anyone.

## Notes for your dev project

- The whole game (rendering, physics, collision, scoring, timer, HUD) lives in one file: `index.html`. Open it in a text editor to see the commented source — that's your "script" for write-ups or documentation.
- If you want to keep iterating, edit `index.html` locally, then re-upload it to the same GitHub repo (or use `git push` if you're comfortable with Git) — Pages auto-updates within a minute or two of each commit.
- Every asset is either generated in code (geometry, shaders) or loaded from `cdnjs.cloudflare.com` (Three.js + Google Fonts), so there's nothing else to upload.
- 
