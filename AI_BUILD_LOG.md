# Aero Beats: AI/Build Log

## Project

- **Game:** Aero Beats
- **Live URL:** https://odessafranz.github.io/aero-beats/
- **Repository:** https://github.com/odessafranz/aero-beats

## Major prompts and changes

1. **Initial game request:** Built a browser rhythm game with an original name, four falling-tile lanes, scoring, combo feedback, keyboard controls, and restart behavior.
2. **Visual direction:** Changed the design to a Y2K/Frutiger Aero style with glossy panels, aqua colors, bubbles, fish, water, and a supplied local background image.
3. **Game structure:** Added compact home and expanded play states, five columns, five right-handed keys (`J`, `K`, `L`, `;`, `'`), finite songs, five levels, and level unlocking after completing a song.
4. **Difficulty and audio:** Added songs that last at least 90 seconds, progressive speed increases, and original synthesized Web Audio instead of commercial recordings or samples.
5. **Reliability revisions:** Adjusted miss timing and input handling after human playtesting. Keys now follow their appearance order, and a key is only considered missed after it has completely crossed below the white line.
6. **Deployment:** Published the game with GitHub Pages and pushed the source code and background asset to a public repository.

## Human verification

I opened the local and public versions in a browser and verified that the game loads, shows five columns and five keys, starts a level, spawns tiles, updates the score, plays original audio after pressing Start, and responds to the keyboard. The final public URL returned successfully after deployment.
