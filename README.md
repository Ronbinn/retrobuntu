# retrobuntu
This is an asible role to configure a debian/ubuntu system for 15khz gaming. As root install git and ansible.
```
apt-get install ansible git
```
Clone my repo
```
git clone https://github.com/ronbinn/retrobuntu
```
Change dir and run the ansible playbook `retrobuntuati.yml` or `retrobuntuintel.yml` depending on your graphics card
```
cd retrobuntu
ansible-playbook retrobuntuati.yml
```
Poweroff, connect your pc to a 15khz tv, power on and you should see this
![](https://raw.githubusercontent.com/Ronbinn/retrobuntu/main/station01.png)

It's [emulationstation](https://emulationstation.org/) a front-end for emulators. There is only one emulator configured ([groovymame](https://github.com/antonioginer/GroovyMAME)) and a single game: [World Rally](https://en.wikipedia.org/wiki/World_Rally_(1993_video_game)) from Gaelco. It's a freeware rom.

If you want to add more emulators or roms press enter and quit emulationstation. There is a minimal xfce desktop with firefox, so you can download more roms or copy them from a pendrive.

If you prefer a step by step guide and do everything by yourself, [read the wiki](https://github.com/ronbinn/retrobuntu/wiki)
