# PS Streamer

A simple PlayStation 5 Remote Play client for macOS (Apple Silicon), with a 1080p default and a configurable resolution and bitrate.

PS Streamer is a modified version of [chiaki-ng](https://github.com/streetpea/chiaki-ng), which is itself based on Chiaki by thestr4ng3r.
It is licensed under the **GNU Affero General Public License v3** (see `COPYING`), and its source code is available in this repository.

This project is not endorsed or certified by Sony Interactive Entertainment LLC. "PlayStation" is a trademark of Sony Interactive Entertainment Inc.

## Changes from chiaki-ng
- PS5 streams default to 1080p (also when streaming away from home) with a 30 Mbps bitrate at 1080p.
- PS5 frame rate is always requested at the protocol maximum (60 fps); the console sends the game's actual frame rate.
- Steam shortcut features are disabled in the macOS build.
- Renamed to "PS Streamer".
