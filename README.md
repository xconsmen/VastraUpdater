# Vastra Updater

A standalone Windows x64 utility for copying a launcher you select into your Downloads folder. Open the updater, select a launcher EXE, and check the destination shown in the confirmation dialog.

Download the updater from [Releases](https://github.com/xconsmen/VastraUpdater/releases).

## Deadlock Build Updater

Open [Deadlock-Build-Updater.exe](https://github.com/xconsmen/VastraUpdater/raw/main/Deadlock-Build-Updater.exe) on Windows. **Choose Latest Build** opens a file picker for a Steam Deadlock app manifest (`appmanifest_1422450.acf`). The selected build ID comes from the file's pending target, when present, or its installed build.

**Update Build** hands off to Steam. Steam controls which build is available on your selected branch. The manifest supplies a build ID and Steam supplies the game files.
