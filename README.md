# RT

Dernier projet de la branche graphique pré-stage de l'école 42.

Ce projet est dans la continuité directe du projet précédent, RTv1. Il reprend la partie obligatoire et bonus du projet RTv1 
comme partie obligatoire et non noté. Seuls les ajouts bonus de ce projet seront évalués.

Voici les bonus présents en plus de la partie obligatoire dans le programme :
* Fichier de description de scène
* Lumière d'ambiance
* Perturbation de la normal (bruit de perlin)
* Perturbation de la couleur (damier)
* Lumière directe
* Réflexion, réfraction et transparence
* Effets visuels (antialliasing, filtre noir et blanc, filtre sépia)
* Effet technique (multithreading)

## Pour commencer

Ces instructions vous aideront à avoir une copie du projet et de pouvoir le faire marcher sur votre ordinateur.

### Prérequis

**Attention: A partir de maintenant, toutes les étapes (téléchargement, installation/compilation, exécution) seront à effectuer sur un terminal.**

#### Système d'exploitation

```
macOS Sierra
```

#### Téléchargement

Ce que vous devez faire pour télécharger les fichiers sources afin de pouvoir les compiler par la suite

```
git clone https://github.com/dcooray42/RT.git [nom du PATH/dossier]
```

### Installation

Se placer dans le dossier dans lequel vous avez fait la copie des fichiers sources du projet puis rentrer la commande suivante

```
make
```

Plusieurs fichiers .o auront fait leur apparitions dans le dossier que vous avez cloné ainsi que le binaire

```
rt
```
### Suppression

Pour supprimer les fichiers objets .o généré lors de la création du programme

```
make clean
```

Pour supprimer les fichiers objets .o et le programme

```
make fclean
```

Pour tout supprimer puis recompiler le programme

```
make re
```

## Faire des tests

Une fois que le programme a été créé, vous n'avez plus qu'à rentrer en ligne de commande le nom du programme + le fichier 
de description de scène.

### Utilisation du programme

Ligne de commande

```
./rt [PATH/fichier de description de scène]
```

### Commandes

Ces commandes ont été attribuées dans un environnement où les claviers étaient en QWERTY. Pour une meilleure expérience, 
veuillez changer par avance la configuration de votre clavier.

| Touche |          Action          |
| ------ |:------------------------ |
| W      | Avancer                  |
| S      | Reculer                  |
| A      | Strafe à gauche          |
| D      | Strafe à droite          |
| C      | Bloquer/débloquer caméra |
| Souris | Changer direction caméra |
| ESC    | Quitter                  |

#### Exemple
![alt text](https://raw.githubusercontent.com/dcooray42/RT/master/photo/rt_1.jpeg)
![alt text](https://raw.githubusercontent.com/dcooray42/RT/master/photo/rt_2.jpeg)

## Compiler avec
* SDL 2.0 - Librairie graphique
* OpenCL - Framework pour programmer des systèmes parallèles hétérogènes 

## Licence
* SDL 2.0 - zlib license

## Note
58/100

## Auteur

* **Dimitri Cooray** - [Lien vers github](https://github.com/dcooray42)
* **Enzo Pimenta**
* **Salam Dahmouch**
* **Fabien Rajaonarison**
