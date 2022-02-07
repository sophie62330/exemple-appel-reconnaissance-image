Ceci est un exemple d'utilisation de l'outil de traitement d'image.

Pour faire un projet comme dans ce git, voici les étapes à suivre :
1) créer projet
2) ajouter CFUCounterReconnaissance.jar aux dépendances du proj
3) ajouter le jar de opencv aux dépendances du proj
4) ajouter la dll de opencv dans les librairies du proj
5) créer un objet trt de type TraitementImage
6) appeler la fonction lancerTraitement(url) sur l'objet créé juste avant
7) l'objet contient maintenant toutes les infos voulues accessibles avec les getters : trt.getNbCFU(), trt.getPhotoFinale()
