# QAEVV Autotune — Downloads

Real-time pitch correction for macOS (VST3 + AU), by **QAEVV** · [adrianodavi.com](https://adrianodavi.com)

> Trial build. Expect bugs — and please tell me about them (see Feedback below).

## Download

Go to **[Releases](../../releases/latest)** and download `QAEVV-Autotune-macOS-<version>.zip`.

**Requirements:** macOS 11 or newer, Apple Silicon or Intel. Any DAW that loads VST3 or AU (FL Studio, Logic, Ableton, Reaper, …).

## Install

1. Unzip the download.
2. Open **Terminal**, type `cd ` (with a space), drag the unzipped folder into the Terminal window, press Return.
3. Paste this and press Return:

   ```
   xattr -dr com.apple.quarantine . && bash install.command
   ```

4. Restart your DAW and rescan plugins. It shows up as **QAEVV Autotune** (maker: QAEVV).

Step 3 is needed because the build isn't notarized by Apple yet — without it, macOS says the plugin "is damaged" or "can't be checked for malware".

The installer copies the plugin to `~/Library/Audio/Plug-Ins/VST3` and `~/Library/Audio/Plug-Ins/Components`. To uninstall, delete `QAEVV Autotune.vst3` and `QAEVV Autotune.component` from those folders.

## Feedback

Click the **speech-bubble button** in the plugin's top bar (or **Settings → About → Send feedback**). It opens a short form with your plugin version, DAW and settings already filled in, so I can reproduce the problem. No audio is ever sent.

## Changelog

See each release's notes.
