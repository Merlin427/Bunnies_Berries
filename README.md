# Bunny Berries 🐰🍓

A gentle maze game for little kids. Help the bunny eat all the berries.

- **Just berries** – no clouds, no way to "lose". Good for ~2–3 year olds.
- **Berries + clouds** – friendly clouds wander around. If one bumps the bunny, it gets dizzy and hops back to the start. There are no lives and no game over. Eat a ⭐ and the clouds turn rainbow, so the bunny can tag them for bonus points.

**5 levels, 5 stickers:** each maze you clear earns a sticker (🐞 🌻 🦋 🍉 🦄). Collect all five for a big celebration. Progress is saved, so the kids carry on from the next sticker.

**Controls:**
- **Arrows:** the bunny hops only while an arrow is held down, and stops when you let go.
- **Swipe:** the bunny keeps going until it hits a wall.
- **Tap:** tap anywhere in the maze and the bunny walks there by itself.

## Host on GitHub Pages

1. Create a new public repo and upload all the files in this folder to the root.
2. Go to **Settings → Pages**, set Source to **Deploy from a branch**, choose `main` and `/ (root)`, then click Save.
3. After a minute, open `https://<your-username>.github.io/<repo-name>/` in Safari on the iPhone or iPad.
4. Tap **Share → Add to Home Screen**. It now opens full-screen like an app and works offline.

## Updating

If you change any file, bump `CACHE` in `sw.js` (for example `bunny-berries-v2`). Otherwise devices keep serving the old cached copy. Open the app once while online and the update is picked up on the next launch.

## Notes

- **No sound?** Check the iPhone's silent switch. iOS mutes web audio when the phone is on silent.
- **Home button:** the 🏠 button needs two taps, so little fingers don't quit by accident.
- **Locking the app:** to stop the kids leaving the app, use **Guided Access** (Settings → Accessibility → Guided Access, then triple-click the side button).
