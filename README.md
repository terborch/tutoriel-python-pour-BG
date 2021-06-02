# Premiers pas
Tutoriel didactique basée sur un cas réel.

## 1. Contexte et motivations
À la suite d'une thermographie (photographies Infra Rouge), j'avais ~300 prises de vue au format .IS2. Pour traiter ces thermographies elles sont toutes ouvertes dans un programme spécialisé. Une à une je traite toutes les images simultanément pour obtenir des images au format .jpg.


![fichier](https://github.com/terborch/tutoriel-python-pour-BG/blob/main/tutoriel_1/Illustratuion_fichiers.png)


Dans le dossier des 300 fichiers .jpg, je fais un tri, pour garder que les 50 thermographies qui seront intégré au rapport. J'efface simplement un à un les images au format .jpg qui ne m'intéressent pas.  


![images thermographiques](https://github.com/terborch/tutoriel-python-pour-BG/blob/main/tutoriel_1/Illustratuion_photo_IR.png)


Maintenant j'ai besoin de regrouper les 50 fichiers .jpg sélectionné ainsi que les 50 fichier .IS2 correspondant, pour les traiter un à un et potentiellement retoucher les thermographies du rapport. Comment faire ? J'automatise le procédé!

## 2. Installer python via anaconda
[Lien de téléchargement Anaconda x64 pour Windows](https://repo.anaconda.com/archive/Anaconda3-2021.05-Windows-x86_64.exe)

Exécuter le fichier téléchargé. Si une autre version de python est installée, il est préférable de la désinstaller.

### 2.1 Obtenir les fichiers de ce repository GitHub
[Lien de téléchargement du repository GitHub](https://github.com/terborch/tutoriel-python-pour-BG/archive/refs/heads/main.zip)

Extraire les fichiers téléchargés puis les placer dans un dossier local (python n'a pas accès au serveur)

### 2.2 Démarrage de Anaconda
1. Lancer anaconda prompt
Démarrer > Recherche > Anaconda prompt
2. Naviguer vers un dossier: 
`cd "\chemin\dossier\"`
2. Naviguer vers le dossier supérieur: 
`cd..`
3. Lancer jupyter notebook: 
`jupyter notebook`


# Aller plus loins

## Site Web basé sur des cas pratiques
https://automatetheboringstuff.com/

## Application mobile
https://www.sololearn.com/home

## info additionel
Éviter d'installer de package python dans l'environnement par défaut (base). Ne jamais mélanger les outils d'installation de package python comme `pip install` ou `conda install`

De nombreux packages viennent par défaut avec Anaconda, surtout orienté datascience mais aussi machine learning. Ceux que j'utilise le plus souvent sont:
`pandas` – traitements de données, tableaux, lire/créer des Excel/csv
`numpy` – fonctions mathématique, traitement vectoriel, matricielle des données, similaire à matlab
`matplotlib` – générer des graphiques
