# Premiers pas
Tutoriel didactique basée sur un cas réel.

## 1. Contexte et motivations
À la suite d'une thermographie (photographies Infra Rouge), j'avais ~300 prises de vue au format .IS2. Pour traiter ces thermographies, elles sont toutes ouvertes dans un programme spécialisé. Je traite toutes les images simultanément pour obtenir des images au format .jpg.


![fichier](https://github.com/terborch/tutoriel-python-pour-BG/blob/main/tutoriel_1/Illustratuion_fichiers.png)


Dans le dossier des 300 fichiers .jpg, je fais un tri pour ne garder que les 50 thermographies qui seront intégrées au rapport. 
J'efface simplement une à une les images au format .jpg qui ne m'intéressent pas.


![images thermographiques](https://github.com/terborch/tutoriel-python-pour-BG/blob/main/tutoriel_1/Illustratuion_photo_IR.png)


Maintenant, j'ai besoin de regrouper les 50 fichiers .jpg sélectionnés, ainsi que les 50 fichiers .IS2 correspondants, pour les traiter 
un à un et potentiellement retoucher les thermographies du rapport. Comment faire ? J'automatise le procédé !

## 2. Installer Python via Anaconda
[Lien de téléchargement Anaconda x64 pour Windows](https://repo.anaconda.com/archive/Anaconda3-2021.05-Windows-x86_64.exe)

Exécuter le fichier téléchargé. Si une autre version de Python est installée, il est préférable de la désinstaller au préalable.

### 2.1 Obtenir les fichiers de ce repository GitHub
[Lien de téléchargement du repository GitHub](https://github.com/terborch/tutoriel-python-pour-BG/archive/refs/heads/main.zip)

Extraire les fichiers téléchargés, puis les placer dans un dossier local (Python n'a pas accès au serveur)

### 2.2 Démarrage de Anaconda
1. Lancer anaconda prompt
Démarrer > Recherche > Anaconda prompt
2. Naviguer vers un dossier : 
`cd "\chemin\dossier\"`
2. Naviguer vers le dossier supérieur: 
`cd..`
3. Lancer Jupyter Notebook : 
`jupyter notebook`



# Aller plus loin
1. Installer Anaconda
https://www.youtube.com/watch?v=YJC6ldI3hWk

2. Utiliser Jupyter Notebook
https://www.youtube.com/watch?v=HW29067qVWk
https://www.dataquest.io/blog/jupyter-notebook-tutorial/

3. Cours en ligne (livre basé sur des cas pratique)
https://automatetheboringstuff.com/

4. Cours en ligne (interactif)
https://www.freecodecamp.org/learn/

5. Cours sur app mobile interactive - Sololearn
* web https://www.sololearn.com/learning/1073
* android https://play.google.com/store/apps/details?id=com.sololearn.python&hl=en_IN&gl=US
* iphone https://apps.apple.com/us/app/sololearn-learn-to-code/id1210079064

6. Cheat sheets
* https://gto76.github.io/python-cheatsheet
* https://www.pythoncheatsheet.org/
* https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf
* https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf

## Infos additionnelles
Éviter d'installer des packages Python dans l'environnement par défaut (base). Ne jamais mélanger les outils d'installation de packages Python comme `pip install` ou `conda install`.

De nombreux packages viennent par défaut avec Anaconda; ils sont surtout orientés datascience, mais aussi machine learning. Ceux que j'utilise le plus souvent sont :
`pandas` – traitement de données, tableaux, lire/créer des Excel/csv
`numpy` – fonctions mathématiques, traitement vectoriel et matriciel des données (similaire à Matlab)
`matplotlib` – générer des graphiques

