# Déployez un modèle dans le cloud

Ce projet est une initiative de la start-up AgriTech "Fruits!", visant à développer une application mobile permettant aux utilisateurs de prendre en photo un fruit et d'obtenir des informations sur ce fruit. Ce projet est une première étape vers le développement de robots cueilleurs de fruits intelligents.

## Description du projet

Le but de ce projet est de développer une chaîne de traitement des images dans un environnement Big Data sur AWS. Nous utilisons PySpark pour la préparation des données et le traitement des images.

## Données

Nous utilisons le dataset Fruits 360, qui contient 90483 images de 131 types de fruits et légumes. Les images sont toutes de taille 100x100 pixels.

## Environnement de développement

Nous utilisons AWS EMR pour l'infrastructure Big Data et le stockage sur AWS S3. Le code est écrit en PySpark.

## Instructions d'installation

1. Configurez une instance EMR sur AWS.
2. Installez PySpark sur votre machine locale ou sur votre instance EMR.
3. Clonez ce repo sur votre machine locale ou sur votre instance EMR.
4. Téléchargez les données et stockez-les dans un bucket S3.

## Instructions d'exécution

1. Exécutez le script PySpark pour la préparation des données.
2. Exécutez le script PySpark pour le traitement des images.
3. Les résultats seront stockés dans le même bucket S3.

## Auteurs

[Boubacar Kone]
