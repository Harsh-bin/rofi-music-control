# rofi-music-control
**Works on all player ( local players like `mpv` `vlc`, `browsers`, `spotify`....)**

## Features
- Displays currently playing track info
- Shows album artwork
- Automatic fallback for missing artwork
- Support for multiple media players `smartly handles multi playback`
- Playback control buttons
- Desktop notification with icon as artwork

**Preview**
| | |
|--|--|
| **Local player `fallback albumart`** ![](preview/p1.png) | **Spotify** ![](preview/p2.png) |
| | |
| **Browsers** ![](preview/p4.png) | **Notifications** ![](preview/p3.png) |

## Installation

> [!CAUTION]
> The bash script is configured to use `~config/rofi/nowplaying` as default path. So, you can use the suggested installation step or modify it as needed.
```
# --- Configuration ---
art_file="$HOME/.config/rofi/nowplaying/album_art.png"
fallback_art_file="$HOME/.config/rofi/nowplaying/fallback_album_art.png"
rofi_theme="$HOME/.config/rofi/nowplaying/nowplaying.rasi"
cache_file="$HOME/.config/rofi/nowplaying/song_title.cache"
```


1. Create the required directories:
```bash
mkdir -p ~/.config/rofi/nowplaying
```
2. Clone this repository:
```bash
git clone https://github.com/Harsh-bin/rofi-music-control ~/.config/rofi/nowplaying
```
3. Make the script executable:
```
chmod +x ~/.config/rofi/nowplaying/nowplaying.sh
```
**All set. Now, you need to add keybindings or other controls to launch the `nowplaying.sh`.**

## Author ✍️

Created by [Harsh-bin](https://github.com/Harsh-bin)

My waybar and rofi config with matugen [config](https://github.com/Harsh-bin/waybar-config)

---
**Enjoy! 🎉**


