# Street Racer — YouTube Playable Car Racing Game

A single-file HTML5 canvas racing game built for **YouTube Playables**.  
Tap left/right (or use arrow keys / A-D) to dodge traffic. First-to-survive distance scores.

## Controls
- **Touch:** Tap left / right side of screen
- **Keyboard:** `←` `→` or `A` `D`

## YouTube Playables readiness
- ✅ HTML5 Canvas, single `index.html` (~6 KB)
- ✅ Mouse + touch input supported
- ✅ Responsive canvas, mobile-friendly (max 360×640)
- ✅ No external calls — all drawn via Canvas API
- ✅ Playables SDK integrated (`ytgame.firstFrameReady()` / `gameReady()`)
- ⚠️ Publish: fill out the [YouTube Playables interest form](https://developers.google.com/youtube/gaming/playables), wait for invite, upload ZIP via Playables Developer Portal.

## Publish to GitHub
```bash
cd /c/Users/Suraj/playables-car-racing
git init
git add .
git commit -m "Initial: Street Racer car racing Playable"
git branch -M main
git remote add origin https://github.com/99surajb/playables-car-racing.git
git push -u origin main
```
Create the empty repo at `https://github.com/99surajb/playables-car-racing` first (no README init).

Then enable GitHub Pages in repo settings → `https://99surajb.github.io/playables-car-racing/`.

## License
MIT
