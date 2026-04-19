vaultkeeper-releases
---------------------

>  Releases here will only include the Windows compiled version. Linux and macOS build versions are triggered by GitHub Actions, so please download them from the source [release](https://github.com/vault-keeper/desktop-app/releases) .

A privacy-focused, offline-first personal vault application for managing accounts, bookmarks, notes, and media — all encrypted locally on your device.

[Source Code](https://github.com/vault-keeper/desktop-app) | [Why vault-keeper?](https://github.com/AI-Star-Dev/vaultkeeper-releases/issues/1)

## Changelog

### 1.0.0 release (2026-04-15)

- first version released 
- add macOS build trigger by GitHub Action

### 1.0.1 release (2026-04-16)

- fix account search
- add report search
- add Linux build trigger by GitHub Action

### 1.0.2 release (2026-04-16 16:30 UTC+8)

- add check for updates feature
- single instance restriction

### 1.0.3 release (2026-04-16 21:00 UTC+8)

- remove BIP39 mnemonic recovery phrase
- fix critical bug in change_master_password
- add encrypted backup export/import (.vkbak format)
- handle workspace name conflicts on import

### 1.0.4 release (2026-04-17)

- Make settings route to work without an active workspace
- Auto-close import modal and add loading protection to settings modals
- Fix some bugs

## Features

- **Account Management** — store and organize credentials with encrypted fields
- **Bookmarks** — save and categorize web links with notes
- **Notes** — write and organize markdown notes
- **Media** — manage and reference local media files
- **Reports** — remember your work by daily or weekly report
- **Tags** — tag and filter content across all categories
- **Workspace** — multi-workspace support with isolated storage
- **Lock Screen** — master-password protection with Argon2 hashing and AES-GCM encryption


## Screenshots

![main](screenshots/main.png)

![workspace](screenshots/workspace.png)

![bookmark](screenshots/bookmark.png)

![account](screenshots/account.png)

![note](screenshots/note.png)

![report](screenshots/report.png)

![media](screenshots/media.png)
