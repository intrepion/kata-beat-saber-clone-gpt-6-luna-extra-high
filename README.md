# NEON CUT

A self-contained, browser-playable mouse rhythm game. Follow the original synthesized synthwave loop and hover, click, or drag over a block as it reaches the glowing beat ring. Blocks only pop inside a small timing window around the beat; they cannot be cleared early.

## Play

Open `index.html` in a modern browser, or serve this folder locally:

```sh
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000). The soundtrack is synthesized in the browser, so there are no downloads or external assets.

## Controls

- **Mouse:** hover, click, or drag through blocks as they reach the beat ring
- **Touch:** tap or swipe through blocks as they reach the beat ring
- **Pause and mute:** use the buttons in the top right

The music and block arrivals share a 90 BPM clock. A bright green outline marks a block's hit window. Your score, streak, and best run are saved in this browser.
