====================================================================
 PROJET PRATIQUE OBLIGATOIRE - PYTHON POUR LA DATA
 INSI - Institut National Supérieur d'Informatique
 GROUPE 1 L1D
====================================================================

CONTENU DU DOSSIER
-------------------
GROUPE_1_L1D_PYTHON_DATA/
|-- sujet_01_titanic.ipynb        -> Sujet 1 : Titanic
|-- sujet_02_supermarket.ipynb    -> Sujet 2 : Ventes supermarché
|-- sujet_03_videogames.ipynb     -> Sujet 3 : Jeux vidéo
|-- conclusions.pdf               -> Synthèse des conclusions des 3 sujets
|-- data/
|   |-- titanic.csv
|   |-- supermarket_sales.csv
|   `-- vgsales.csv
`-- README.txt                    -> Ce fichier

MEMBRES DU GROUPE
-----------------
+----+---------------------------------------------+-----------+---------------------------------------------+
| N° | Nom et Prénom                                | Matricule | Partie affectée                              |
+----+---------------------------------------------+-----------+---------------------------------------------+
| 1  | HARIMINO Faly Henintsoa                      |    401    | Partie 2 - Nettoyage & Préparation           |
|    |                                               |           | Partie 4 - Analyses avancées & Conclusions   |
+----+---------------------------------------------+-----------+---------------------------------------------+
| 2  | ANDRIAMIRADO Fanomezantsoa Fiononana         |    402    | Partie 1 - Exploration & Qualité des données |
|    |                                               |           | Partie 3 - Création de variables & Analyses  |
+----+---------------------------------------------+-----------+---------------------------------------------+
| 3  | (à compléter)                                |    ...    | (à définir)                                  |
+----+---------------------------------------------+-----------+---------------------------------------------+
| 4  | (à compléter)                                |    ...    | (à définir)                                  |
+----+---------------------------------------------+-----------+---------------------------------------------+

TECHNOLOGIES UTILISÉES
-----------------------
Python 3 - NumPy - Pandas (uniquement, aucun Machine Learning).

COMMENT EXÉCUTER LES NOTEBOOKS
-------------------------------
1. Ouvrir le dossier GROUPE_1_L1D_PYTHON_DATA dans Jupyter Notebook ou VS Code.
2. S'assurer que le dossier "data/" reste au même niveau que les .ipynb
   (les notebooks lisent les fichiers avec un chemin relatif "data/...csv").
3. Exécuter chaque notebook du début à la fin ("Restart & Run All").

====================================================================
 RÉPARTITION DU TRAVAIL - 4 PARTIES
====================================================================

Conformément à la consigne, les 3 sujets sont obligatoires et chaque
membre participe aux 3 sujets (interdiction de faire "un sujet = un
étudiant"). Le travail est organisé en 4 parties transversales
(chaque partie couvre la même étape sur les 3 sujets), classées par
ordre de difficulté croissante. Les 2 parties les plus difficiles
sont provisoirement affectées au Matricule 401, les 2 parties
restantes au Matricule 402. La répartition définitive entre les 4
membres du groupe sera communiquée ultérieurement.

--------------------------------------------------------------------
PARTIE 1 - Exploration & Qualité des données  [NIVEAU : facile]
--------------------------------------------------------------------
Affectée à : ANDRIAMIRADO Fanomezantsoa Fiononana - Matricule 402

- Sujet 1 (Titanic)      : Partie A - Chargement et exploration
- Sujet 2 (Supermarché)  : Partie A - Exploration
- Sujet 3 (Jeux vidéo)   : Partie A - Exploration
- Transverse : vérification de la cohérence des 3 notebooks
  (info(), describe(), colonnes, dimensions) avant remise.

--------------------------------------------------------------------
PARTIE 2 - Nettoyage & Préparation des données  [NIVEAU : difficile]
--------------------------------------------------------------------
Affectée à : HARIMINO Faly Henintsoa - Matricule 401

- Sujet 1 (Titanic)      : Partie B - Nettoyage (Age, Cabin, Embarked, Fare)
- Sujet 2 (Supermarché)  : Partie B - Préparation (Date, Jour/Mois/
  Jour_Semaine, calcul de CA, comparaison CA vs Total)
- Sujet 3 (Jeux vidéo)   : Partie B - Nettoyage (Year, Publisher) +
  Partie C - Vérification NumPy (Calculated_Global_Sales, Difference)
- Difficulté : nécessite de justifier chaque choix de traitement des
  valeurs manquantes (imputation par sous-groupe, conversion de type,
  vérification de cohérence entre colonnes) plutôt que d'appliquer
  une méthode automatique.

--------------------------------------------------------------------
PARTIE 3 - Création de variables & Analyses principales  [NIVEAU : facile/moyen]
--------------------------------------------------------------------
Affectée à : ANDRIAMIRADO Fanomezantsoa Fiononana - Matricule 402

- Sujet 1 (Titanic)      : Partie C - Création de variables
  (FamilySize, IsAlone, AgeGroup) + Partie D - Analyse (points 1 à 5)
- Sujet 2 (Supermarché)  : Partie C - Analyse des ventes + Partie D -
  Analyse par agence
- Sujet 3 (Jeux vidéo)   : Partie D - Analyse mondiale (top jeux,
  plateformes, éditeurs, genres)

--------------------------------------------------------------------
PARTIE 4 - Analyses avancées & Conclusions  [NIVEAU : difficile]
--------------------------------------------------------------------
Affectée à : HARIMINO Faly Henintsoa - Matricule 401

- Sujet 1 (Titanic)      : Partie D - Analyse (points 6 à 10) +
  Partie E - Conclusion
- Sujet 2 (Supermarché)  : Partie E - Analyse des produits + Partie F
  - Analyse des clients + Partie G - Conclusion
- Sujet 3 (Jeux vidéo)   : Partie E - Analyse géographique + Partie F
  - Analyse temporelle (comparaison par période) + Partie G -
  Conclusion
- Difficulté : croise plusieurs variables (groupby multi-niveaux,
  comparaisons géographiques et temporelles), et implique la
  rédaction des interprétations et conclusions de chaque sujet, ainsi
  que la synthèse finale dans conclusions.pdf.

--------------------------------------------------------------------
TÂCHES TRANSVERSES (tout le groupe, dernier jour)
--------------------------------------------------------------------
- Relecture croisée : chaque membre relit une partie qu'il n'a pas
  rédigée, afin d'être capable de l'expliquer en soutenance.
- Harmonisation du style de code et des commentaires entre les 3
  notebooks.
- Vérification finale : exécution complète ("Restart & Run All") des
  3 notebooks sans erreur avant la remise.
- Répartition des questions probables de soutenance entre tous les
  membres, sur les 3 datasets.
