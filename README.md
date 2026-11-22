# Codex: a Pi Pocket theme

A Codex desktop app-inspired theme for [Pi Pocket](https://github.com/TannerMidd/pi-pocket).
Neutral greys, soft message bubbles, quiet one-line tool calls, and a rounded message box.
Pi Pocket keeps its own π mark.

- Dark and light palettes. The paired **Codex** colors follow the system's light or dark setting.
- Your messages appear on the right. Other people's messages appear on the left with their names.
- Tool calls expand to show their details. Failed, waiting, denied, and stopped calls keep their status marks.
- Text uses Pi Pocket's bundled Inter font, or the Apple system font in supporting browsers.
  Code uses available system monospace fonts, with Pi Pocket's fonts as fallbacks.
- CSS only: no JavaScript, external requests, bundled fonts, images, or telemetry.
- Requires Pi Pocket **0.20.0 or later**, with `themeApi` **1**.

## Install

Copy the `codex/` folder into `~/.pi-pocket/themes/` (or `themes/` inside your `PI_POCKET_DIR`).
Then choose **Codex** in Appearance → Theme.

The theme has been submitted to the public gallery. After its index entry is merged,
you can also install it from Menu → Extensions → Discover → Themes → Codex.
Installing from the gallery does not apply it; choose it in Appearance afterward.

You can choose other colors while keeping the layout. To return to the default layout,
choose **Pocket** in Appearance. If a theme makes the app difficult to use,
open the app with `?noext=1` to enter safe mode.

## Files

- `codex/theme.json`: theme metadata.
- `codex/theme.css`: imports the layout.
- `codex/layout.css`: tokens and layout rules.
- `codex/colors.toml`: dark palette.
- `codex/colors-light.toml`: light palette.

The theme uses Pi Pocket's theme tokens and `data-part` selectors. Its home action
button styling also uses the app's `.button` and `.primary` classes, which can change
between Pi Pocket releases.

## License and attribution

MIT. See [LICENSE](LICENSE). The license covers this theme's CSS, palettes, and documentation.
No third-party fonts or artwork are distributed in this repository. Fonts supplied by
Pi Pocket or the operating system retain their own licenses.

This is an independent theme by Tanner Middleton. It is not affiliated with or endorsed
by OpenAI. Codex is a name used by OpenAI; the name describes the visual inspiration
and does not imply ownership of OpenAI's software, branding, or assets.
