<img alt="Visits" src="https://badges.pufler.dev/visits/13atm01/dotfiles?style=flat-square&label=&color=success&logo=GitHub&logoColor=white&labelColor=373e4d"/> 
<img alt="Repo Size" align="right" src="https://github-size-badge.herokuapp.com/13atm01/dotfiles.svg"/>

## :art: Screenshot

> :link: **Theme 1**  ![SS](/Other/Violet(1).png)
> :link: **Theme 2**  ![SS](/Other/Violet(2).png)

## :computer: My Setup :computer:

- **OS :** Fedora 32
- **DE :** KDE Plasma
- **Terminal :** kitty
- **Shell :** zsh
- **Panel :** tint2
- **App launcher :** rofi
- **File manager :** dolphin

## :wrench: Dotfiles Install

> :file_folder: **General Config**

- ```bash
  git clone https://github.com/13atm01/dotfiles
  ```

- ```bash
  cd dotfiles/ && cp -r {.*,*} ~/
  ```

- ```bash
  rm -r ~/{README.md,LICENSE,.git} # Delete unnecessary files
  ```
  
## :wrench: Installation

> :bulb: **App launcher rofi**

:penguin: *Fedora*

- ```bash
  sudo dnf install rofi
  ```

:penguin: *Debian/Ubuntu*

- ```bash
  sudo apt-get install rofi
  ```

> :information_source: **Panel tint2**

:penguin: *Fedora*

- ```bash
  sudo dnf install tint2
  ```

:penguin: *Debian/Ubuntu*

- ```bash
  sudo apt-get install tint2
  ```
  
> :computer: **Terminal kitty**

:penguin: *Fedora*

- ```bash
  sudo dnf install kitty
  ```

:penguin: *Debian/Ubuntu*

- ```bash
  sudo apt-get install kitty
  ```

> :gear: **Shell zsh**

:penguin: *Fedora*

- ```bash
  sudo dnf install zsh
  ```
- ```bash
  chsh -s $(which zsh)  #change default shell to zsh
  ```
  
:penguin: *Debian/Ubuntu*

- ```bash
  sudo apt-get install zsh
  ```
- ```bash
  chsh -s $(which zsh)  #change default shell to zsh
  ```

> :page_with_curl: **oh-my-zsh**

- ```bash
  sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
  ```

## :heart: Credits

- [@owl4ce](https://github.com/owl4ce/)
