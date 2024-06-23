# Système de Détection d'Ordinateur et de Souris avec OpenCV et YOLO

## Description
Ce projet est un système de détection d'ordinateurs et de souris dans des images ou des flux vidéo en utilisant OpenCV et le modèle de détection d'objets YOLO (You Only Look Once). Le code est organisé de manière orientée objet pour assurer une meilleure modularité et compréhension.

## Prérequis
- Python 3.6 ou supérieur
- OpenCV 4.5 ou supérieur
- YOLOv5
- PyTorch

## Installation
1. Clonez ce dépôt :
    ```bash
    git clone https://github.com/votreutilisateur/votreprojet.git
    cd votreprojet
    ```

2. Installez les dépendances :
    ```bash
    pip install -r requirements.txt
    ```

## Utilisation
1. Assurez-vous d'avoir une webcam connectée.
2. Exécutez le script principal :
    ```bash
    python yolo.py
    ```
3. Une fenêtre s'ouvrira affichant le flux vidéo de votre webcam avec les détections d'objets annotées.

## Structure du Projet
- `yolo.py` : Contient le point d'entrée principal du programme.

## Fonctionnalités
- Chargement et affichage du flux vidéo de la webcam avec OpenCV.
- Détection des objets à l'aide du modèle YOLOv5 pré-entraîné.
- Annotation des objets détectés (ordinateurs et souris) sur le flux vidéo.

## Notes
- Appuyez sur `q` pour quitter la fenêtre de visualisation.
- Le modèle YOLOv5s est utilisé par défaut pour des raisons de rapidité et d'efficacité.

## Auteur
- Votre PAYONG DJOMO JEAN CHARLES TRESOR 
- Contact : Tresorpayong10@gmail.com
