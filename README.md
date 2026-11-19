# Phosphor

**Steam as a tiling terminal on a phosphor CRT.** A [Millennium](https://steambrew.app) theme for the Steam client.

![Phosphor: library](media/library.gif)

- **A tiling layout:**
  - Two panes, *library* and *main*, sit edge to edge with box-drawing borders and inset titles (`┤ library ├`).
  - A one-line title row at the top: `[phosphor] [view] [friends] [games] [help]` and `user@name`.
  - A **tmux-style status line** along the bottom: `[steam] 0:store 1:library* 2:community 3:you`, the dock as `[+add] [dl] [friends]`, and uptime, date and clock.
- **One color, many brightnesses:**
  - Everything is monospace and glows.
  - The selected game is in **reverse video**, and installed games are marked `*`.
  - Section headings read `## name_` with a blinking cursor, and Play is `$ ./play`.
  - Covers and art turn monochrome phosphor (optional).
- **A real command line:** press **:** and type `library`, `store`, `downloads`, `friends`, `find <name>` to filter the game list, `clear`, or `help`.
- **CRT:** scanlines, a slow roll bar, a curved-glass vignette, a gentle flicker, and a power-on self test when Steam opens.

![Phosphor: game page](media/gamepage.gif)

## Install

1. Install [Millennium](https://steambrew.app).
2. Find **Phosphor** in the Millennium theme browser, or download this repository into `Steam/millennium/themes/Phosphor`.
3. Open **Steam → Millennium → Themes** and pick **Phosphor**.

## Options

Open **Millennium → Themes → Phosphor** to change:

Phosphor (Green, Amber, White, Ice, Rose) · Images (Monochrome / Color) · Scanlines (Normal / Heavy / Off) · Density · What's New · Readout · Startup screen · Motion · Privacy

Everything here is original: no other game's names, logos, art or fonts. Fonts are ones that ship with Windows.

## License

MIT, see [LICENSE](LICENSE).
