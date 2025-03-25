### Analyse des Données de Ventes d'un Supermarché et Pilotage de Dashboard
## Description du Projet
Ce projet consiste à analyser les données de ventes d'un supermarché pour fournir des insights clés, optimiser les performances commerciales et créer un tableau de bord interactif à l’aide de Power BI. L’objectif est de rendre l’analyse des données de ventes plus accessible, notamment en permettant de suivre des KPIs pertinents, identifier des tendances de vente, comprendre les préférences des clients et proposer des axes d'amélioration pour la prise de décision.

## Objectifs
Importer, nettoyer et transformer les données à l’aide de Power Query.

Créer des mesures calculées et des colonnes avec DAX.

Identifier les KPIs pertinents pour le suivi des performances.

Concevoir un tableau de bord interactif pour faciliter la visualisation des données et l'analyse.

Visualiser les tendances de vente, les préférences des clients et les axes d’amélioration à l’aide de graphiques interactifs.

Optimiser les visualisations pour améliorer l’interprétation des données et la prise de décision.

## Stack Technique
 Power BI : Outil principal pour la création du tableau de bord et des visualisations.

 Power Query : Utilisé pour le nettoyage et la transformation des données.

 DAX (Data Analysis Expressions) : Utilisé pour créer des mesures calculées et des colonnes dans Power BI.

 Microsoft Excel : Utilisé pour l’importation et l’analyse initiale des données.

## Étapes du Projet
# 1. Importation et Préparation des Données
Importation des données : Les données de ventes ont été importées depuis plusieurs fichiers (CSV, Excel).

Nettoyage des données : Suppression des doublons, gestion des valeurs manquantes, et conversion des formats de données (dates, montants).

Transformation des données : Utilisation de Power Query pour transformer les données en format exploitable.

# 2. Calculs et Mesures avec DAX
Création de mesures calculées pour obtenir des KPIs tels que Total des ventes, Marge bénéficiaire, et Panier moyen.

Ajout de colonnes calculées comme le panier moyen par client, la fréquence d'achat.

# 3. Création de Graphiques Interactifs
Histogrammes : Affichage de l’évolution des ventes sur différentes périodes.

Carte géographique : Visualisation des ventes par région ou par magasin.

Graphiques en anneau : Distribution des ventes par catégorie de produits.

Courbes : Tendances de ventes sur plusieurs années ou mois.

# 4. Construction du Tableau de Bord
Tableau de bord interactif permettant aux utilisateurs de filtrer les données en fonction de différents critères (dates, produits, magasins).

Utilisation de slicers pour affiner les visualisations.

# 5. Optimisation des Visualisations
Amélioration de l’ergonomie des visualisations avec des couleurs et des mises en forme conditionnelles pour attirer l'attention sur les informations clés.

 Création de visualisations claires pour une interprétation rapide et précise des données.

## Structure du Projet
bash
Copier
Modifier
├── Data/                    # Dossier contenant les fichiers de données
├── PowerBI/                 # Contient le fichier .pbix avec le tableau de bord Power BI
├── Scripts/                 # Dossier pour les scripts Power Query et DAX
├── README.md               # Documentation principale du projet
                
## Instructions d'Installation
# Prérequis
Power BI Desktop : Téléchargez et installez Power BI à partir de ce lien.

Fichiers de données : Téléchargez les fichiers de données depuis le dossier Data/ dans ce projet.

Étapes pour utiliser le projet
Ouvrez Power BI Desktop.

Cliquez sur "Ouvrir" et sélectionnez le fichier .pbix dans le dossier PowerBI/.

Explorez le tableau de bord interactif et utilisez les slicers pour analyser les données de ventes.

## Contribuer au Projet
Si tu souhaites contribuer à ce projet, voici les étapes :

Fork ce dépôt.

Crée une branche pour ta fonctionnalité (git checkout -b feature-xyz).

Commit tes changements (git commit -m "Ajout de la fonctionnalité XYZ").

Pousse ta branche (git push origin feature-xyz).

Crée une Pull Request.


## Quelques bonnes pratiques de gestion de projet :
Maintenir un code propre dans les fichiers DAX et Power Query.

Ajouter des commentaires pour décrire la logique des mesures et des colonnes calculées.

Mettre à jour régulièrement les données pour suivre les performances actuelles.
## 📩 Contact
Si tu as des questions, n'hésite pas à me contacter sur [LinkedIn](https://linkedin.com/in/jenny-tchiegue-90780325) ou à ouvrir une issue sur GitHub ! 🚀


