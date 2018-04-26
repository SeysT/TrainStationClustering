Auteur : HACHEMIN Pierre-Yves et SEYS Thibaut

Date : 25/04/2018

# TrainStationClustering

## Installation

Pour installer le projet nous conseillons l'utilisation d'un environnement virtuel python :

```sh
virtualenv env --python=/usr/bin/python3.6
source ./env/bin/activate
pip install -r requirements.txt
```

Pour utiliser comme kernel l'environnement virtuel que nous venons de créer :

```sh
python -m ipykernel install --user --name=dac-project
```

## Structure du projet

Les fichiers du projet sont les suivants :

- `Data` : contient l'ensemble des datasets utilisés.
- `doc` : contient la documentation complémentaire de la plateforme Open Data du STIF.
- `Rapport.ipynb` : notebook jupyter décrivant notre approche pour ce projet. /!\ Certains traitements au sein du notebook sont assez longs à éxécuter.