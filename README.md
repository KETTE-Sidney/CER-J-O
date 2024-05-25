# CER-J-O
Projet finale informatique CY Tech 2024
## Description
Le Suivi des Performances des Athlètes est une application en C conçue pour gérer et suivre les performances des athlètes dans divers événements. Le programme permet aux utilisateurs d'ajouter des performances, de voir les performances par événement ou par date, et de calculer des statistiques telles que les meilleurs, pires et temps moyens pour des événements. Il inclut également des fonctionnalités pour comparer les performances à différentes dates et identifier les trois meilleurs athlètes pour un événement spécifique.

## Fonctionnalités
- Ajouter des enregistrements de performances pour les athlètes.
- Voir les performances par événement ou par date.
- Calculer des statistiques : meilleurs, pires et temps moyens pour un événement.
- Comparer les différences de performances entre deux dates.
- Lister tous les événements disponibles.
- Identifier les trois meilleurs athlètes pour un événement spécifique.

## Structure des Fichiers
Le programme est organisé en plusieurs fichiers :

- `athletes.c` : Contient les fonctions pour gérer les performances des athlètes.
- `athletes.h` : Fichier d'en-tête définissant les structures et les prototypes de fonctions pour `athletes.c`.
- `events.c` : Contient les fonctions pour initialiser, lister et valider les événements.
- `events.h` : Fichier d'en-tête définissant la structure et les prototypes de fonctions pour `events.c`.
- `file.c` : Contient les fonctions pour charger et sauvegarder les données des athlètes.
- `file.h` : Fichier d'en-tête définissant les prototypes de fonctions pour `file.c`.
- `stats.c` : Contient les fonctions pour calculer les statistiques de performance.
- `stats.h` : Fichier d'en-tête définissant les prototypes de fonctions pour `stats.c`.
- `main.c` : Contient la fonction principale et le menu d'interface utilisateur.

## Installation
Pour installer et exécuter le Suivi des Performances des Athlètes, suivez ces étapes :

1. Clonez le dépôt ou téléchargez les fichiers du code source.
2. Compilez le code source en utilisant un compilateur C, tel que `gcc`. Utilisez la commande suivante pour compiler le programme :
    ```bash
    gcc -o athlete_tracker main.c athletes.c events.c file.c stats.c
    ```
3. Exécutez l'exécutable compilé :
    ```bash
    ./athlete_tracker
    ```

## Utilisation
1. Lorsque vous exécutez le programme, il vous sera demandé de saisir le nombre d'athlètes.
2. Entrez le nom de chaque athlète.
3. Le menu principal s'affichera alors avec les options suivantes :
    - **1. Ajouter une Performance** : Ajouter un enregistrement de performance pour un athlète.
    - **2. Voir les Performances par Événement** : Voir toutes les performances d'un athlète pour un événement spécifique.
    - **3. Voir les Performances par Date** : Voir toutes les performances d'un athlète pour une date spécifique.
    - **4. Voir les Statistiques** : Calculer et afficher les meilleurs, pires et temps moyens pour un événement.
    - **5. Lister les Événements** : Lister tous les événements disponibles.
    - **6. Top 3 des Athlètes pour un Événement** : Identifier les trois meilleurs athlètes pour un événement spécifique basé sur la performance moyenne.
    - **7. Différence de Performance Entre Deux Dates** : Comparer la performance d'un athlète entre deux dates pour un événement spécifique.
    - **8. Quitter** : Quitter le programme.

4. Suivez les instructions à l'écran pour naviguer dans le menu et effectuer les actions souhaitées.

## Exemple
Voici un exemple d'utilisation du programme :
1. Exécutez le programme.
2. Entrez le nombre d'athlètes (par exemple, `2`).
3. Entrez les noms des athlètes (par exemple, `Usain` et `Bolt`).
4. Utilisez le menu pour ajouter des performances, voir les performances et calculer des statistiques
5. 
---

**Note :** Ce programme utilise des codes couleur ANSI pour améliorer la sortie dans le terminal. Si votre terminal ne supporte pas les codes couleur ANSI, la sortie peut ne pas s'afficher comme prévu.
