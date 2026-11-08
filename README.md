# CHRONO SHIFT: Combat Edition

A fast arcade action game in the browser, written in vanilla JavaScript with HTML5 canvas. Sound effects are synthesised live with the Web Audio API, so there are no audio files.

Play: https://kammmran.github.io/CHRON-SHIFT/

## Modes

| Mode | Files |
|---|---|
| Single player | `modules/1-person.html`, `modules/1-person.js` |
| Local two player | `modules/2-person.html`, `modules/2-person.js` |
| Online two player | `modules/online-2p.html`, `modules/online-2p.js` |

The menu is in `index.html`, the shared engine (audio, particles, game logic) in `script.js`, and styles in `style.css`.

## Run locally

```bash
git clone https://github.com/kammmran/CHRON-SHIFT.git
cd CHRON-SHIFT
python3 -m http.server 8000   # open http://localhost:8000
```
