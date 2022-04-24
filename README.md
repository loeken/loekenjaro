## loekenjaro

customized i3 manjaro community edition

build by github - look inside [github action](https://github.com/loeken/loekenjaro/blob/main/.github/workflows/iso_build.yml) for build instructions

[iso-profiles](https://github.com/loeken/iso-profiles) for the files

## sneak peak
![GitHub Logo](/screenshot.png)

## download isos

the iso's are split up due to size
you can download the *.iso* files from https://github.com/loeken/loekenjaro/releases
```
wget https://github.com/loeken/loekenjaro/releases/download/202202232126/manjaro-i3-22.02-loekenjaro-220223-linux516.iso.z01
wget https://github.com/loeken/loekenjaro/releases/download/202202232126/manjaro-i3-22.02-loekenjaro-220223-linux516.iso.zip

# combine
cat manjaro-i3-22.02-loekenjaro-220223-linux516.iso.z01 manjaro-i3-22.02-loekenjaro-220223-linux516.iso.zip > combined.zip
unzip combined.zip
```

this creates: manjaro-i3-*.iso


## added packages:
- terminator
- pulseaudio-bluetooth
- thunar
- xfce4-settings
- rofi
- nmap
- iotop
- bwm-ng
- htop
- kubectl
- polybar
- brave-browser
- code
- zsh-theme-powerlevel10k
- zsh-autosuggestions
- docker
- nodejs
