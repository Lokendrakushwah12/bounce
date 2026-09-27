# Bounce

The black-and-white Nokia Bounce, rebuilt as a single HTML file.

Open `index.html` in a browser to play. No build step, no dependencies.

## Controls

| Action | Keys |
|---|---|
| Roll | Arrow keys or A / D |
| Jump (hold to keep bouncing) | Up, W or Space |
| Menu / resume | Esc |

The on-screen pad and buttons work on touch screens.

## How it plays

- Thread every hoop to open the exit door.
- Crystals are checkpoints. Thorns and spiders pop the ball.
- The pump makes the ball big, so it floats in deep water. The deflater makes it small again, so it fits through tunnels.

## Physics

Ball physics follow the original game: 25 ticks a second, integer pixels, one-pixel collision steps, the original gravity, jump, bounce and water constants. They were ported from the community decompilation at [rndtrash/nokia-bounce-decomp](https://github.com/rndtrash/nokia-bounce-decomp). Levels are original designs, not copies of Nokia's.
