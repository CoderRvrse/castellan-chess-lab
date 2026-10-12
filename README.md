# Castellan Chess Lab

Downloads for Castellan Chess Lab, an offline chess analysis and training app for Windows. It
runs Stockfish 19 as a native program, reviews finished games and plays training games.

## Download

The newest installer is on the [Releases page](https://github.com/CoderRvrse/castellan-chess-lab/releases/latest),
named `Castellan_<version>_x64-setup.exe`. It installs for your Windows user and needs no
administrator rights.

The installers are not code-signed yet, so Windows shows an "Unknown publisher" warning
(*More info*, then *Run anyway*). GitHub shows each file's SHA-256 beside it on the release
page. To compare it with your download, in PowerShell:

    Get-FileHash .\Castellan_<version>_x64-setup.exe

## Updates

An installed Castellan asks this repository for the newest version when it starts. You can
switch that off at the bottom of its window. It installs an update only when you say so, and
only if the download carries the project's update signature. `latest.json` in each release is
the small file it reads.

## What is here

Released installers only. The source code is not in this repository.

Castellan bundles Stockfish 19, which is licensed under the GNU GPL v3. Its licence and full
source code are installed with the app, in the `stockfish` folder of the install folder, and
are also at https://github.com/official-stockfish/Stockfish/tree/sf_19.

Castellan is for analysing positions you set up and games that are finished. It has no
live-game mode.
