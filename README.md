# KDE plasma setup

Install an AUR Helper (yay could be nice) and then: 

### First step

pacman -S --needed $(comm -12 <(pacman -Slq | sort) <(sort pkglist.txt))

### Second step

yay -S --needed - < pkglist.txt

### Third step (remove all other packages, TRICKY)

pacman -Rsu $(comm -23 <(pacman -Qq | sort) <(sort pkglist.txt))


## List of main applications setup 

Application name | URL |
| :--- | ---: |
brave |  |
coolero |  |
kitty |  |
tidal-hifi-git |  |
topgrade |  |

