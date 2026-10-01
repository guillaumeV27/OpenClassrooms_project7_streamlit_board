# Projet 7 — Implémentez un système de scoring

## 📋 Présentation du projet

Ce dépôt fait partie du **Projet 7 de la formation Data Scientist en alternance d'OpenClassrooms**.

**« Prêt à dépenser »** est une société financière qui propose des crédits à la consommation à des personnes ayant **peu ou pas d'historique de crédit**.

Dans le cadre de ce projet, un modèle de Machine Learning a été développé afin d'estimer le **risque de défaut d'un client** et d'aider à la décision d'accorder ou non un crédit.

Ce dépôt contient le code du **dashboard interactif** permettant de visualiser les résultats du modèle de scoring.

---

## 🎯 Objectif du dashboard

Le dashboard a pour objectif de rendre les résultats du modèle de scoring **compréhensibles et accessibles à l'utilisateur**.

Il permet notamment de :

- sélectionner un client ;
- afficher la décision associée à sa demande de crédit ;
- visualiser son **score de crédit** et sa **probabilité de défaut** ;
- comparer les caractéristiques du client avec celles d'autres clients ;
- visualiser les principales variables ayant influencé la prédiction du modèle ;
- faciliter l'interprétation de la décision prise par le modèle.

---

## 🖥️ Fonctionnement

Le dashboard communique avec une **API de prédiction** développée avec Flask.

Le fonctionnement général de l'application est le suivant :

```text
Utilisateur
    ↓
Dashboard
    ↓
API Flask
    ↓
Modèle de Machine Learning
    ↓
Prédiction du risque de défaut
    ↓
Affichage et interprétation des résultats
```

---

## 🔗 API

Le dashboard utilise l'API de scoring disponible à l'adresse suivante :

[https://flask-api-predict.onrender.com/](https://flask-api-predict.onrender.com/)

L'API permet au dashboard d'interroger le modèle de Machine Learning afin de récupérer les prédictions associées aux clients.

---

## 🛠️ Technologies utilisées

- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib / Seaborn
- Plotly
- Requests
- Flask API
- Git / GitHub

---

## 📁 Structure du projet

```text
.
├── app.py
├── requirements.txt
├── data/
├── README.md
└── ...
```

> La structure peut varier selon la version actuelle du projet.

---


``

## 📊 Interprétation des résultats

Le dashboard présente les résultats du modèle de manière visuelle afin de faciliter leur compréhension.

Pour chaque client, il permet d'observer :

- la **probabilité de défaut** prédite par le modèle ;
- la décision **crédit accordé / crédit refusé** ;
- les principales caractéristiques ayant contribué à la décision du modèle.

L'objectif est de rendre le fonctionnement du modèle de scoring plus **transparent et interprétable**.

---

## 🚀 Déploiement

Le dashboard peut être déployé en ligne afin de permettre son utilisation sans installation locale.

Lien vers le dashboard :

[Accéder au dashboard](https://appapp-hwkmzph88qbzs2tf7nfhnh.streamlit.app/)
---

## 👨‍💻 Auteur Guillaume Vechambre

Projet réalisé dans le cadre de la formation **Data Scientist d'OpenClassrooms**.



