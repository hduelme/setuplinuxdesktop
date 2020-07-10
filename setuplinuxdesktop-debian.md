# setuplinuxdesktop (debian)

# drivers

#### bluetooth-headset
```bash
apt install pulseaudio pulseaudio-module-bluetooth pavucontrol bluez-firmware
service bluetooth restart
apt install blueman
```

---

# programs

## browser
- #### firefox
  ```bash
  sudo apt install firefox
  ```
- #### chromium
  ```bash
  sudo apt install chromium
  ```
- #### google chrome
  ```bash
  wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb -o /tmp/google-chrome-stable_current_amd64.deb
  cd /tmp && sudo apt install ./google-chrome-stable_current_amd64.deb
  ```
  
---

## office
- #### wpsoffice
  ```bash
  flatpak install flathub com.wps.Office
  ```
- #### libreoffice
  ```bash
  sudo apt install libreoffice-core
  ```
- #### thunderbird
  ```bash
  sudo apt install thunderbird
  ```
- #### linphone
  ```bash
  sudo apt install linphone
  ```
- #### onlyoffice
  ```bash
  flatpak install flathub org.onlyoffice.desktopeditors
  ```

---

## password
- #### bitwarden
  ```bash
  sudo snap install bitwarden
  ```
  
---
  
## torrent clients
- #### qbittorrent
  ```bash
  sudo apt install qbittorrent
  ```
- #### transmission
  ```bash
  sudo apt install chromium
  ```

---

## media
  - #### spotify
  ```bash
  sudo apt install spotify-clien
  ```
  - #### discord
  ```bash
  flatpak install flathub com.discordapp.Discord
  ```
  - #### vlc
  ```bash
  sudo apt install vlc
  ```

---

## media-production
- #### obs
  ```bash
  flatpak install flathub com.obsproject.Studio
  ```
- #### audacity
  ```bash
  sudo apt install audacity
  ```
- #### kdenlive
  ```bash
  sudo apt install kdenlive kdenlive-data
  ```
- #### gimp
  ```bash
  sudo apt install gimp
  ```

---

## desktop-mods
- #### variety
  ```bash
  sudo apt install variety
  ```

---

## gaming
- #### steam
  ```bash
  sudo apt install steam
  ```
- #### minetest
  ```bash
  sudo apt install minetest
  ```
- #### lutris
  ```bash
  echo "deb http://download.opensuse.org/repositories/home:/strycore/Debian_10/ ./" | sudo tee /etc/apt/sources.list.d/lutris.list
  wget -q https://download.opensuse.org/repositories/home:/strycore/Debian_10/Release.key -O- | sudo apt-key add -
  rm Release.key
  sudo apt-get update
  sudo apt-get install lutris
  ```
- #### minecraft java edition
  ```bash
  sudo snap install minecraft-launcher-ot
  ```
---

## development
- ## atom
  ```bash
  sudo snap install atom --classic
  ```
- ## vscode
  ```bash
  sudo snap install code --classic
  ```
- ## eclipse
  ```bash
  sudo snap install eclipse --classic
  ```
- ## intelij
  ```bash
  sudo snap install intellij-idea-community --classic
  ```
- ## pycharm
  ```bash
  sudo snap install pycharm-community --classic
  ```
- ## clion
  ```bash
  sudo snap install clion --classic
  ```
- ## goland
  ```bash
  sudo snap install goland --classic
  ```

---

# programming-languages

- ## git
  ```bash
  sudo apt install git
  ```
- ## docker
  ```bash
  sudo apt install docker docker-compose
  ```
- ## php
  ```bash
  sudo apt install php php-common php-cli
  ```
  - #### composer
  ```bash
  sudo apt install composer
  ```
- ## nodejs
  ```bash
  sudo apt install nodejs npm
  ```
  - #### sass
  ```bash
  sudo npm i sass
  ```
- ## python
  ```bash
  sudo apt install python python3
  ```
  - #### pip
  ```bash
  sudo apt install python-pip python3-pip
  ```
- ## java
  ```bash
  sudo apt install default-jdk
  ```
- ## c
  ```bash
  sudo apt install gcc g++
  ```
- ## go-lang
  ```bash
  sudo apt-get install golang
  ```
- ## cobol
  ```bash
  sudo apt install open-cobol
  ```
