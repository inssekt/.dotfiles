
# .dotfiles

My personal dotfiles I use for my Arch Linux system.


## Requirements

These are the programs you need for the dotfiles to work.

```bash
  yay -S stow fish kitty hyprland waybar wofi visual-studio-code-bin noto-fonts-main noto-fonts-emoji ttf-font-awesome ttf-jetbrains-mono-nerd
  curl https://raw.githubusercontent.com/oh-my-fish/oh-my-fish/master/bin/install | fish
```

## Installation

GNU stow is a symlink farm manager.
Using the command `stow` it will create a symlink from the .dotfiles config folder to your ~/ folder.

To use my dotfiles, do the following.

```bash
  git clone https://github.com/inssekt/.dotfiles.git
  cd .dotfiles
  stow <program_name>
```

For example, if you wanted to use my hyprland config you would run `stow hypr`. This would symlink `.dotfiles/hypr/.config/hyprland` to `~/.config/hypr/hyprland`
    
## Screenshots

![App Screenshot](https://i.imgur.com/w23u4xr.png)

