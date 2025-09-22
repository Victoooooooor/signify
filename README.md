# Signify - IA pour la reconnaissance de la Langue des Signes

Ce projet vise à développer une application capable de reconnaître des gestes de la Langue des Signes en temps réel.

## Fonctionnalités
- Détection et suivi des mains avec **MediaPipe**
- Extraction des landmarks (21 points clés)
- Classification en temps réel avec un modèle entraîné en **PyTorch**
- Interface de prévisualisation caméra avec **OpenCV**

## Installation
Prérequis : **Python 3.11.9** installé  


## Création et activation d’un environnement virtuel
```bash
python -m venv .venv
```
## Activation (Windows)
```
.venv\Scripts\activate
```

## Activation (Linux / macOS)
```
source .venv/bin/activate
```
## Cloner le dépôt et installer les dépendances
```
git clone https://github.com/<ton-user>/signify.git
cd signify
pip install -r requirements.txt
```

# Prévisualisation caméra
Actuellement seulement la détection de la main et des 21 points clés
```
python -m src.hand_preview
```
# Roadmap

 Entraînement du modèle de classification

 Reconnaissance de plusieurs gestes/phrases

 Interface utilisateur améliorée (GUI ou webapp)

 Exportation vers une application mobile
