# DL Models Deployment — Classification d’images avec MobileNetV2 & Gradio

## 📌 Description du projet

Ce projet démontre le déploiement d’un modèle de deep learning pour la classification d’images,  
en utilisant le modèle **MobileNetV2** pré-entraîné sur ImageNet,  
avec une interface utilisateur simple et interactive via **Gradio**.

L’application permet de charger une image et d’obtenir les **3 classes les plus probables**.

## 👥 Membres de l’équipe

- Brahim Assabir
- Nadia Kendoul
  
## 🗂️ Structure du projet
```text
DL-Models-Deployment/
├── notebook.ipynb
├── requirements.txt
├── README.md
└── demo_video.mp4
```
## ⚙️ Configuration de l’environnement

1️⃣ Cloner le dépôt

git clone https://github.com/brahim-assabir/DL-Models-Deployment.git
cd DL-Models-Deployment

2️⃣ Créer et activer un environnement virtuel

python -m venv venv
venv\Scripts\activate

3️⃣ Installer les bibliothèques nécessaires

pip install -r requirements.txt

🚀 Lancer l’application
Depuis Jupyter Notebook
Ouvrir le notebook

jupyter notebook notebook.ipynb

Exécuter toutes les cellules pour démarrer l’interface Gradio.

🧠 Informations sur le modèle

Modèle : MobileNetV2 (pré-entraîné sur ImageNet)

Tâche : Classification d’images (Top-3 prédictions)

🎥 Démonstration

👉 Cliquez ici pour voir la vidéo : 

📚 Ressources

TensorFlow

Gradio

MobileNetV2 Paper
