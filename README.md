# Package HE-MAN (OpenBor) pour BATOCERA
Vous trouverez ici le package du jeu HE-MAN pour l'émulateur OpenBor. Ce package est destiné au système d'émulation BATOCERA.

# Création du package
- Le package est déjà disponible à la racine du projet (HE_MAN-?.?.?-?-any.pkg.tar.xz), pour compiler votre propre package vous devez d'abord le supprimer.
- Copier l'intégralité du répertoire HE-MAN dans un répertoire de votre choix sur votre système BATOCERA (ex: Packaging).
- Connectez vous en SSH, puis placez vous dans le dossier HE-MAN.
- Lancez la commande `batocera-makepkg`
- Le package est généré dans le répertoire supérieur (ex: Packaging).

# Installation
- Copier l'archive HE-MAN-?.?.?-?-any.pkg.tar.xz dans un répertoire de votre choix sur votre système BATOCERA (ex: Packaging).
- Connectez vous en SSH, puis lancez la commande `pacman -U HE-MAN_2X-?.?.?-?.pkg.tar.xz` dans ce dossier.

# Suppression du package
- Connectez vous en SSH à votre système BATOCERA
- Lancer la commande `pacman -R HE-MAN`

# Liens
BATOCERA -> https://batocera.org/

Wiki BATOCERA Pacman Manager -> https://wiki.batocera.org/pacman_package_manager

OPENBOR -> http://www.chronocrash.com/forum/

HE-MAN -> https://gamejolt.com/games/he-man/19434