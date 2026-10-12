# Apollo downloads

Apollo is a desktop app for managing servers over SSH. This repository
only holds its release files; the source is private.

**Download:** open the [latest release](https://github.com/finlook/apollo-releases/releases/latest)
and pick:

- Windows: `apollo-windows-amd64-setup.exe` - installs for your user
  (no admin prompt). Apollo updates itself after that.
- macOS: `apollo-macos-universal.dmg` - open it and drag Apollo to
  Applications.

Each release also has `update.json`, which Apollo reads to find updates.
It's signed, and Apollo refuses anything that doesn't match.

Builds aren't code-signed yet: Windows may show SmartScreen ("More info"
-> "Run anyway"), and macOS needs right-click -> Open the first time.
