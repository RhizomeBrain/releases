# Rhizome Brain

Releases of the Rhizome Brain desktop app, for Macs with Apple Silicon.

## Install

1. Download the latest `Rhizome-Brain_<version>_aarch64.dmg` from [Releases](https://github.com/RhizomeBrain/releases/releases/latest).
2. Open it and drag **Rhizome Brain** into **Applications**.
3. Open Rhizome Brain from Applications. The app is not signed yet, so macOS refuses it the first time: open **System Settings → Privacy & Security** and click **Open Anyway** beside Rhizome Brain, then confirm.

The app updates itself: when a new version is out, its menu-bar icon offers it.

## The `rhz` command

The app carries the `rhz` command-line tool. To run it from a terminal:

    sudo ln -s "/Applications/Rhizome Brain.app/Contents/MacOS/rhz" /usr/local/bin/rhz
