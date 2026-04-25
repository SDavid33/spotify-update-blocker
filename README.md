![GitHub release](https://img.shields.io/github/v/release/SDavid33/spotify-update-blocker)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![PowerShell](https://img.shields.io/badge/powershell-supported-blue)

# Spotify Update Blocker (Windows)

Prevent the Spotify Windows app from auto-updating.

## How it works

This script removes and locks the Spotify update folder, preventing the app from installing updates.

## Features

- Blocks Spotify auto updates
- Runs automatically at Windows startup
- No manual intervention required after setup
- Logs activity for debugging

## Installation

1. Download the files or clone the repository
2. Place both scripts in the same folder
3. Run `Install-SpotifyGuard.ps1` as Administrator

## Files

- `Run-SpotifyGuard.ps1` → main script
- `Install-SpotifyGuard.ps1` → sets up automatic startup

## Notes

- Windows only
- Requires PowerShell
- Spotify updates will be blocked until the script is removed

## Disclaimer

This is an unofficial workaround and may stop working if Spotify changes how updates are handled.

## Download

[Download latest release](../../releases/latest)


## Sponsor

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/N4N0XO52O)
