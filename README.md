🎌 Mon Projet Final : Score Éditorial Anime (GoGoKodo)

📌 C'est quoi ce projet ?
Le but, c'est d'aider une plateforme de streaming d'animés à choisir quels titres mettre en avant rapidement. En général, il faut attendre des mois pour avoir les stats des utilisateurs, mais là, on veut un signal de qualité immédiat avec des données limitées.

L'idée centrale, c'est de prouver qu'une simple note globale ne suffit pas (Hypothèse H1) et que la régularité des épisodes est la clé pour ne pas décevoir les fans (Hypothèse H2).

📊 Ma Méthode
J'ai suivi les 5 étapes de la méthodologie demandée :

Data cleaning & EDA : J'ai nettoyé les données et regardé les distributions pour comprendre les biais.
Calcul du score métier : J'ai créé un score spécial (70% note globale / 30% régularité) pour mieux refléter la qualité réelle.
Validation : J'ai comparé les notes brutes avec mon nouveau score pour voir si ça apportait vraiment quelque chose de nouveau.
Segmentation : J'ai classé les animés en 4 catégories ("Chef-d'œuvre", "Culte mais risqué", etc.) pour aider à prendre une décision.
Recommandation : Un petit système pour suggérer des animés "sûrs" selon le genre.

🛠️ Outils utilisés
Langage : Python 3.13.1
Éditeur : VS Code (avec l'extension Jupyter)
Bibliothèques : Pandas (pour les tableaux), Matplotlib et Seaborn (pour les graphiques)

🚀 Comment lancer le projet sur Mac
Installer les outils : Ouvre ton terminal dans VS Code et tape cette commande :

Bash : "pip3 install pandas matplotlib seaborn"
Lancer l'analyse : Ouvre le fichier analyse.ipynb, choisis le noyau Python en haut à droite et clique sur "Tout exécuter".

📂 Ce qu'il y a dans mon dossier (Livrables)
Conformément aux consignes :

analyse.ipynb : Tout mon code avec les commentaires.
animes_final_calcule.csv : Le dataset propre avec mes nouveaux scores.
README.md : Ce fichier.
distribution_notes.png & correlation_score.png : Mes graphiques exportés.