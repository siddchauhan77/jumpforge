# Jumpforge

A tiny browser platformer inspired by classic side-scrolling mechanics, with a built-in level builder.

## Play

The local server is running at:

```text
http://127.0.0.1:8080/index.html
```

You can also open `index.html` directly in a browser.

To run from a fresh download:

```bash
npm start
```

Then open `http://127.0.0.1:8080/index.html`.

## Share

This is a static browser game. To share it, send someone `index.html` or upload the folder to any static host like Vercel, Netlify, or GitHub Pages.

## Controls

- `A/D` or arrow keys: move
- `W`, `Up`, or `Space`: jump
- `B`: build mode
- `P`: play mode
- `1-8`: choose a build tool
- Click or drag on the canvas in build mode to paint tiles

## Builder

Use the right panel to place ground, bricks, prize blocks, coins, spikes, enemies, and a goal flag. Levels can be saved to local storage or exported as a shareable level code.
