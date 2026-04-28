# NAVIS — Clawd on Desk Theme

A custom theme for [Clawd on Desk](https://github.com/rullerzhou-afk/clawd-on-desk) featuring **NAVIS** — a tsundere IT consultant pixel-art chibi mascot.

![NAVIS idle](assets/navis-idle.gif)

## Features

- **11 states** — idle, thinking, working, juggling, error, attention, notification, sleeping, waking, carrying, sweeping
- **4 animated GIFs** — idle (breathe + blink), working (typing), thinking (eye-shift), sleeping (breath)
- **7 idle animations** — look-left, look-right, stretch, yawn, smug, headphones-adjust, hair-flip
- **5 reactions** — clickLeft, clickRight, drag, double-click, annoyed (eye-roll)
- **3 working tiers** — typing → juggling → tier3 (multi-monitor) based on concurrent session count

## Install

1. Locate your Clawd themes directory:
   - **macOS**: `~/Library/Application Support/clawd-on-desk/themes/`
   - **Windows**: `%APPDATA%\clawd-on-desk\themes\`
   - **Linux**: `~/.config/clawd-on-desk/themes/`

2. Clone this repo into a `navis/` subfolder:
   ```bash
   git clone https://github.com/arousal-takuya/clawd-on-desk-navis-theme.git \
     "$HOME/Library/Application Support/clawd-on-desk/themes/navis"
   ```

3. In Clawd: **Settings → Theme → NAVIS** to select.

## Character

NAVIS is a tsundere IT consultant character — confident, sharp-tongued, wearing white over-ear headphones with mic, beige oversized hoodie with orange interior, and a small paw-print logo. Inspired by the Asuka Langley archetype.

## Built with

- [gpt-image-2](https://platform.openai.com/docs/guides/images) (via Codex CLI built-in `image_gen` tool) for sprite generation
- [PIL/Pillow](https://pillow.readthedocs.io/) for chroma-key removal and GIF assembly

## License

MIT — see [LICENSE](LICENSE). Theme assets are user-generated content under MIT. Clawd on Desk itself is AGPL-3.0 by [@rullerzhou-afk](https://github.com/rullerzhou-afk).
