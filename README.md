# Alarm in a Meadow

An interactive alarm-clock prototype. Turn the glass wheel to move through a day in the meadow. Time is written out in words, and the sky and shadows change as you turn the wheel.

[Open the prototype](https://emguseii.github.io/meadow-alarm/)

- Drag the wheel with a mouse or a finger. A full turn advances or rewinds twelve hours.
- Press **Space** to start the 24-second looping showreel. Press **Space** again or **Esc** to return to manual control.
- Focus the wheel and use the arrow keys for one-minute adjustments.

For local use, open `index.html` in a browser. The page uses plain HTML, CSS, and JavaScript. Its landscape PNGs and numeral SVGs are included, so it needs no build step.

The wheel sounds are synthesized with Web Audio. To hear a melody during the sunrise scene in your local copy, place an `alarm-melody.mp3` next to `index.html`.
