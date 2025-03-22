# Analyse en Composantes Principales (ACP)

Ce projet implémente une application JavaFX permettant de réaliser une Analyse en Composantes Principales (ACP). L'utilisateur peut saisir une matrice de données, calculer les matrices centrée, réduite et normée, et visualiser les résultats sous forme graphique.

## Fonctionnalités

1. **Saisie de la matrice** :
   - L'utilisateur saisit le nombre de lignes et de colonnes de la matrice.
   - Les valeurs de la matrice sont ensuite saisies ligne par ligne via la console.

2. **Calcul des matrices** :
   - Matrice centrée.
   - Matrice réduite.
   - Matrice normée.
   - Matrice transposée.
   - Matrice de corrélation.

3. **Visualisation graphique** :
   - Création d'un graphique de dispersion pour représenter les données centrées et normées.

## Prérequis

- **JDK** : Version 8 ou supérieure.
- **JavaFX** : Ajoutez les bibliothèques JavaFX à votre projet.

## Installation

1. Clonez ce dépôt ou copiez les fichiers sources dans un nouveau projet.
2. Assurez-vous que JavaFX est correctement configuré dans votre IDE.
3. Compilez et exécutez le fichier `ACP.java`.

## Exécution

1. Lancez l'application.
2. Entrez le nombre de lignes et de colonnes de votre matrice.
3. Saisissez les valeurs de la matrice dans la console.
4. Les matrices calculées seront affichées dans la console.
5. Un graphique s'ouvrira pour visualiser les données.

## Exemple de Sortie

### Entrée

- Nombre de lignes : 3
- Nombre de colonnes : 3
- Valeurs :
  - Ligne 1 : 1.0, 2.0, 3.0
  - Ligne 2 : 4.0, 5.0, 6.0
  - Ligne 3 : 7.0, 8.0, 9.0

### Sortie

1. **Matrice centrée** :
   ```
   -3.0  -3.0  -3.0
    0.0   0.0   0.0
    3.0   3.0   3.0
   ```

2. **Matrice réduite** :
   ```
   -1.0  -1.0  -1.0
    0.0   0.0   0.0
    1.0   1.0   1.0
   ```

3. **Matrice normée** :
   ```
   -0.577  -0.577  -0.577
    0.0     0.0     0.0
    0.577   0.577   0.577
   ```

4. **Graphique** : Un graphique de dispersion affichant les données.

## Structure du Projet

- **Main Class** : `ACP`
- **Méthodes principales** :
  - `saisirMatrice` : Saisie et affichage des matrices.
  - `afficherMatrice` : Affiche une matrice donnée.
  - `calculsMatrices` : Calcule les différentes matrices (centrée, réduite, normée, transposée, corrélation).
  - `start` : Point d'entrée de l'application JavaFX.

## Auteurs

- **HoussemBouagal**

## Licence

Ce projet est sous licence MIT. Vous êtes libre de le modifier et de le redistribuer tout en conservant cette note.

