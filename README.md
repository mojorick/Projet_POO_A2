🧬 Projet POO – Jeu de la Vie
🧠 Principe
Le Jeu de la Vie est un automate cellulaire imaginé par le mathématicien John Conway. Il modélise l’évolution d’une population de cellules sur une grille 2D selon un ensemble de règles simples, à chaque itération temporelle discrète.

Chaque cellule peut être dans l’un des deux états suivants :

Vivante

Morte

Le voisinage d’une cellule (hors bordure) est constitué de 8 cellules adjacentes. L’évolution des cellules suit les règles suivantes :

Une cellule morte avec exactement 3 voisines vivantes devient vivante.

Une cellule vivante avec 2 ou 3 voisines vivantes reste vivante.

Dans tous les autres cas, la cellule meurt ou reste morte.

💡 Objectif du projet
Ce projet a pour but de développer une implémentation en C++ orientée objet du Jeu de la Vie. Le programme lira en entrée un fichier décrivant la taille de la grille et son état initial.

📄 Exemple de fichier d'entrée :
5 10
0 0 1 0 0 0 0 0 0 0
0 0 0 1 0 0 0 0 0 0
0 1 1 1 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0


👨‍💻 Travail en binôme
Le projet sera réalisé par groupes de 2 étudiants.

L’utilisation de GIT est obligatoire pour tous les membres du groupe.

Toute tentative de plagiat ou d’incapacité à expliquer son code sera sanctionnée.

✅ Critères d’évaluation
Réponse au besoin

Qualité et robustesse du code

Utilisation des concepts de programmation orientée objet

Niveau d’aboutissement

Maitrise du projet par le groupe

⚙️ Spécifications techniques
Utilisation exclusive de la POO (aucun code procédural).

Développement en C++ standard, avec la bibliothèque STL.

Utilisation de SFML pour l'interface graphique.

Implémentation de :

Diagramme de cas d’utilisation

Diagramme de classe

Diagramme d’activité

Diagramme de séquence

Code efficace, structuré et modulaire.

🔧 Fonctionnalités
Mode Console
Lecture du fichier d'entrée.

Génération de la grille et des cellules.

Exécution du jeu pour n itérations ou jusqu’à stabilisation.

Sauvegarde de chaque état dans un fichier au format d’entrée.

Résultats stockés dans un dossier nommé <nom_du_fichier>_out.

Mode Graphique (SFML)
Affichage de la grille dans une fenêtre graphique.

Simulation lancée automatiquement.

Contrôle du délai entre deux itérations.

Implémentation orientée objet à partir d’un exemple de base.

🚀 Extensions possibles
Grille torique : les bords sont connectés (haut/bas, gauche/droite).

Cellules obstacles : vivantes ou mortes, elles n’évoluent jamais.

Motifs pré-programmés : ajout via le clavier pendant l’exécution.

Parallélisation de la mise à jour des cellules (optimisation multi-thread).

