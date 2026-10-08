# Octopuses Are Aliens

An investigation by Megan into the greatest cover-up in human history. Every fact is real. Every conclusion is not.

A 19-slide narrated web presentation. Each slide has an optional narration player. Turn on **Auto-play deck** to have the narration play and advance through every slide.

## View it

Open `index.html` through GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## Controls

| Key | Action |
| --- | --- |
| `←` / `→`, `PgUp` / `PgDn` | Previous / next slide (works with presentation clickers) |
| `Space` | Play or pause narration |
| `F` or the ⛶ button | Full screen. Controls hide after 2.5 seconds; move the mouse to bring them back. Double-click the slide also works. |

## Perform it live

1. Open the page and click **Present live**. The presenter view opens in a second window.
2. Drag the audience window (`index.html`) to the projector or TV and press `F` for full screen.
3. Read from the presenter view on your laptop. It shows the script one sentence per line, red **pause** cues for the dramatic beats, the current and next slide, and a timer with a target time per slide.

Advancing in either window moves both. In the presenter view: `T` starts or pauses the timer, `R` resets it, and `+` / `−` change the script size.

Swipe works on phones. Link to a specific slide with `#N`, for example `index.html#5`.

## Contents

- `slides/`: 19 slides as WebP, plus thumbnails. Slides tagged **Lab report** (5, 6, 9, 13, 17) were added to Megan's original 14.
- `audio/`: one MP3 narration per slide.
- `index.html`: the viewer.
- `presenter.html`: the presenter view with the live script and timer.
- `slides.js`: the slide list and narration script, shared by both pages. Edit the script here.

No build step, no dependencies.

## Credits

- Narration: synthetic voice from [Kokoro](https://github.com/hexgrad/kokoro) text-to-speech (voice `bm_george`, Apache-2.0 model), written in the style of a nature documentary. Not any real person's voice.
- Fonts: Anton, Space Mono, and DM Sans from Google Fonts.
- Sources are listed at the bottom of the page.
