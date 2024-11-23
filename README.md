# Dotfiles

My dotfiles are for the following: 
 - Fish Shell
    - Atuin (Shell history replacement)
    - Eza (ls replacement)
    - Starship (Shell prompt)
    - Zoxide (cd replacement) 
 - Hyprland
 - Kitty
 - Neovim
 - Waybar

## To use my dotfiles
> Note: Since I use an Atomic Desktop, I use homebrew to install most commandline packages.
> Fish, Hyprland, Kitty, Neovim, and Waybar are the exception as I install this via OS Packagement. 

1. Install all required packaged.
```bash
brew install atuin eza starship zoxide
```
2. Make sure that you have GNU Stow installed.
if not install with brew:
```bash
brew install stow
```

3. Clone the repository
```bash
git clone git@github.com:eXsoR65/dotfiles.git ~/dotfiles
```

4. Change directory to ~/dotfile and run stow to link them. 
```bash 
cd ~/dotfiles && stow .
```

### Screenshot
![screenshot](screenshot.png)

