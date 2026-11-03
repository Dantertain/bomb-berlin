# Bomb Berlin

A falling-block puzzle game in a single HTML file. No build step, no dependencies.

A plane patrols above a burning, bombed-out city and drops clusters of bombs. Stack them;
when a row is complete, a heavy bomber flies over and blows it up.

Pick a side (USA or USSR) at the top of the screen and race the other side to Berlin. Their control of the city
climbs steadily; clearing rows pushes them back. Each game lasts 30 seconds, and the other
side always takes Berlin in the end — your score is how well you held them off.

Works on phones: drag to move, tap to rotate, drag down to soft drop, flick down to hard drop.

Sound effects are synthesized in the browser with the Web Audio API (no audio files).

**Controls:** ← → move · ↑ / X rotate · Z rotate back · ↓ soft drop · Space hard drop · C / Shift hold · P pause · M mute.
On phones, use the on-screen buttons.

Play it at https://dantertain.github.io/bomb-berlin/ (GitHub Pages, served from the `main` branch).
