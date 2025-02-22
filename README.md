# Classification Automatique de Documents 📄✨

## Description 📌
Ce projet vise à automatiser la classification de documents administratifs à l'aide de l'intelligence artificielle. Développé lors d'un stage au sein de la Province de Sidi Kacem, il utilise des techniques de Machine Learning pour organiser efficacement les documents et optimiser leur gestion.

## Fonctionnalités 🛠️
- 📂 Classification automatique des documents PDF en catégories spécifiques (Économie, Équipement, Social, Urbanisme).
- 🤖 Utilisation d'un modèle de Machine Learning basé sur **Naïve Bayes Multinomiale**.
- 🏷️ Extraction et prétraitement des textes des documents pour l'entraînement du modèle.
- 🌐 Interface utilisateur développée avec **Flask** pour permettre le téléchargement et l'affichage des résultats de classification.

## Technologies utilisées 🚀
- **Langages** : Python, HTML/CSS, JavaScript
- **Frameworks et bibliothèques** : Flask, Scikit-learn, PyPDF2
- **Environnements** : PyCharm, Anaconda
- **Système de versionnement** : Git/GitHub

## Installation 🖥️
1. **Cloner le projet**  
   ```bash
   git clone https://github.com/salmakk/Syst-me-intelligent-de-classification
   ```

2. **Créer un environnement virtuel**  
   ```bash
   python -m venv env
   source env/bin/activate  # Pour Linux/Mac
   env\Scripts\activate      # Pour Windows
   ```

## Utilisation 🚀
1. **Lancer l'application Flask**  
   ```bash
   python classification.py
   ```
2. **Accéder à l'interface**  
   Ouvre un navigateur et va sur `http://127.0.0.1:5000/`

3. **Uploader un document**  
   - Sélectionne un fichier PDF.
   - Le modèle analyse et classe automatiquement le document.
   - La catégorie détectée est affichée à l’utilisateur.

## Améliorations possibles 🔧
- Intégration d'autres modèles de Machine Learning (ex: SVM, Random Forest).
- Développement d'une API REST pour interagir avec d'autres applications.
- Optimisation de l'interface utilisateur avec React ou Vue.js.

## Auteur 👩‍💻
**Salma EL BEKKARI**  
Projet réalisé dans le cadre d'un stage d'observation.

