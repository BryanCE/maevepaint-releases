# Changelog

## 0.1.7

- A new **Magic** tab with Blur, Smudge, Push, Kaleidoscope and Fractal fold. Kaleidoscope folds
  the whole picture into mirrored wedges, and dragging slides the picture under the mirrors.
  **Fractal fold** swirls the picture into a fractal around where you press. Drag away to make
  it bigger, and drag around to turn it.
- Brushes have a **Magic** tab beside **Brush** and **Feel**. Each magic has its own card with an
  on and off switch, and its settings show while it's on:
  - **Kaleidoscope** repeats each stroke around the middle of the page, or the middle of the
    view on open paper, with **Sides** and **Mirror**.
  - **Fractal sprouts** grows little Julia, Mandelbrot or Burning Ship fractals out from each
    stroke, in bands of the stroke's color. Pick the **Shape**, **Size**, **Spacing**,
    **Colors** and **Color by**, which bands by **Equation** or **Distance**. **More** has the
    rest, including the Julia shape, a Mandelbrot map to tap and **Walk**.
- Mandelbrot, Julia and Burning Ship fractal paint, in the **More colors** window, with
  **Colors**, **Size** and **Turn**. Brushes, fills, Recolor and filled shapes can all paint
  with it.
- **View > Picture on top** moves a coloring page's picture over or under the drawing, so paint
  can cover a picture that opened as line art. Undo moves it back.
- **Reset to defaults** in a brush's **Brush** tab also turns off its magic.
- **Triangle**, **Star** and **Polygon** join the **Shapes** tab, and each can be filled like the
  rectangle and ellipse. Pick a star's **Points** and a polygon's **Sides**.
- The Fill shape tool is gone. **Fill** colors in a shape instead.
- The Move tool picks what it takes hold of: one thing, everything touching it, or everything.
  It can move, copy, or turn and size. Turn and size puts a frame around what's picked, with
  corners to drag for size, a knob to drag for turning, and Flip buttons for sideways and upside
  down.
- The pen comes first on the tool rail.
- The pencil starts at 8B, so it shows up on paper. Soft pencils draw a solid line even when
  small.
- Smudging inside the lines stays inside the lines.

## 0.1.6

- The grown-ups' window has separate **Pictures** and **Stickers** pages. Each lists every set
  once, with its switch to hide it, **Remove** for a downloaded set and **Install** for one you
  don't have yet. A row shows how many pictures or stickers a set has, its size and its license.

## 0.1.5

- Update the app from the grown-ups' window. **Updates** checks GitHub for a newer version,
  then downloads it, checks the download, installs it and restarts. Your picture is saved
  first.
- The app keeps a log file, `maevepaint.log`, in its data folder. It records what went wrong
  and any time the app froze.
- Saving never holds up drawing.

## 0.1.4

- A quick fix to 0.1.3.

## 0.1.3

- New brushes: Gel pen, Inky pen, Colored pencil, Oil pastel, Sidewalk chalk, Splatter and
  Glitter spray. Any brush can sparkle.
- Crayon, chalk, oil pastel and sidewalk chalk lay one smooth mark instead of showing each dab.
- White ink in a see-through brush shows up on dark colors.
- Turn a sticker by dragging around where you pressed. With a second finger, pinch to size it
  and twist to turn it.
- Rainbow paint shows a rainbow ring around the color and a rainbow bar under the colors.
  Picking a plain color turns it off.
- Bigger text in the kids' window.
- Simple mode:
  - One size slider for every tool.
  - Paint and pens never run dry.
  - No zooming, and a second finger doesn't stop the stroke.
  - The stickers tool is included.
  - Big tiles in narrow sidebars.
- The grown-ups' window has a dark mode switch on the **Child** page.
- Spray paint and the airbrush start stronger.

## 0.1.2

- Touch works properly on Linux. The first finger draws, two fingers pan and zoom, and a finger
  drag scrolls lists.
- A lost finger or mouse release no longer leaves drawing stuck.
- Saving runs in the background, so dragging a slider saves once at the end instead of at every
  step.

## 0.1.1

- Download picture and sticker sets from inside the app, in the grown-ups' window under
  **Content > Get more**. Install and remove them any time.
- The picture chooser sorts pictures by topic. Tap Dinosaurs and you get every dinosaur picture
  from every set.
- The grown-ups' window lists picture and sticker sets by topic or by source, with a switch to
  hide each one.
- A sound you picked yourself shows its file name instead of "Your sound".
- Touch always draws from the screen's touch messages. The setting for it is gone.
- The "more below" arrow no longer shows up on tools that have no options.
- **Help > Credits & licenses** lists every open-source part built into the app.
- First Linux release, as a `.deb` for Linux Mint, Ubuntu and Debian.

## 0.1.0

First release.
