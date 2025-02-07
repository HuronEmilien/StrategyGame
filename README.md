# Jeu de Stratégie au Tour par Tour - Projet Génie Logiciel

---

## Description du Projet
Ce projet consiste à développer un jeu de stratégie au tour par tour où plusieurs joueurs s'affrontent sur une grille en 2D. Chaque combattant dispose d'énergie, d'armes et de diverses capacités pour éliminer ses adversaires et survivre jusqu'à la fin.

### Fonctionnalités Principales
- **Gestion des Joueurs** : Possibilité de jouer entre 2 et n joueurs
- **Actions Disponibles** :
  - Déplacement en 4 directions
  - Dépôt de mines et de bombes
  - Tir horizontal et vertical
  - Déclenchement d'un bouclier défensif
  - Récupération de pastilles d’énergie
- **Éléments de la Grille** :
  - Murs infranchissables
  - Mines et bombes visibles ou invisibles
  - Pastilles d’énergie

### Critères de Victoire
Un joueur est éliminé lorsque son énergie atteint zéro. Le dernier survivant remporte la partie.

---

## Technologies Utilisées
- **Java** : Langage de développement principal
- **Swing/JavaFX** : Interface graphique
- **Javadoc** : Documentation du code
- **Git/SVN** : Gestion de version sur la forge universitaire
- **Ant** : Automatisation du build et génération du fichier `.jar`

---

## Installation et Exécution
### Prérequis
- Java installé (JDK >= 11)
- Apache Ant installé


## Conception et Architecture
- **MVC** : Séparation entre modèle, vue et contrôleur
- **Proxy Pattern** : Pour restreindre les informations visibles par chaque joueur
- **Factory Pattern** : Pour générer différents types de combattants
- **Strategy Pattern** : Pour gérer les stratégies des joueurs IA

---

## Remarques
- **Respect strict de l’architecture logicielle demandée**
- **Tests unitaires pour garantir la robustesse du jeu**
- **Évaluation basée sur la lisibilité, modularité et évolutivité du code**
