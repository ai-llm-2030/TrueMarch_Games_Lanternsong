# Lanternsong

**Five lit worlds, 30 public-domain songs. Repeat the melody note by note, or tap it as tiles.**

<p align="center">
  <img src="assets/screenshot-title.png" alt="Lanternsong — title screen" width="820">
</p>

<p align="center">
  <a href="https://ai-llm-2030.github.io/TrueMarch_Games_Lanternsong/"><b>▶ Play Lanternsong in your browser</b></a>
</p>

## Gameplay

<p align="center">
  <img src="assets/screenshot-play.png" alt="Lanternsong — gameplay" width="820">
</p>

## More screenshots

<table>
<tr><td width="50%"><img src="assets/screenshot-map.png" alt="The journey map"><br><sub>The journey map</sub></td><td width="50%"><img src="assets/screenshot-tiles.png" alt="Endless Tiles"><br><sub>Endless Tiles</sub></td></tr>
<tr><td width="50%"><img src="assets/screenshot-shop.png" alt="The Lantern Market"><br><sub>The Lantern Market</sub></td><td width="50%"><img src="assets/screenshot-results.png" alt="Stage clear"><br><sub>Stage clear</sub></td></tr>
</table>

## Controls

| Keys | Action |
|---|---|
| 1 – 9 or D F J K | Light the lanterns |
| H | Listen again |
| Esc / P | Pause |
| M | Sound on / off |

## Run it yourself

No install, no build step, no server code, no network. The game runs entirely in your browser and keeps your progress in the browser's local storage.

```bash
git clone https://github.com/ai-llm-2030/TrueMarch_Games_Lanternsong.git
cd TrueMarch_Games_Lanternsong
python3 -m http.server 8000
# open http://localhost:8000
```

Opening `index.html` directly works too in most browsers; a local server is the most reliable way.

## What's inside

```
TrueMarch_Games_Lanternsong/
├── index.html        the whole game: one file, plain JavaScript and <canvas>
├── lib/
│   ├── arcade.js     shared helpers: crisp canvas, frame loop, input, theme
│   └── arcade.css    shared look
├── assets/           the pictures in this README
├── LICENSE
└── README.md
```

Written from scratch in vanilla JavaScript: every sprite, background and sound is drawn or synthesised in code (Canvas 2D and the Web Audio API). No libraries, no frameworks, no third-party assets. The melodies are public-domain songs, arranged and played in code.

## About

**Lanternsong** is one of the 120+ games made by **[TrueMarch](https://truemarch.com)**. This repository is the standalone single-player edition of the game.

## License

© 2026 TrueMarch. All rights reserved. The source is published so you can read it, learn from it and play the game; see [LICENSE](LICENSE).
