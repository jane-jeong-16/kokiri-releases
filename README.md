# Kokiri — downloads

A lightweight **PostgreSQL & MySQL** desktop client with an AI query assistant.
This repo hosts the release downloads and the auto-update feed. (The source code
is private.)

## Download

**[⬇︎ Latest release](https://github.com/jane-jeong-16/kokiri-releases/releases/latest)** — macOS (Apple Silicon)

Grab the `Kokiri-<version>-arm64.dmg`.

## Install (macOS, Apple Silicon)

Kokiri isn't notarized by Apple yet, so macOS blocks it on first launch. It's
safe to open — here's how:

1. Open the `.dmg` and drag **Kokiri** to **Applications**.
2. In **Terminal**, run:
   ```sh
   xattr -cr /Applications/Kokiri.app
   ```
3. Open Kokiri normally.

You only need step 2 once. (No-Terminal alternative: try to open it, then
**System Settings → Privacy & Security → Open Anyway**.)

## Updating

Kokiri checks for updates on launch and shows an in-app banner when a newer
version is available.

---

Requires Apple Silicon (`uname -m` → `arm64`). Bring your own Anthropic API key
for the AI assistant — your data stays on your machine; only schema is sent.
