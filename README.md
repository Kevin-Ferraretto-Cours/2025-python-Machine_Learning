# Projet d'Estimation Immobilière

Ce projet a été réalisé dans le cadre d'un examen sous Jupiter en Python. Il permet d'estimer le prix d'un bien immobilier en fonction de sa superficie et du nombre de pièces.

## Auteurs

Ce projet a été réalisé en binôme par :
- [Kevin Ferraretto](https://kevin-ferraretto.fr/)
- [@TheLordGibril](https://github.com/TheLordGibril)

## Structure du projet

```
projet-immobilier/
├── data/               # Dossier contenant les données utilisées
├── src/                # Dossier contenant les scripts Python
├── requirements.txt    # Liste des dépendances Python
└── README.md           # Ce fichier
```

## Installation

1. Clonez ce dépôt :
```bash
git clone https://github.com/Kevin-Ferraretto-Cours/2025-python-Machine_Learning.git
cd 2025-python-Machine_Learning
```

2. Créez un environnement virtuel Python :
```bash
# Création de l'environnement virtuel
python -m venv venv

# Activation de l'environnement virtuel
# Sous Windows
venv\Scripts\activate
# Sous Linux/macOS
source venv/bin/activate
```

3. Installez les dépendances :
```bash
pip install -r requirements.txt
```

## Utilisation

1. Assurez-vous que votre environnement virtuel est activé
2. Lancez Jupyter Notebook :
```bash
jupyter notebook
```

3. Ouvrez le notebook principal dans le dossier `src/` pour exécuter l'analyse

## Fonctionnalités

- Chargement et prétraitement des données immobilières
- Analyse exploratoire des données (EDA)
- Modélisation pour l'estimation des prix en fonction de la superficie et du nombre de pièces
- Visualisation des résultats et évaluation du modèle

## Données

Les données utilisées sont stockées dans le dossier `data/`. Elles contiennent des informations sur les biens immobiliers, notamment :
- Superficie en m²
- Nombre de pièces
- Prix de vente
- Et d'autres caractéristiques potentiellement présentes

## Dépendances principales

Les principales bibliothèques utilisées dans ce projet sont :
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

Pour la liste complète, consultez le fichier [requirements.txt](requirements.txt).

## Remarques

- Ce projet a été développé dans le cadre d'un examen, certaines parties peuvent nécessiter des améliorations pour une utilisation en production.
- L'environnement virtuel n'est pas inclus dans le dépôt et doit être créé localement.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENCE) pour plus de détails.
