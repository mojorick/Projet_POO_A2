
<h1 align="center">🧬 Projet POO – Jeu de la Vie</h1>

<h2>🧠 Principe</h2>

<p>
Le <strong>Jeu de la Vie</strong> est un automate cellulaire imaginé par le mathématicien <strong>John Conway</strong>. Il modélise l’évolution d’une population de cellules sur une grille 2D selon un ensemble de règles simples, à chaque itération temporelle discrète.
</p>

<p>Chaque cellule peut être dans l’un des deux états suivants :</p>
<ul>
  <li>Vivante</li>
  <li>Morte</li>
</ul>

<p>Le voisinage d’une cellule (hors bordure) est constitué de <strong>8 cellules adjacentes</strong>. L’évolution des cellules suit les règles suivantes :</p>
<ul>
  <li>Une <strong>cellule morte</strong> avec <strong>exactement 3 voisines vivantes</strong> devient <strong>vivante</strong>.</li>
  <li>Une <strong>cellule vivante</strong> avec <strong>2 ou 3 voisines vivantes</strong> reste <strong>vivante</strong>.</li>
  <li>Dans tous les autres cas, la cellule <strong>meurt</strong> ou reste <strong>morte</strong>.</li>
</ul>

<h2>💡 Objectif du projet</h2>

<p>Ce projet a pour but de développer une <strong>implémentation en C++ orientée objet</strong> du Jeu de la Vie. Le programme lira en entrée un fichier décrivant la taille de la grille et son <strong>état initial</strong>.</p>

<h3>📄 Exemple de fichier d'entrée :</h3>

<pre><code>5 10
0 0 1 0 0 0 0 0 0 0
0 0 0 1 0 0 0 0 0 0
0 1 1 1 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0
</code></pre>

<h2>👨‍💻 Travail en binôme</h2>
<ul>
  <li>Le projet sera réalisé par groupes de <strong>2 étudiants</strong>.</li>
  <li><strong>L’utilisation de GIT est obligatoire</strong> pour tous les membres du groupe.</li>
  <li>Toute tentative de <strong>plagiat</strong> ou <strong>d’incapacité à expliquer son code</strong> sera sanctionnée.</li>
</ul>

<h2>✅ Critères d’évaluation</h2>
<ul>
  <li>Réponse au besoin</li>
  <li>Qualité et robustesse du code</li>
  <li>Utilisation des <strong>concepts de programmation orientée objet</strong></li>
  <li>Niveau d’aboutissement</li>
  <li>Maitrise du projet par le groupe</li>
</ul>

<h2>⚙️ Spécifications techniques</h2>
<ul>
  <li>Utilisation <strong>exclusive de la POO</strong> (aucun code procédural).</li>
  <li>Développement en <strong>C++ standard</strong>, avec la bibliothèque <strong>STL</strong>.</li>
  <li>Utilisation de <strong>SFML</strong> pour l'interface graphique.</li>
  <li>Implémentation de :
    <ul>
      <li><strong>Diagramme de cas d’utilisation</strong></li>
      <li><strong>Diagramme de classe</strong></li>
      <li><strong>Diagramme d’activité</strong></li>
      <li><strong>Diagramme de séquence</strong></li>
    </ul>
  </li>
  <li>Code <strong>efficace</strong>, <strong>structuré</strong> et <strong>modulaire</strong>.</li>
</ul>

<h2>🔧 Fonctionnalités</h2>

<h3>Mode Console</h3>
<ul>
  <li>Lecture du fichier d'entrée.</li>
  <li>Génération de la grille et des cellules.</li>
  <li>Exécution du jeu pour <em>n</em> itérations ou jusqu’à stabilisation.</li>
  <li>Sauvegarde de chaque état dans un fichier au format d’entrée.</li>
  <li>Résultats stockés dans un dossier nommé <code>&lt;nom_du_fichier&gt;_out</code>.</li>
</ul>

<h3>Mode Graphique (SFML)</h3>
<ul>
  <li>Affichage de la grille dans une fenêtre graphique.</li>
  <li>Simulation lancée automatiquement.</li>
  <li><strong>Contrôle du délai</strong> entre deux itérations.</li>
  <li>Implémentation orientée objet à partir d’un exemple de base.</li>
</ul>

<h2>🚀 Extensions possibles</h2>
<ul>
  <li><strong>Grille torique</strong> : les bords sont connectés (haut/bas, gauche/droite).</li>
  <li><strong>Cellules obstacles</strong> : vivantes ou mortes, elles n’évoluent jamais.</li>
  <li><strong>Motifs pré-programmés</strong> : ajout via le clavier pendant l’exécution.</li>
  <li><strong>Parallélisation</strong> de la mise à jour des cellules (optimisation multi-thread).</li>
</ul>
