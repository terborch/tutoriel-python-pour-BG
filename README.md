# Premiers pas
Tutoriel didactique basée sur un cas réel.

## 1. Contexte et motivations
À la suite d'une thermographie (photographies Infra Rouge), j'avais ~300 prises de vue au format .IS2. Pour traiter ces thermographies elles sont toutes ouvertes dans un programme spécialisé. Une à une je traite les images qui m'intéresse, puis je les transforme toutes ces images au format .jpg.
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")


Dans le dossier des 100 fichiers .jpg restant, je fais un tri, pour garder que 50 fichiers .jpg qui seront intégré au rapport.
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Maintenant j'ai besoin de regrouper les 50 fichiers .jpg sélectionné ainsi que les 50 fichier .IS2 correspondant, pour générer les images dans le spectre visible et potentiellement retoucher les thermographies dans le rapport. Comment faire ? J'automatise le procédé!

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
