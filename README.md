# Post_install_deb13
## Comment installer le script ?
_Il faut lancer le script avec les droits root._

Lancer les commandes suivantes :

Si la VM est toute neuve, lancer la commande :
- apt install ssh

puis celles-ci :
- wget postinstalldeb13.sh https://raw.githubusercontent.com/GaryBatista/post_install_deb13/refs/heads/main/postinstalldeb13
- chmod +x postinstalldeb13
- ./postinstalldeb13.sh
