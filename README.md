# fedora install

This repository contains my fedora linux install list, including system configurations, fonts, wallpapers and essential applications.

## system configurations

- [rpm fusion](https://docs.fedoraproject.org/en-US/quick-docs/rpmfusion-setup/)

- [multimedia](https://docs.fedoraproject.org/en-US/quick-docs/installing-plugins-for-playing-movies-and-music/)

- ffmpeg

  ```bash
  # swap the free version with full ffmpeg package
  sudo dnf swap 'ffmpeg-free' 'ffmpeg' --allowerasing
  ```

- [build essential](https://unix.stackexchange.com/questions/1338/what-is-the-fedora-equivalent-of-the-debian-build-essential-package)

- [keyd](https://github.com/rvaiya/keyd)

- [fuse](https://github.com/appimage/appimagekit/wiki/fuse)

- [jetbrains mono](https://www.jetbrains.com/lp/mono/)

- [workspace shortcut conflict](<https://askubuntu.com/questions/1193090/what-is-hidin(g-ctrl-shift-alt-up-down)>)

## command line tools

- [git](https://www.theodinproject.com/lessons/foundations-git-basics)

  ```bash
  # changing commit message editor to vs code
  git config --global core.editor "code --wait"
  ```

- [node.js](https://www.theodinproject.com/lessons/foundations-installing-node-js)

- [vim](https://fedoraproject.org/wiki/Vim)

## applications

- [bitwarden](https://flathub.org/en/apps/com.bitwarden.desktop)

- [discord](https://discord.com/download)

- [extension manager](https://flathub.org/en/apps/com.mattjakeman.ExtensionManager)
  - alphabetical app grid

- [google chrome](https://support.google.com/chrome/a/answer/9025903?hl=en)

- [obsidian](https://flathub.org/en/apps/md.obsidian.Obsidian)

- [open tablet driver](https://opentabletdriver.net/Wiki/Install/Linux)

- [postman](https://flathub.org/en/apps/com.getpostman.Postman)

- [telegram](https://flathub.org/en/apps/org.telegram.desktop)

- [ticktick](https://ticktick.com/download?language=en_US)

- [vlc](https://docs.fedoraproject.org/en-US/quick-docs/installing-and-running-vlc/)

- [vivaldi](https://help.vivaldi.com/desktop/install-update/install-the-vivaldi-browser/)
    ```bash
    # forcing dark mode
    sudo nano /usr/share/applications/vivaldi-stable.desktop
    Exec=/usr/bin/vivaldi-stable %U --force-dark-mode --enable-features=WebUIDarkMode
    ```
- [vs code](https://code.visualstudio.com/docs/setup/linux)

## app images
- [openrgb](https://openrgb.org/#downloads)

## wallpapers
- [macos monteroy](https://4kwallpapers.com/gradients/macos-monterey-wwdc-21-stock-dark-mode-5k-5585.html)