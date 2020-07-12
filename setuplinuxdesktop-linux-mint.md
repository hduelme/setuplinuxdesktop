# setuplinuxdesktop (Linux Mint)
if you miss something check out the [debian-wiki](setuplinuxdesktop-debian.md)

# programs

## password
- #### bitwarden
  ```bash
  flatpak install flathub com.bitwarden.desktop
  ```
  
---

## gaming
- #### minecraft java edition
  ```bash
  sudo apt install minecraft-launcher
  ```
---

## development
- #### atom
  ```bash
  flatpak install flathub io.atom.Atom
  ```
- #### vscode
  ```bash
  flatpak install flathub com.visualstudio.code-oss
  ```
- #### eclipse
  ```bash
  sudo apt install -y wget
  wget http://mirror.umd.edu/eclipse/technology/epp/downloads/release/2020-06/R/eclipse-java-2020-06-R-linux-gtk-x86_64.tar.gz
  sudo tar -zxvf eclipse-java-2020-06-R-linux-gtk-x86_64.tar.gz -C /usr/
  sudo ln -s /usr/eclipse/eclipse /usr/bin/eclipse
  ```
- #### pycharm
  ```bash
  flatpak install flathub com.jetbrains.PyCharm-Community
  ```
