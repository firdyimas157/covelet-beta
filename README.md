# Covelet beta

Covelet is a macOS utility that lives around the MacBook notch: the date and time beside it, and a panel that drops down on hover with your agenda, clipboard history, daily notes, Drop (files and nearby devices), music, Pomodoro, device stats, world clock, and AI coding tool usage.

Everything stays on your Mac. No account, no login, no analytics.

This repository is for beta testers: download builds from **Releases** and report problems in **Issues**. The app's source code is not published here.

## Install

Requires macOS 26.

1. Download the latest `Covelet-<version>.dmg` from [Releases](../../releases).
2. Open the DMG and drag Covelet to Applications.
3. Open Covelet. If macOS says it can't be verified, go to System Settings → Privacy & Security and click **Open Anyway**. (Needed until builds are notarized.)
4. A welcome card drops down from the notch. Rest the pointer on the notch any time to open the panel; Settings and Quit are in the last tab.

On Macs without a notch, or with only an external display, the bar sits at the top centre of the menu bar.

## Report a problem

In Covelet: Settings → General → About → **Send Feedback**. It opens a new issue here with your Covelet and macOS versions filled in. Screenshots help a lot.

Please don't include passwords, private notes, or anything you copied that you wouldn't want public: issues here are public.

## What leaves your Mac

- Lyrics lookups: the song's title, artist, and album go to lrclib.net. Switch this off in Settings → General → Privacy.
- Spotify cover art loads from Spotify.
- Files you send go straight to devices on your own Wi-Fi.

Nothing else.

## Uninstall

Switch off Launch at login (Settings → General), Quit Covelet, and drag it to the Trash. Notes stay in your notes folder (Documents/Covelet Notes by default); Settings → About → Data folder holds the rest.
