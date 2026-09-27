# Bounce

The black-and-white Nokia Bounce, rebuilt as a single HTML file.

Open `index.html` in a browser to play. No build step, no dependencies.

## Controls

| Action | Keys |
|---|---|
| Roll | Arrow keys or A / D |
| Jump (hold to keep bouncing) | Up, W or Space |
| Menu / resume | Esc |

On touch screens, drag the joystick sideways to roll and push it up to jump. The sound button in the top bar mutes the beeps.

## How it plays

- Thread every hoop to open the exit door. Small hoops only fit the small ball.
- Crystals are checkpoints. Thorns and spiders pop the ball.
- The pump makes the ball big, so it floats in deep water. The deflater makes it small again, so it fits through tunnels.
- Rubber blocks bounce you higher each time you land on them with jump held.
- Ramps turn a fall into a roll.
- Power-ups last 12 seconds: gravity flips you onto the ceiling, jump launches you skyward, speed doubles your top speed.

There are eleven levels. Each one introduces a mechanic, and the last one mixes them.

## Editing levels

Levels are plain text maps at the top of the script in `index.html`. The legend is in the comment above them.

## Physics

Ball physics follow the original game: 25 ticks a second, integer pixels, one-pixel collision steps, and the original gravity, jump, bounce, water, slope, rubber and power-up rules. They were ported from the community decompilation at [rndtrash/nokia-bounce-decomp](https://github.com/rndtrash/nokia-bounce-decomp). Levels are original designs, not copies of Nokia's.
