
<div align="center">
  <a href="https://blent.ai">
    <img src="https://blent-static-media.s3.eu-west-3.amazonaws.com/images/logo/logo_blent_300x.png" alt="Logo Blent.ai" width="200" />
  </a>

  <h2 align="center">Estimation de la rétention des clients d'une banque</h2>

  <p align="center">
    Projet Machine Learning - <a href="https://blent.ai">Blent.ai</a>
    <br />
    <a href="https://blent.ai/app/projects" target="_blank"><strong>Explorer tous les projets »</strong></a>
</div>

<div align="center"><img src="https://cdn.static-media.blent.ai/images/projects/badge_bank_churn.svg" width="120" alt="Badge du projet" /></div>

## À propos du projet

Dans un contexte concurrentiel, une banque cherche à  **fidéliser ses clients**  en leur proposant des services adaptés. Pour cela, elle s'intéresse à savoir quels sont les clients qui sont susceptibles de résilier tout ou une partie de leurs produits bancaires.

Pour cela, la banque dispose d'un historique sur plusieurs années de clients qui ont soient résilié leurs produits (ils ont  _churn_), soient restés clients de la banque. Un jeu de données a été extrait depuis la base de données principale contenant l'ensemble des clients (actuels et anciens) de la banque, accompagnés d'informations supplémentaires (nombre de produits bancaires, localisation, âge).

L'objectif est de déterminer  **si un client de la banque va résilier son contrat ou non**  à l'avenir en utilisant ses informations financières et personnelles connues de la banque. Cette problématique de score d'attrition (ou  _churn_  en anglais) est une problématique de  **classification binaire**  que l'entreprise cherche à résoudre en utilisant ses propres données.

> TODO : Compléter cette partie pour apporter plus d'informations sur le contexte du projet.

## Étapes du projet

- [ ] Explorer le jeu de données pour étudier les propriétés statistiques des variables
- [ ] Nettoyer le jeu de données et créer une base d'apprentissage pour un modèle
- [ ] Entraîner et optimiser un modèle de Machine Learning à partir de la base d'apprentissage
- [ ] Évaluer les performances du modèle et déterminer un score moyen par méthode de validation croisée
- [ ] Publier le code source et les résultats sur GitHub

La description des étapes est disponible sur la page associée au projet.

> TODO : Cocher les cases au fur et à mesure de l'avancement.

## Résultats

| Taille du train |      AUC      |
|:---------------:|:-------------------:|
|        1k       | 00.00% ± 00.00% |
|       10k       | 00.00% ± 00.00% |
|       100k      | 00.00% ± 00.00% |

> TODO : Il est possible d'ajouter des graphes pour apporter plus d'indications sur les résultats.

## Structure du projet

Le dépôt Git contient les éléments suivantes.

- `notebooks/` contient les Notebooks Jupyter du projet.
- `LICENSE.txt` : licence du projet.
- `requirements.txt` : liste des dépendances Python nécessaires.
- `README.md` : fichier d'accueil.

## Premiers pas

Les instructions suivantes permettent d'exécuter le projet sur son PC.

### Pré-requis

Le projet nécessite Python 3 d'installé sur le système.

> TODO : Ne pas hésiter à compléter/adapter cette partie en fonction des dépendances logicielles.

### Installation

1. Cloner le projet Git.
	```
	git clone https://github.com/blent-ai/Projet-Machine-Learning-Bank-Churn.git
	```
2. Installer les dépendances du fichier `requirements.txt` dans un environnement virtuel.

	**Linux / MacOS**
	```
	python3 -m venv venv/
	source venv/bin/activate
	pip install -r requirements.txt
	```
	**Windows**
	```
	python3 -m venv venv/
	C:\<chemin_dossir>\venv\Scripts\activate.bat
	pip install -r requirements.txt
	```

> TODO :
> - Remplir le fichier `requirements.txt` pour y ajouter les dépendances (Scikit-Learn, Pandas, etc).

### Démarrage

> TODO : Expliquer en quelques lignes et avec des exemples de ligne de commande comment l'utilisateur peut entraîner ou utiliser lui-même le modèle. 

## Licence

*Ce projet est proposé par <a href="https://blent.ai">Blent.ai</a>. Les données utilisées pour ce projet peuvent être soumises à des droits d'auteur et de propriété intellectuelle. Blent.ai ne peut être responsable des utilisations faites des données utilisées dans le cadre de ce projet.*

> TODO : Ajouter les licences supplémentaires au projet (autres données, outils propriétaires, etc).
