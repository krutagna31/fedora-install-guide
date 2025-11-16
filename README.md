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

- [workspace shortcut conflict](<https://askubuntu.com/questions/1193090/what-is-hidin(g-ctrl-shift-alt-up-down)>)

## command line tools

- [vim](https://fedoraproject.org/wiki/Vim)

- [git](https://www.theodinproject.com/lessons/foundations-git-basics)

  ```bash
  # changing commit message editor to vs code
  git config --global core.editor "code --wait"
  ```

- [node.js](https://www.theodinproject.com/lessons/foundations-installing-node-js)

