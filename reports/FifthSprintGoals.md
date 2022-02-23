# Objectifs du 23/02/2022

PO: Hugo SABATIER

## Fonctionnalités attendues

###### A compléter avec la liste des attentes fonctionnelles du produit en fin de sprint.

* Publier la position du robot.
* Controler le robot par feedback linearisation.
* Plannifier un chemin pour le robot.
* Controler le robot par champs de potentiel.
* Commencer la rédaction du rapport.

## Tâches à réaliser

###### A compléter avec la liste macroscopique des tâches à réaliser afin d'implémenter les fonctionnalités détaillées précédemment.

* Intégration dans ROS de la détection de la position du robot par vision avec la caméra globale.
* Implémenter un contrôleur par feedback linearisation.
* Récupérer la position du robot pour la plannification.
* Corriger les bugs liés à la modélisation du robot.
* Implémenter un contrôleur par champs de potentiel.

## Challenges techniques

###### A compléter avec la liste argumentée des challenges et verrous techniques liées aux tâches à réaliser.

* Veiller à utiliser les mêmes référentiels.
* Récupérer une ancienne version sur Git du modèle du robot pour comprendre pourquoi il ne fonctionne plus et repartir de cette version.
* Choisir le type de message pour la publication de la position du robot.
