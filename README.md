# MaevePaint

A paint program for kids. It has pencils, inks, paint that blends, spray, chalk, fills, shapes and
stickers, plus magic like blur and a kaleidoscope. Everything makes a sound, and undo never runs
out. Kids draw on blank paper or color in pages from the picture library.

Grown-ups get a separate window with settings the child never sees: which picture and sticker
sets show up, what each thing sounds like, downloading more sets and updating the app.

## Download

- **The app:** [latest release](https://github.com/BryanCE/maevepaint-releases/releases/latest)
- **Coloring pages and stickers:** [picture and sticker library](https://github.com/BryanCE/maevepaint-releases/releases/tag/library).
  The app downloads these for you from the grown-ups' window, so you only need this link to
  see what's there.

### Linux Mint, Ubuntu and Debian

Download `maevepaint_<version>_amd64.deb` and double-click it, or run
`sudo apt install ./maevepaint_<version>_amd64.deb`. MaevePaint then shows up in the menu under
Graphics.

It runs on Linux Mint 22 and newer, Ubuntu 24.04 and newer, and Debian 13. It needs an X11
desktop. Linux Mint's Cinnamon is X11 out of the box.

### Windows

Download `maevepaint.exe`. There's nothing to install, so put it anywhere and run it. It needs
64-bit Windows 10 or 11.

The exe isn't code-signed, so the first time you run it Windows SmartScreen says "Windows
protected your PC". Click **More info**, then **Run anyway**.

## Coloring pages and stickers

The app starts with no picture or sticker sets, so the download stays small. To add some, open the
grown-ups' window with the gear button at the top right or **File > Settings**. Go to the
**Pictures** or **Stickers** page and click **Install** on the sets you want. They come from this
repo's [picture and sticker
library](https://github.com/BryanCE/maevepaint-releases/releases/tag/library) release.

The sets come from NASA, NOAA, the National Park Service, the USDA Forest Service, Wikimedia
Commons, FreeSVG, OpenMoji, Tux Paint and a few others. Kids pick pictures by topic, like
Dinosaurs, Space, Ocean or Animals. Stickers come in topics too. You can turn any set off to hide
it, and remove any set you downloaded. When a newer version of a set you downloaded comes out, its
row shows **Update**.

## Updates

The grown-ups' window's **Updates** page checks for a newer version. **Update** downloads it,
installs it and restarts the app, saving the picture first.

## Where things are saved

Pictures go in the `MaevePaint` folder inside your Pictures folder. Each one saves as you draw,
and closing it writes a PNG next to it.

Settings and downloaded sets go in `%APPDATA%\MaevePaint\data` on Windows and
`~/.local/share/maevepaint` on Linux. The log file, `maevepaint.log`, is in the same folder.

None of it leaves your computer. [PRIVACY.md](PRIVACY.md) has the details.

## Licenses

MaevePaint is free to use and share. The terms are in [LICENSE](LICENSE).

The app shows each set's license next to the set before you install it, and the license file
travels inside the set. **Help > Credits & licenses** lists everything built into the app, with
the full license texts.

## Changes

[CHANGELOG.md](CHANGELOG.md) lists what changed in each version.

## Bugs and ideas

Found a bug, or want a new brush or sticker set? Open an
[issue](https://github.com/BryanCE/maevepaint-releases/issues/new/choose) and pick **Something's
wrong** or **Idea**. You need a free GitHub account.

Check the [open issues](https://github.com/BryanCE/maevepaint-releases/issues) first. If someone
already reported it, react to theirs with 👍 or add a comment instead of opening a new one.

For a bug, say which version you're running and how to make it happen again. The version is
under **Help > About MaevePaint**. A screenshot helps a lot, and so does `maevepaint.log` from
the folder under [Where things are saved](#where-things-are-saved).
