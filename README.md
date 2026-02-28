# Post_install_deb13
## Objectif du script

Ce script permet d'installer un ensemble de base de paquets / commandes automatiquement, utile lors d'une installation neuve d'une VM Linux.

## Liste des paquets installés
- ssh
- zip
- unzip
- nmap
- locate
- ncdu
- curl
- git
- screen
- dnsutils
- net-tools
- sudo
- lynx
- updatedb
- winbind
- samba

## Comment installer le script ?
_Il faut lancer le script avec les droits root._

Lancer les commandes suivantes :

Si la VM est toute neuve, lancer la commande :
- apt install ssh

puis celles-ci :
- wget postinstalldeb13.sh https://raw.githubusercontent.com/GaryBatista/postinstalldeb13/refs/heads/main/postinstalldeb13
- chmod +x postinstalldeb13
- ./postinstalldeb13
