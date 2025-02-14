# Dotfiles

My dotfiles use the following: 
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
>[!NOTE]
> Since I use an Atomic Desktop, I use [Homebrew](https://brew.sh/) to install most commandline packages, see [Homebrew on Linux](https://docs.brew.sh/Homebrew-on-Linux) for insturctions. 
> Fish, Hyprland, Kitty, and Waybar are the exception as I install this via OS Packagement. 

1. Install all required packaged.
```bash
brew install atuin eza starship zoxide neovim stow
```
2. Install a Nerd Font FireCode
```
wget -P ~/.local/share/fonts https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/FiraCode.zip \
&& cd ~/.local/share/fonts \
&& unzip FiraCode.zip \
&& rm FiraCode.zip LICENSE README.md \
&& fc-cache -fv
```
3. Clone the repository
```bash
git clone https://github.com/eXsoR65/dotfiles.git ~/dotfiles
```
4. Change directory to ~/dotfile and run stow to link them. 
```bash 
cd ~/dotfiles && stow .
```

### Screenshot
![screenshot](screenshot.png)

