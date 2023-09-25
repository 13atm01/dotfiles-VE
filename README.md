<p align="center">
<a href="https://ibb.co/8MGT7jS" title="dotfiles"><img src="https://i.ibb.co/Wn7q2cY/Dotfiles.png" width="75%"></a>
</p>

## :art: Screenshot <img alt="Visits" src="https://badges.strrl.dev/visits/13atm01/dotfiles-VE?style=plastic&label=&color=8727D8&success&logo=GitHub&logoColor=white&labelColor=373e4d" align="right"/> 

:link: ***Theme 1*** <a href="https://www.deviantart.com/13andi01/art/My-Desktop-Violet-Evergarden-1-861259352"><img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/1e66b7e7-6690-440a-a71b-826e8081974a/de8rryw-937c1f85-2210-46f8-bd70-94389d2d8ada.png/v1/fill/w_1192,h_670,q_70,strp/my_desktop_violet_evergarden__1__by_13andi01_de8rryw-pre.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9NzY4IiwicGF0aCI6IlwvZlwvMWU2NmI3ZTctNjY5MC00NDBhLWE3MWItODI2ZTgwODE5NzRhXC9kZThycnl3LTkzN2MxZjg1LTIyMTAtNDZmOC1iZDcwLTk0Mzg5ZDJkOGFkYS5wbmciLCJ3aWR0aCI6Ijw9MTM2NiJ9XV0sImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl19.4eIbk7NHGxe5WaFN2dDBTOrId5n6UeLTOzekobJ2HGA"></a>

:link: ***Theme 2*** <a href="https://www.deviantart.com/13andi01/art/My-Desktop-Violet-Evergarden-2-861260942"><img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/1e66b7e7-6690-440a-a71b-826e8081974a/de8rt72-e7a430f1-4792-4683-a9b4-2109f62cb44c.png/v1/fill/w_1192,h_670,q_70,strp/my_desktop_violet_evergarden__2__by_13andi01_de8rt72-pre.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9NzY4IiwicGF0aCI6IlwvZlwvMWU2NmI3ZTctNjY5MC00NDBhLWE3MWItODI2ZTgwODE5NzRhXC9kZThydDcyLWU3YTQzMGYxLTQ3OTItNDY4My1hOWI0LTIxMDlmNjJjYjQ0Yy5wbmciLCJ3aWR0aCI6Ijw9MTM2NiJ9XV0sImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl19.45nNwXoV9iqjymYEPsq168eEkz3kCACKbXTbx1_mYss"></a>
  
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

> :rocket: **App launcher rofi**

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
