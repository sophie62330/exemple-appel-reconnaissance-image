Ceci est un exemple d'utilisation de l'outil de traitement d'image.

Pour faire un projet comme dans ce git, voici les étapes à suivre :
1) récupérer CFUCounterReconnaissance.jar dans https://github.com/sophie62330/module-reconnaissance-contours-image.git (dans le dossier : out/artifacts/CFUCounterReconnaissance_jar/)
2) créer projet (ou ouvrir un existant)
3) ajouter CFUCounterReconnaissance.jar aux dépendances du proj
4) ajouter le jar de opencv aux dépendances du proj
5) ajouter la dll de opencv dans les librairies du proj
6) créer un objet trt de type TraitementImage 
7) appeler la fonction lancerTraitement(url) sur l'objet créé juste avant
8) l'objet contient maintenant toutes les infos voulues accessibles avec les getters : trt.getNbCFU(), trt.getPhotoFinale()
