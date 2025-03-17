# detection-maladie-plantes

# Détecteur de Maladies des Haricots 

## Description
Ce projet est un système de détection des maladies des haricots basé sur l'apprentissage profond. Il permet aux agriculteurs et aux professionnels de l'agriculture d'identifier rapidement et précisément les maladies affectant leurs cultures de haricots à partir de simples photographies.

## Installation

### Prérequis
- Python 3.8 ou supérieur
- pip (gestionnaire de paquets Python)

### Étapes d'installation
bash
Cloner le repository
git clone https://github.com/votre-username/bean-disease-detector.git
Se déplacer dans le dossier du projet
cd bean-disease-detector
Créer un environnement virtuel
python -m venv venv
Activer l'environnement virtuel
Sur Windows
venv\Scripts\activate
Sur Linux/Mac
source venv/bin/activate
Installer les dépendances
pip install -r requirements.txt

## Structure du Projet
bean-disease-detector/
├── data/ # Données d'entraînement et de test
│ ├── train/ # Images d'entraînement
│ └── test/ # Images de test
├── model/ # Modèles entraînés et résultats
│ └── results/ # Résultats d'évaluation
│ └── confusion_matrix.png
├── src/ # Code source
│ ├── train.py # Script d'entraînement
│ ├── predict.py # Script de prédiction
│ └── utils/ # Utilitaires
├── requirements.txt # Dépendances du projet
└── README.md # Documentation

## Utilisation

### Entraînement du modèle
bash
python src/train.py --epochs 50 --batch-size 32

### Prédiction
bash
python src/predict.py --image path/to/image.jpg

## Maladies Détectées
- Rouille des feuilles
- Tache angulaire

## Performances
Le modèle atteint une précision de X% sur l'ensemble de test. La matrice de confusion est disponible dans `model/results/confusion_matrix.png`.

## Technologies Utilisées
- Python 3.8
- TensorFlow 2.x
- OpenCV
- NumPy
- Pandas
- Matplotlib

## Contribution
Les contributions sont les bienvenues ! Pour contribuer :
1. Forkez le projet
2. Créez une branche pour votre fonctionnalité
3. Committez vos changements
4. Poussez vers la branche
5. Ouvrez une Pull Request

## Licence
Ce projet est sous licence MIT. 

## Contact
Ibrahima LY - papalybn@gmail.com

## Remerciements
