# Collections pecheLearn

Le contenu à télécharger depuis l'application pecheLearn :

- `cartes/` : les collections de cartes, proposées dans **Apprendre → Plus de cartes** ;
- `exercices/` : les séries d'exercices, proposées dans **Exercices → Plus d'exercices**.

## Ajouter ou mettre à jour un fichier

1. Déposer le fichier `.json` dans le dossier de son niveau, lui-même dans
   celui de la langue, sous `cartes/` ou `exercices/` :

   ```
   cartes/
     français-serbe/
       A1 - débutant/
         Serbe — Vocabulaire — Cuisine.json
       A2 - élémentaire/
   exercices/
     français-serbe/
       A1 - débutant/
         Serbe — Exercices — Les cas.json
   ```

   Le nom du dossier de niveau s'affiche tel quel dans l'app, et les niveaux
   sont triés par ordre alphabétique : commencer par A1, A2, B1… suffit à les
   garder dans l'ordre. Le nom du fichier est le titre affiché.
2. Pousser sur `main`.

C'est tout : l'app lit la liste des fichiers depuis GitHub. Il n'y a pas
d'index à tenir à jour, ni de numéro de version — un fichier modifié est
proposé en « Mise à jour » à ceux qui l'ont déjà téléchargé.

Formats acceptés : les mêmes que l'import JSON dans l'app — collection de
cartes, histoire ou tableaux sous `cartes/`, série d'exercices sous `exercices/`.

## Bon à savoir

- Le dépôt est public : n'importe qui peut lire ces fichiers.
- Une mise à jour ajoute les nouvelles cartes et corrige les existantes sans
  toucher à la progression ; une carte retirée du fichier n'est pas supprimée
  chez ceux qui l'avaient déjà.
