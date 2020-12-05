![SS](/Other/df.png)

<img alt="Visits" src="https://badges.pufler.dev/visits/ilham25/dotfiles?style=flat-square&label=&color=success&logo=GitHub&logoColor=white&labelColor=373e4d"/>
<img alt="Repo Size" align="right" src="https://github-size-badge.herokuapp.com/ilham25/dotfiles.svg"/>

## :art: Screenshot

> :link: **All Theme** > ![SS](/Other/dot.gif)

## :snowflake: My Setup :snowflake:

- **WM :** i3-gaps
- **Terminal :** urxvt
- **Shell :** zsh
- **Panel :** tint2
- **Notification :** dunst
- **App launcher :** rofi
- **File manager :** thunar

## :wrench: Installation

### :computer: **Arch Based (Dependencies)**

> :exclamation: For AUR helper, im using **yay**

> :page_with_curl: **i3 Windows Manager**

```bash
sudo pacman -S i3-gaps
```

> :sound: **Audio**

```bash
sudo pacman -S alsa-utils pulseaudio
```

> :high_brightness: **Brightness**

```bash
yay -S brightnessctl
```

> :chart_with_upwards_trend: **Network Monitor & RAM Usage**

```bash
yay -S psuinfo
```

> :signal_strength: **Wireless Tools**

```bash
sudo pacman -S wireless_tools
```

> :hammer: **Other utility (panel, notification, terminal, file manager, etc)**

```bash
yay -S dunst tint2 gsimplecal rofi feh lxappearance qt5ct qt5-styleplugins lxsession xautolock rxvt-unicode-patched xclip scrot thunar thunar-archive-plugin thunar-media-tags-plugin thunar-volman tumbler w3m geany nano vim viewnior pavucontrol parcellite neofetch htop picom-ibhagwan-git gtk2-perl xfce4-power-manager zsh zsh-completions imagemagick playerctl networkmanager-dmenu
```

> :diamonds: **oh-my-zsh & plugins**

- ```bash
  chsh -s /usr/bin/zsh # Change default shell to zsh for current user
  ```

- ```bash
  sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
  ```

- ```bash
  git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
  ```

- ```bash
  git clone https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
  ```

## :wrench: Dotfiles Install

> :file_folder: **General Config**

- ```bash
  git clone https://github.com/ilham25/dotfiles
  ```

- ```bash
  cd dotfiles/ && cp -r {.*,*} ~/
  ```

- ```bash
  rm -r ~/{README.md,LICENSE,.git} # Delete unnecessary files
  ```

> :nut_and_bolt: **Icons**

- ```bash
  cd ~/.icons/
  ```
- ```bash
  tar -Jxvf Papirus-Custom.tar.xz && tar -Jxvf Papirus-Dark-Custom.tar.xz && tar -Jxvf oomox-megumi.tar.xz && tar -Jxvf oomox-oreki.tar.xz && tar -Jxvf oomox-frosted.tar.xz
  ```

- ```bash
  sudo cp -r {Papirus-Custom,Papirus-Dark-Custom,oomox-megumi,oomox-oreki,oomox-frosted} /usr/share/icons/
  ```

- ```bash
  rm -r ~/.icons/{Papirus-Custom,Papirus-Dark-Custom,oomox-megumi,oomox-oreki,oomox-frosted,*.tar.xz} # Delete unnecessary files
  ```

> :bulb: **Refresh font cache**

```bash
fc-cache -rv
```

## :clap: How to change theme

> **Run this command and choose the theme index**

```bash
cht
```

![SS](/Other/cht.png)

## :black_square_button: Keybinds

| Key                                                                         | Action                                  |
| --------------------------------------------------------------------------- | --------------------------------------- |
| <kbd>Mod + C                                                                | Close Windows                           |
| <kbd>Mod + Z (release) + :arrow_up:/:arrow_down:/:arrow_left:/:arrow_right: | Resize Windows - Tiling                 |
| <kbd>Mod + Shift + :arrow_up:/:arrow_down:/:arrow_left:/:arrow_right:       | Move Windows - Tiling                   |
| <kbd>Mod + Shift + Space                                                    | Switch between tiling/floating          |
| <kbd>Mod + Left Click (hold)                                                | Move Windows - Floating                 |
| <kbd>Mod + Right Click (hold)                                               | Resize Windows - Floating               |
| <kbd>Mod + 1/2/3/4/5/6/7/8/9/0                                              | Change Workspace                        |
| <kbd>Mod + Shift + 1/2/3/4/5/6/7/8/9/0                                      | Move active windows to workspace number |
| <kbd>Mod + E                                                                | Open file manager                       |
| <kbd>Mod + R                                                                | App launcher                            |
| <kbd>Mod + L                                                                | Lock Screen                             |
| <kbd>Mod + Return                                                           | Open terminal                           |
| <kbd>Mod + Shift + E                                                        | Power Menu                              |
| <kbd>Mod + Shift + R                                                        | WM Restart                              |
| <kbd>Mod + Print                                                            | Screenshot Menu                         |
| <kbd>Mod + H                                                                | Change Tiling direction (Horizontal)    |
| <kbd>Mod + J                                                                | Change Tiling Direction (Vertical)      |

## :heart: Credits

- [i3wm Wiki](https://i3wm.org/docs/userguide.html)
- [@owl4ce](https://github.com/owl4ce/)
- [@nwg-piotr - psuinfo](https://github.com/nwg-piotr)
- [@horst3180 - Arc Dark Theme](https://github.com/horst3180/arc-theme)
- [ZorinOS theme](https://github.com/ZorinOS/zorin-desktop-themes)
- [Persona Wallpaper](https://wall.alphacoders.com/big.php?i=756850)
- [Katou Megumi Wallpaper](https://wall.alphacoders.com/big.php?i=908221)
- [Hyouka Wallpaper](https://wall.alphacoders.com/big.php?i=994176)
- [Frosted Wallpaper](https://wallpaperaccess.com/minimalist-mountain)
