# CS 61A Animator Project

## What it does

**Animator** is a drawing app built in Gleam. It has four modes, which you switch between with the tabs at the top of the control panel.

### Code
- Write a `draw` function in the built-in code editor, and the app animates the paths it returns on the canvas
- The drawing updates every time you change the code, and error messages show up in a red banner when the code doesn't work
- A **shape slider** changes the value passed to `draw`, so one drawing can change shape
- A **speed slider** speeds the animation up, slows it down, or plays it backward, and there are **Pause/Play** and **Reset** buttons
- A **drawing library** drop-down lets you switch between saved drawings or make a new one; everything is saved in your browser, so it's still there after a reload

### Speed Trace (mini-game)
- Trace a shape with your mouse before the pink **ghost** finishes drawing it
- Pick a polygon (Square, Trapezoid, Star, Pentagon, Hexagon, Octagon or Decagon) or a custom challenge
- The race starts with your first stroke, and the speed slider sets how fast the ghost is, so you can make it easier or harder
- To win, you have to cover 90% of **every** shape; meters show your progress, the ghost's progress, and the shape you've traced the least
- When you win, you get your time and an **accuracy score** based on how close you stayed to the outline

### Builder
- Make your own challenges for friends to race
- Add polygons, drag them around, and change their size, rotation and color
- Save a challenge with a name, load it again to edit it, or delete it

### Free Draw
- Draw whatever you want with a color picker, a brush size slider, and six brushes: **Solid, Rainbow, Neon glow, Dashed, Watercolor and Zigzag**
- **Replay** redraws your picture in the order and at the speed you drew it
- **Undo** and **Clear** buttons
- **Save as challenge** turns your drawing into a Speed Trace challenge

### Everywhere
- **Export PNG** saves whatever is on the canvas as an image
- The control panel can be hidden so it doesn't cover the drawing
- Challenges and drawings are saved in your browser's localStorage

**Try it:** https://aydaneddiegonzalez.github.io/animator/
