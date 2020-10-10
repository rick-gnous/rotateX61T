# Script de rotation d’écran pour Thinkpad X61T

## Installation

Mettez les fichiers dans `/home/<user>/.bin`. Ajoutez le dossier dans le `$PATH` si ce n’est pas déjà fait.

## Usage 

### rotateFunction 

Contient les fonctions pour tourner l’écran et le stylet. Chaque rotation a un numéro attribué qui est sauvegardé dans le fichier `/home/<user>/.bin/rotationmode`.

Numéro  | position de l’écran
0       | normal
1       | pivoté à droite
3       | pivoté à gauche
4       | à l’envers

### rotatebutton et autotorotate

À lier avec le bouton de rotation de l’écran et d’automatiser la rotation lors du passage en mode tablette.
