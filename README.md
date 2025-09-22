# Signify - IA pour la reconnaissance de la Langue des Signes

Ce projet vise à développer une application capable de reconnaître des gestes de la Langue des Signes en temps réel.


## Installation
Prérequis : **Python 3.11.9** installé  

## Cloner le dépôt et installer les dépendances
```
git clone https://github.com/<ton-user>/signify.git
cd signify
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

## Récupérer le dataset
1. Se rendre sur https://www.kaggle.com/datasets/grassknoted/asl-alphabet
2. Télécharger le zip
3. Créer le dossier data dans le dossier signify
4. Extraire le dataset dans signify/data 

# Prévisualisation caméra
Actuellement seulement la détection de la main et des 21 points clés
```
python -m src.hand_preview
```

