# Categoriser_automatiquement_des_questions_Stackoverflow
Dans ce projet nous allons créer des modèles de machine Learning pour le NLP, afin de catégarizer automatiquement des questions posés sur le forum de StackOverFlow

Il s'agit de développer une API de suggestion de tags à destination des utilisateur de [Stack Overflow](https://stackoverflow.com/). Le besoin étant de faciliter les débutants à leur suggérer des tags pertinents pour leur questions ou intérrogations.

Il était demandé de réaliser:

- Le fitrage des données issue de l'API [stackexchange explorer](https://data.stackexchange.com/stackoverflow/query/new)
- Réaliser le pétraitement des documents 
- Comparer des approches suppervisées (Regression logistique, Random Forest) et non supervisées (LDA, NMF) afin de prédire des tags
- Réaliser les fonctions et classes nécessaire à l'implémentation de l'API. 
- Développer une API et la mettre en production

# Contenu du repositiry:
- Models : Ce dossier contient l'ensembles modèles généré à partir des notebooks
- Variables : contient l'ensemble des variables et le dictionnaires des mots généré à partir des notebooks
- Scores : contient l'ensemble des scores obtenu par les modèles entrainés à partir des notebooks
- Un notebook de nottoyage et d'exploration des données.
- Un notebook de vectorisation des données.
- Un notebook de test des models non supervisés
- Un notebook de test des models supervisés
- Une présentation powerpoint des l'ensemble des données


# Données:
[Stackexchange explorer](https://data.stackexchange.com/stackoverflow/query/new)
