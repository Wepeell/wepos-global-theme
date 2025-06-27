# WepOS Global Theme
This is a global theme for KDE Plasma intended for my personal custom image of Bazzite: [WepOS](https://github.com/Wepeell/wepos)

It is essentially just a theme variant with my preferred defaults based on Aurora, Bazzite, BreezeDark and Vapor.

## Requirements
- [plasma5-wallpapers-dynamic](https://github.com/zzag/plasma5-wallpapers-dynamic)

## Install

1. Download the `com.github.wepos.desktop` folder from this repository.

2. Move the folder to one of the following locations, depending on your intended scope:

   - Per-user installation:
     ```bash
     ~/.local/share/plasma/look-and-feel/com.github.wepos.desktop
     ```

   - System-wide installation:
     ```bash
     /usr/share/plasma/look-and-feel/com.github.wepos.desktop
     ```

3. Set your default wallpaper
   - Open the file:
     ```bash
     org.kde.plasma.folder.js
     ```
   - Modify it to point to your desired wallpaper file path:
     ```bash
     applet.writeConfig("Image", "file:///path/to/wallpaper/file.avif")
     ```
     _Note: A wallpaper is not included in this repository._
