# FocusTime

FocusTime is a lightweight Windows app for tracking time spent in foreground applications. It counts the active window rather than background processes and pauses tracking after a configurable period of inactivity.

## Features

- Daily, weekly, monthly, yearly, all-time, and custom date-range reports.
- A scrollable calendar with a five-year minimum history range, extended to older recorded data, and lazy browsing up to 50 years ahead.
- Customizable Liquid Glass rendering with adjustable quality and refresh rates, plus a dark matte mode.
- Automatic performance adaptation and a diagnostics view.
- Nine interface language choices: Ukrainian, English, Spanish, Japanese, German, French, Brazilian Portuguese, Simplified Chinese, and Russian.
- Optional Windows startup, always-on-top and start-minimized options, and global shortcuts.
- CSV export and manual backups.

## Run

1. Extract the ZIP archive to a folder.
2. Run `FocusTime.exe`.

No installer or administrator privileges are required. The app is built for 64-bit Windows 10 and Windows 11 and uses Windows' built-in WPF/.NET Framework components.

## Shortcuts

- `Ctrl+Alt+F` — show or hide the app window.
- `Ctrl+Alt+S` — save a PNG screenshot of the rendered window, including its current glass frame.

The shortcuts are registered globally when available. Their registration status is shown in **Settings > Hotkeys**.

## Screenshots and glass

Live glass captures the desktop behind the app. To prevent the app from capturing itself and producing a recursive image, the window is excluded from standard screenshot and screen-recording APIs by default. Use `Ctrl+Alt+S` to save a PNG of the rendered app with glass. The **Hide window in screenshots** option can be disabled in **Settings > Liquid Glass**; in that mode live background capture is turned off to avoid self-capture artifacts.

## Local data and privacy

Usage history and settings stay on the current Windows account in `%APPDATA%\FocusTime`. The distribution ZIP contains only the application, icon, and documentation; it does not include personal usage history or settings.
