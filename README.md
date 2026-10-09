# Chat History

Desktop app for macOS and Windows that shows your local Claude Code and GitHub Copilot chat histories: prompts and answers, token usage per chat and per day, the commits you made with AI help, and an activity sheet you can paste into Excel. It only reads the chat files on your computer; nothing is sent anywhere unless you ask the AI to estimate a commit.

This repository holds only the downloads. Each release has the same three files:

| File | For |
|---|---|
| [ChatHistory-Mac.dmg](https://github.com/kavillo/chat-history-releases/releases/latest/download/ChatHistory-Mac.dmg) | Mac with Apple silicon (M1 or later) |
| [ChatHistory-Windows.zip](https://github.com/kavillo/chat-history-releases/releases/latest/download/ChatHistory-Windows.zip) | Windows, 64-bit Intel/AMD |
| ChatHistory-version.json | Used by the app to find new versions |

The links above always give the latest version. Older versions are on the [Releases](https://github.com/kavillo/chat-history-releases/releases) page.

## Install

- **Mac**: open the `.dmg` and drag Chat History to Applications. The app is not signed by Apple: the first time, right-click it and choose **Open**, or allow it in System Settings → Privacy & Security.
- **Windows**: expand the zip; it contains a `Chat History` folder. Start `Chat History.exe` inside it. Windows SmartScreen may warn the first time: choose **More info → Run anyway**. To update, replace the folder; your activity sheet is kept in `%APPDATA%\chat-history-viewer-windows`.

The app checks for new versions every 10 minutes and offers to download them; you install them yourself.
