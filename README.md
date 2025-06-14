# TDB
Dans le cadre du master MéDAS: Création d'un tableau de bord automatisé sur le suivi des ODD en France. 

# DATA 
Dans ce fichier sont regroupés les différentes tables créées par le script intégration. 
Tables de correspondances des données à partir des metadata. 
Tables de données exploitables à partir de DATA. 

## Description de la donnée: 
Les données sont décrites en détails par les tables de correspondance extraites du fichier DS_DEVDUR_metata.csv. 

L’Assemblée générale de l’Organisation des Nations unies (ONU) a adopté 17 objectifs de développement durable (ODD), déclinés en 169 cibles pour la période 2015-2030. Ces objectifs et cibles constituent une feuille de route commune de la transition.

La France a engagé un travail d’appropriation de ces objectifs pour définir une feuille de route adaptée à ses priorités et spécificités nationales. Les 98 indicateurs retenus permettent de dimensionner un suivi sur les politiques publiques françaises concourant aux ODD.

Ce jeu de données constitue le suivi de ces 98 indicateurs.

Rapide introduction pour une compréhension générale: 
Chaque ligne correspond a une politique publique menée pour un indicateur d'un objectif de développement durable (ODD). Le jeu de données concerne la France et l'Outre-Mer. Chaque action est décrite par :
- Objectif de développement durable,
    - Indicateur d'objectif du développement durable (cibles),
    - Composite du développement durable (sujet de la cible),
    - Type d'indicateur du développement durable (si ODD ou indicateur de richesse nationale),
- statut global de l'indicateur,
- valeur d'observation,
- unité de mesure correspondante à l'action,
- statut d'activité des sujets,
- sex,
- âge
- profession et catégorie socioprofessionnelle,
- année,
- région concernée.
  
Chaque ODD ayant sa propre manière d'être mesuré, il est important de comprendre les spécificités de ce jeu de données pour bien interpréter les résultats présentés. 
Chaque ODD sera donc analysé individuellement sur les observations recueillies. 
Les comparaisons sur l'ensemble des ODD se feront sur le nombre d'actions concernées et la répartition par rapport à d'autres attributs (statut, cible, personnes). 

# OUTILS (liste incomplète)
Onyxia
Git
Jupyter - openpyxl
Excel

# OUTPUT
L'objectif est d'obtenir un tableau de bord Excel qui permette de: 

1- Page BILAN: 
Comparer les quantités d'action, ou l'effort cumulé, sur chaque ODD et par type d'indicateur. 
Identifier les sujets cibles principaux de développement durable. 
Identifier les indicateurs les plus représentés (indifféremment de l'ODD concerné). 
Identifier la répartition des actions par geolocalisation. 

2- Page ODD: 
Page filtrée sur un indicateur par filtre, et par année. 
Nom de l'indicateur, ODD associé, Unité de mesure. 
Répartition des sujets cibles de l'action.


# SCRIPTS
Intégration: Chargement et pré traitement des données.
Exploration: Script explicatif des données (usage projet). 
TDB: Construction du document final (Excel).

# PLAN D'ACTION
1-	Établir une table de correspondance à partir des métadonnées : 
a.	Comment créer des Catégories d’index à partir d’un sommaire potentiellement évolutif ? 
b.	Comment intégrer ces correspondances dans un modèle ? 

2-	Analyser les données et définir l'exploitation des données

3-	Analyse des indicateurs en fonction de filtres dynamiques

4-	Identifier un MODOP de MAJ adapté à différents cas d’évolutions de la donnée. 

