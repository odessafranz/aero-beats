# Aero Beats: Unfamiliar-User Test Note

## Tester and context

- **Tester:** [add tester name]
- **Date:** [add date]
- **Test task:** Start Level 1 and play by following the five keys in the order they appear.

## Observed friction

1. **The game appeared to end too early.** During play, a key could reach or pass the white pulse line while it was still visibly on the board. The player had not understood that the game was already treating that animation moment as a miss.
2. **The game originally allowed keys to be hit in any order.** This made the song pattern unclear and meant a player could press a later key instead of following the sequence shown on screen.

## Revisions made

1. The miss boundary was revised so a key remains playable until it has completely crossed below the white line. Reaching the line alone is not a loss.
2. Each key is assigned an appearance order. Only the earliest unplayed key can be hit. Pressing a later key or clicking a later tile ends the run, so the player must follow the song sequence.
3. The interface was updated to show the five-key control set: `J`, `K`, `L`, `;`, and `'`.

## Verification after revision

A human playtest verified that the game no longer ends merely because a key touches the white line. The key must fall completely below it. The playtest also verified that the first visible key must be hit before a later key can disappear; an out-of-order input ends the session as intended.

## Result

The revisions make the rules stricter but clearer: follow the keys in the order they appear, and a miss occurs only after the current key has fallen fully below the white line.
