## loekenjaro

i3 manjaro community edition with some tools preinstalled

some packages are provided via https://repo.internetz.me

## sneak peak
![GitHub Logo](/screenshot.png)

## download isos

the iso's are split up due to size
you can download the *.iso* files from https://github.com/loeken/loekenjaro/releases
```
wget https://github.com/loeken/loekenjaro/releases/download/202109071653/manjaro-i3-21.09-development-210907-linux510.iso.zip
wget https://github.com/loeken/loekenjaro/releases/download/202109071653/manjaro-i3-21.09-development-210907-linux510.iso.z0

# combine
cat manjaro-i3-21.09-development-210907-linux510.iso.z01 manjaro-i3-21.09-development-210907-linux510.iso.zip > combined.zip
unzip combined.zip
```

this creates: manjaro-i3-21.09-development-210907-linux510.iso


## added packages:
- terminator
- pulseaudio-bluetooth
- thunar
- xfce4-settings
- rofi
- docker
- minikube
- nmap
- iotop
- bwm-ng
- htop
- kubectl
- docker
- docker-compose
- minikube
- polybar

## AUR packages
- visual-studio-code-bin
- zsh-theme-powerlevel10k-git
- google-chrome