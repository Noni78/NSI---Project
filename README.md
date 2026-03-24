# Jeu NSI – Die and Retry

## Description
Projet réalisé par des élèves de Première NSI.  
Objectif. créer un jeu vidéo en Python avec Pygame.

Le jeu suit le style die and retry.  
Chaque partie recommence de zéro.  
Le joueur progresse en apprenant les bons combos d’améliorations.

Pour accéder au jeu, télécharger le repo en zip puis extraire (ou cloner le repo sur vscode ou autre) puis executer game.py
## Pourquoi ce projet
Nous avons choisi ce projet car nous jouons aux jeux vidéo depuis longtemps.  
Créer un jeu correspond à nos intérêts.  
Pygame était déjà maîtrisé, donc adapté au projet.

## Technologies
- Python  
- Pygame  

## Répartition des rôles
Nolan  
- Mécaniques de jeu  
- Comportement des ennemis  
- Gestion des power ups  
- Logique du personnage  
- Interface graphique  
- Création et recherche des visuels  
Vlad, Sylvain, Dimitri 
- Play test


## Gameplay

### Système de vagues
- Les ennemis arrivent par vagues  
- Un boss apparaît toutes les 5 vagues  
- Chaque vague augmente la difficulté  

### Contrôles
- Déplacement. ZQSD ou flèches  
- Compétence. touche E, recharge avec le temps  
- Ultime. touche A, se recharge en éliminant des ennemis  

### Progression
- Les ennemis laissent des gemmes d’expérience  
- Les gemmes permettent de monter en niveau  
- Chaque niveau augmente les dégâts et la vie maximale  

### Power ups
Cœur du gameplay.

- Gagnés en montant de niveau ou en fin de vague  
- Choix entre 3 améliorations aléatoires  
- Rareté. commun ou épique  
- Importance des synergies entre améliorations  

Exemples  
- Elf électro  
- Boules de feu  

## Objectif
Survivre le plus longtemps possible.  
Optimiser ses choix d’améliorations.  
S’adapter à la difficulté croissante.
