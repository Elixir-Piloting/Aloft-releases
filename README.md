# Aloft

A macOS-style top bar for Windows.

Download the Windows x64 installer from [Releases](https://github.com/Elixir-Piloting/Aloft-releases/releases).

This repository contains only published installers, updater signatures and the automatically maintained `update.json` manifest. Aloft source code is private.

The release workflow publishes an installer before updating the manifest. `update.json` is created by the first successful release and records the latest version, release notes, signature, download URL, date and version history.

Release notes use standard JSON `\n` newlines. The application checks for updates on startup and from Settings ? About, and shows notes for newer versions. Installation is always user initiated.
