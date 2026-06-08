# Soundboard

**School of Tomorrow's AI** — classic sound design clichés for live presentations, workshops, and performances.

→ Open `index.html` in any modern browser. No build step, no dependencies.

---

## How it works

12 buttons. Each one triggers an `.mp3` file from the `sounds/` folder.  
If a file is missing, the button falls back to a synthesised version via Web Audio API.

---

## File structure

```
index.html
sounds/
  01-applause.mp3
  02-drum-roll.mp3
  03-suspense.mp3
  04-fail.mp3
  05-fanfare.mp3
  06-laughter.mp3
  07-booing.mp3
  08-impact.mp3
  09-ta-da.mp3
  10-game-over.mp3
  11-ding.mp3
  12-alarm.mp3
```

---

## Replacing sounds

Drop your own `.mp3` files into the `sounds/` folder using the same filenames.  
The button badge will show `✓ loaded` once the file is detected.

> **Format:** `.mp3` recommended — broadest browser compatibility, including Safari.

---

## Brand

Built following the [School of Tomorrow's AI brand kit](https://linalopes.github.io/SchoolAI-brand-kit/).

Colors: Deep Purple `#22113E` · Pink `#EA7DFF` · Turquoise `#08F2DB` · Gray Green `#CAD8D8`  
Fonts: Space Grotesk · Courier Prime · Inter

---

## License

[MIT](LICENSE)
