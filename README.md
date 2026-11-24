**English** | [日本語](README.ja.md)

# Zoyacdeck

A small button panel for Windows — a software stream deck you can keep anywhere on screen.
Open programs and websites, control music, mute your mic, switch audio devices, record the screen and more, with one click.

English · 한국어 · 日本語

## Download

Get `Zoyacdeck-<version>.zip` from **[the latest release](https://github.com/koishilab514/zoyacdeck/releases/latest)**, unzip it and run `Zoyacdeck.exe`. No installation needed.

- Windows 10 / 11 (64-bit)
- If Windows shows "Windows protected your PC" on first launch, click **More info → Run anyway**. It appears because this is an unsigned personal project.
- Virus scan: **[VirusTotal report for v1.0.5](https://www.virustotal.com/gui/file/b92630e11feff453e26f94568b91d87dab7f6b09152d261321c1b8b1f3cae65f)** as an example. Microsoft Defender, Kaspersky, Norton, Avast, Bitdefender and other major antivirus products report it clean. A few lesser-known engines flag it, which is common for small unsigned programs. To check the version you downloaded, upload the zip or exe to [virustotal.com](https://www.virustotal.com/).

## What it does

- **Open**: programs, folders, installed apps and websites. Drag desktop shortcuts or a browser address onto an empty slot.
- **Music**: previous / play-pause / next, plus a media bar with the track name and volume.
- **Sound**: output device and per-program volume panel, one-click device switching, mute a single program, mute your mic.
- **Record**: record the whole monitor, an area or a window, with just that program's sound if you like. GPU encoding keeps games smooth.
- **Capture**: area or window screenshots, saved as PNG and copied to the clipboard.
- **Shortcuts**: a button that presses a keyboard shortcut (Ctrl+S, Ctrl+Z, F5 and so on) in the window you're using. Handy for editing and document programs.
- **Widgets**: clocks, date, CPU / GPU / RAM usage, timer and stopwatch, scheduled PC shutdown, a memo calendar and monitor brightness.
- **Video**: play your own video files in a tile, on repeat.
- **Customize**: 5 color themes, your own pictures or animated GIFs on buttons, a background picture, up to 3 pages.

## Good to know

- Zoyacdeck presses keys in other programs only when you click a Shortcut button you added.
- The panel shows over windowed and borderless-fullscreen programs, not exclusive fullscreen.
- Recording needs the free tool ffmpeg. Settings > Record > "Get ffmpeg" downloads it from the official source.
- Language: follows your Windows language. Change it in Settings > General > Language.
- To quit: right-click the tray icon (four teal squares) in the bottom-right of the taskbar → Exit.
- Zoyacdeck checks for new versions once a day and updates with one click.
- See `README.txt` in the zip for full instructions.

## Support

Zoyacdeck is free. If it helps you, you can buy me a coffee ☕

[![Support me on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/koishi514)

## Contact

- Made by koishi514
- Questions and bug reports: [Issues](https://github.com/koishilab514/zoyacdeck/issues) or koishilab514@naver.com

## Changelog

### 1.0.6 (2026-11-24)

- With "always on top" off, clicking the panel now brings it in front of other windows. The window you were using stays active. Clicking another window sends the panel back behind it.

### 1.0.5 (2026-11-23)

- Fixed recording not starting with the latest ffmpeg (9.1). Older ffmpeg still works.
- Fixed recording turning into sound only (or stopping) when an administrator prompt or the lock screen appeared. Recording now shows "Briefly paused" while the screen is hidden and picks up again afterwards, saved as one file.
- Area recording can now be done without sound (Settings > Record > Sound > "Record area selection without sound").
- Fixed the page and hide box tooltips lingering or popping up at the mouse after you moved away. They now show right above the box and disappear as soon as you leave.
- With button names hidden, the timer and scheduled shutdown tiles also hide their names while idle and show a larger icon or time. While running, the end time still shows.

### 1.0.4 (2026-11-23)

- The zip now includes a Japanese guide (README-ja.txt). Settings > About > Open README opens it when the display language is Japanese.
- New Shortcut key button (Add button > Keyboard). Click the box and press the keys, or pick a common one such as Copy, Undo, Save or Bold. Clicking the button presses that shortcut in the window you're using, which is handy for editing and document programs. Win-key shortcuts work too (tick Win). Programs running as administrator only accept it when Zoyacdeck is also run as administrator.
- The app icon (four teal squares) is now centered. It used to sit one pixel off toward the bottom right, and its edges are sharper now.

### 1.0.3 (2026-11-23)

- New video tile. Add one video file, several, or a folder from your PC, and it plays on repeat in the tile (3 wide × 2 tall by default). Sound is off at first; scroll over it to change only this tile's volume. Click to pause or resume; next and previous video are in the right-click menu. It doesn't show up in the media bar or respond to media keys, and it stays sharp even if you lower the panel opacity. It pauses when the panel is hidden or you switch pages.
- You can now pick the timer alert volume for each button (100%, 75%, 50%, 25%, 10%).
- New Rows setting: 1, 2 or 3 rows (Settings > Panel). On a 1-row panel, tall buttons show as unavailable tiles and aren't deleted. 3 rows default to the smallest button size, and you can still resize them with Custom (remembered separately). When the panel is short, the page number boxes on the right fold into 2 columns.
- Button names can be hidden so icons show larger (Settings > Panel > Button names). By default names hide on 3 rows only, and hovering shows the name.
- The name sticker (rounded background behind names) can be turned on or off (Settings > Panel). The shutdown and timer tiles now get the same sticker, and short notices like "Volume 40" shrink to fit narrow tiles.
- Video tiles can now be 5 wide × 3 tall (for 3-row panels). New videos on a 3-row panel start at 5×3.
- Timer: entering 60 seconds or more turns into minutes automatically (100 sec → 1 min 40 sec).

### 1.0.2 (2026-11-23)

- New monitor brightness button. Scroll over it to change brightness by 5%, or click it to go 30% → 60% → 100%. Change all monitors at once or pick one. External monitors need DDC/CI turned on in the monitor's menu.
- New calendar button. Click it to open a calendar where you can write a memo for each day. A red dot appears on the button when today has a memo. Add a background picture from "Background" at the top of the calendar.

### 1.0.1 (2026-11-22)

- The panel now snaps to screen edges when you drag it near them. It snaps to both sides in a corner and stays clear of the taskbar. Keep dragging to pull it away. You can turn this off in Settings > General > Position.
- Scrolling the button editor no longer changes drop-down lists (size, sound and more) or number boxes when the pointer passes over them. They change only when you click.

### 1.0.0 (2026-11-22)

- First release.
