# Project 7 — Implement a Credit Scoring System

[🇫🇷 Version française](README_FR.md)


## 📋 Project Overview

This repository is part of **Project 7 of the OpenClassrooms Data Scientist apprenticeship program**.

**"Prêt à dépenser"** is a financial company that provides consumer loans to people with **little or no credit history**.

As part of this project, a Machine Learning model was developed to estimate a client's **risk of default** and help determine whether a loan application should be approved or rejected.

This repository contains the code for the **interactive dashboard** used to visualize the results of the credit scoring model.

---

## 🎯 Dashboard Objective

The dashboard aims to make the credit scoring model's results **clear and accessible to users**.

It allows users to:

- select a client;
- display the decision associated with the client's loan application;
- visualize the client's **credit score** and **probability of default**;
- compare the client's characteristics with those of other clients;
- visualize the main features that influenced the model's prediction;
- facilitate the interpretation of the model's decision.

---

## 🖥️ How It Works

The dashboard communicates with a **prediction API** developed with Flask.

The general workflow of the application is as follows:

```text
User
    ↓
Dashboard
    ↓
Flask API
    ↓
Machine Learning Model
    ↓
Default Risk Prediction
    ↓
Results Visualization and Interpretation
```

---

## 🔗 API

The dashboard uses the credit scoring API available at:

[https://flask-api-predict.onrender.com/](https://flask-api-predict.onrender.com/)

The API allows the dashboard to query the Machine Learning model and retrieve predictions for individual clients.

---

## 🛠️ Technologies Used

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

## 📁 Project Structure

```text
.
├── app.py
├── requirements.txt
├── data/
├── README.md
└── ...
```

> The project structure may vary depending on the current version of the application.

---

## 📊 Results Interpretation

The dashboard presents the model's results visually to make them easier to understand.

For each client, users can view:

- the **probability of default** predicted by the model;
- the **loan approved / loan rejected** decision;
- the main features that contributed to the model's decision.

The goal is to make the credit scoring model more **transparent and interpretable**.

---

## 🚀 Deployment

The dashboard is deployed online and can be used without any local installation.

Dashboard:

[Access the dashboard](https://appapp-hwkmzph88qbzs2tf7nfhnh.streamlit.app/)

---

## 👨‍💻 Author

**Guillaume Vechambre**

Project developed as part of the **OpenClassrooms Data Scientist program**.
