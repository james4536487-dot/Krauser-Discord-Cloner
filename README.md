# Krauser Discord Cloner

A modern application for cloning and backing up Discord servers.
Dark interface, secure token storage, auto-update.

![version](https://img.shields.io/badge/version-4.2.0-blue)
![platform](https://img.shields.io/badge/platform-Windows-lightgrey)

---

## Features

- **Cloning** — a complete copy of the server (roles, channels, emojis, stickers, webhooks, etc.)
- **Synchronization** — add only missing objects without deleting anything
- **Cleanup** — complete removal of server content
- **Backup and restoration** — saving the server structure to a file
- **Auto-backup** before deletion — insurance for your data
- **Configuration profiles** — saved sets of parameters
- **Operation history** — log of all actions
- **9 color themes**, light/dark theme, Russian and English languages
- **Auto-update** via GitHub

---

## Installation

1. Download **`KrauserCloner-Setup.exe`** from the [Releases](https://github.com/james4536487-dot/Krauser-Discord-Cloner/releases/tag/v4.2.0) section
2. Run the installer and follow the setup wizard
3. Launch the application from the desktop or the Start menu

---

## Security

- The token is encrypted via **Windows DPAPI** and tied to your account —
  even if the file is copied, the token cannot be decrypted on another PC.
- A backup copy is automatically created before data deletion.

---

## Requirements

- Windows 10 / 11
- Microsoft Edge WebView2 (usually already installed on the system)

---

## Warning

⚠️ This program works with your personal Discord token — essentially, as a self-bot. Discord forbids this, and your account can be banned for it.
The author is not responsible for your account being banned. By downloading and running the cloning, you do so at your own risk and agree that the author is not to blame if something happens to your account.

💡 Tip: use a spare account that you don't mind losing. And after cloning, just transfer the server rights to your main account. 

---

*© Krauser*
