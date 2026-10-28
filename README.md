# Collections pecheLearn

Les collections de cartes et les séries d'exercices proposées dans l'onglet
**Réglages → Catalogue** de l'application pecheLearn.

## Ajouter ou mettre à jour une collection

1. Déposer le fichier `.json` dans le dossier de la langue (par exemple
   `français-serbe/`). Le nom du fichier est celui affiché dans l'app : suivre
   la convention « Langue — Type — Nom », par exemple
   `Serbe — Vocabulaire — Cuisine.json`.
2. Pousser sur `main`.

C'est tout : l'app lit la liste des fichiers depuis GitHub. Il n'y a pas
d'index à tenir à jour, ni de numéro de version — un fichier modifié est
proposé en « Mise à jour » à ceux qui l'ont déjà téléchargé.

Formats acceptés : les mêmes que « Importer un JSON… » dans l'app (collection
de cartes, histoire, tableaux, ou série d'exercices).

## Bon à savoir

- Le dépôt est public : n'importe qui peut lire ces fichiers.
- Une mise à jour ajoute les nouvelles cartes et corrige les existantes sans
  toucher à la progression ; une carte retirée du fichier n'est pas supprimée
  chez ceux qui l'avaient déjà.
