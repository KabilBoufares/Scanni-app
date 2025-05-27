

# 📱 Scanni – Application mobile open source de scan et sécurité intelligente

**Scanni** est une application mobile open source développée avec **React Native** (frontend) et **FastAPI (backend Python)**.
Elle permet de **scanner**, **générer**, **organiser** et **protéger** vos QR codes, documents et liens avec une interface fluide et sécurisée.

---

## 🚀 Fonctionnalités principales

### 🔍 Scanner

* Lecture instantanée de QR codes.
* Scan d’images et de documents (PDF, JPG, PNG).
* Détection automatique de contenu : URL, vCard, texte, Wi-Fi, géolocalisation.
* Reconnaissance de texte (OCR) prévue pour les versions futures.

### 🔗 Génération de QR codes

* Création de QR codes à partir de :

  * Liens URL
  * Coordonnées GPS
  * Textes libres
  * Informations de contact (vCard)
  * Réseaux Wi-Fi
* Personnalisation (format, logo, couleur) en cours de développement.

### 🗃 Historique intelligent

* Sauvegarde locale des scans et QR codes générés.
* Tri par type, date ou contenu.
* Mode privé (scan sans enregistrement).
* Exportation possible pour sauvegarde manuelle.

### ☁️ Sauvegarde cloud (Google Drive)

* Connexion facultative via compte Google.
* Sauvegarde et restauration de fichier (`.db` ou `.json`).
* Gestion des conflits de données.
* Aucun envoi automatique : respect de la vie privée.

---

## 🧠 Partie IA et Machine Learning (prévue)

Le projet inclura à l’avenir :

* Détection intelligente de liens frauduleux, de phishing ou de redirections suspectes.
* Analyse automatique de documents (résumé, classification, contenu).
* Attribution d’un score de sécurité aux liens scannés.
* Recherche intelligente dans les historiques de scan.

Les modèles IA seront d’abord hébergés dans le cloud, puis potentiellement embarqués partiellement dans l’application pour usage hors ligne.

---

## 🧱 Technologies utilisées

* **Frontend** : React Native
* **Backend** : FastAPI (Python)
* **Base locale** : SQLite ou Realm
* **Sauvegarde cloud** : Google Drive API, Supabase (optionnel)
* **OCR** : Tesseract OCR (intégration prévue)

---

## 📦 Structure du projet (proposée)

```
scanni/
├── backend/           → API FastAPI
├── frontend/          → App React Native
├── docs/              → Documentation, maquettes, spécifications
└── README.md
```

---

## 🌍 Projet open source

Scanni est un projet **open source** libre et évolutif.
L’objectif est de créer une application mobile accessible, privée et intelligente pour la gestion de QR codes et de documents.

### Contributions bienvenues :

* Amélioration de l’interface utilisateur
* Optimisation de performance
* Intégration backend/API
* Développement IA/NLP
* Traductions

---

## 📄 Licence

Scanni est publié sous **licence MIT**.
Vous pouvez librement utiliser, modifier et redistribuer ce projet, à condition de mentionner l’auteur original.

---

## ✉️ Contact

* Auteur : *Kabil Boufares*
* GitHub : *https://github.com/KabilBoufares*
* Projet lancé en 2025

---

