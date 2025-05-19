# 🎮 Tic-Tac-Toe Game

## 📝 Présentation

Ce projet est une implémentation du célèbre jeu Tic-Tac-Toe (aussi connu sous le nom de Morpion) développée en C# avec Windows Forms. Il s'agit d'un jeu de réflexion se jouant à deux, où chaque joueur place à tour de rôle son symbole (X ou O) sur une grille 3x3. Le gagnant est celui qui parvient à aligner trois de ses symboles horizontalement, verticalement ou en diagonale.

## ✨ Fonctionnalités

- **Interface graphique intuitive** : Grille de jeu 3x3 avec des boutons interactifs
- **Indication visuelle du tour** : Affichage du joueur actuel (Joueur 1 ou Joueur 2)
- **Marquage des alignements gagnants** : Coloration des lignes gagnantes en vert
- **Détection automatique des victoires** : Vérification horizontale, verticale et diagonale
- **Détection des matchs nuls** : Lorsque toutes les cases sont remplies sans gagnant
- **Option de redémarrage** : Bouton pour recommencer une nouvelle partie
- **Notification de fin de partie** : Affichage du gagnant ou d'un match nul

## 🖥️ Interface utilisateur

L'interface du jeu est composée des éléments suivants :

- **Grille de jeu** : 9 boutons représentant les cases du jeu
- **Indicateur de tour** : Affiche quel joueur doit jouer
- **Indicateur de résultat** : Affiche le gagnant ou indique un match nul
- **Bouton de redémarrage** : Permet de réinitialiser le jeu à tout moment

## 🎲 Comment jouer

1. Le Joueur 1 (X) commence la partie en cliquant sur une case vide
2. Le Joueur 2 (O) joue ensuite, et ainsi de suite
3. Pour gagner, un joueur doit aligner trois de ses symboles (horizontalement, verticalement ou en diagonale)
4. Si toutes les cases sont remplies sans alignement, la partie est déclarée nulle
5. Utilisez le bouton "Restart" pour commencer une nouvelle partie

## 🚀 Installation et prérequis

### Prérequis

- Microsoft Windows 7 ou plus récent
- .NET Framework 4.5 ou plus récent
- Microsoft Visual Studio (pour le développement)

### Installation

1. Clonez ou téléchargez ce dépôt sur votre machine locale
2. Ouvrez le fichier solution `XO-Game-Final.sln` avec Visual Studio
3. Compilez et exécutez le projet

## 🧩 Structure du code

Le projet est organisé selon le modèle standard d'une application Windows Forms :

- **Form1.cs** : Contient la logique du jeu et les gestionnaires d'événements
- **Form1.Designer.cs** : Définit l'interface utilisateur et les contrôles
- **Program.cs** : Point d'entrée de l'application
- **Images/** : Contient les ressources graphiques (X, O, et point d'interrogation)

### Classes et structures principales

- **enPlayer** : Énumération pour identifier les joueurs (Player1, Player2)
- **enWinner** : Énumération pour identifier le résultat (Player1, Player2, Draw, GameInProgress)
- **stGameStatus** : Structure contenant l'état actuel du jeu (gagnant, état de la partie, nombre de coups joués)

## 🛠️ Techniques utilisées

- **Programmation orientée objet** : Utilisation de classes, structures et énumérations
- **Gestion d'événements** : Interception des clics sur les boutons
- **Manipulations graphiques** : Dessin des lignes de la grille et coloration des alignements
- **Logique de jeu** : Algorithmes de vérification des conditions de victoire

## 🔄 Possibilités d'amélioration

- Ajout d'un mode joueur contre ordinateur (IA)
- Sauvegarde des scores entre les parties
- Personnalisation des noms des joueurs
- Adaptation à différentes tailles d'écran (responsive design)
- Animation des symboles lors du placement
- Sons et effets visuels pour améliorer l'expérience utilisateur

## 👤 Auteur

- **Oussama Souissi** - [GitHub](https://github.com/Oussama-souissi024)

## 📜 Licence

Ce projet est distribué sous licence open source.
