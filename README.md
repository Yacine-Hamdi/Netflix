# 📊 Analyse du Catalogue Netflix vs. Attentes des Utilisateurs  

## 📌 Description du Projet  
Ce projet a pour but de comparer l’offre de contenu proposée par Netflix avec les attentes exprimées par les utilisateurs dans le rapport *What We Want*. Nous avons réalisé un **web scraping** du catalogue Netflix pour collecter les titres disponibles, puis nous avons analysé ces données en les croisant avec celles du rapport pour identifier les éventuels écarts entre l’offre et la demande.  

## 🛠 Technologies utilisées  
- **Python** : Scraping, nettoyage et analyse des données  
- **BeautifulSoup / Selenium** : Extraction des données depuis Netflix  
- **Pandas** : Traitement et manipulation des données  
- **Matplotlib / Seaborn** : Visualisation des tendances  
- **Power BI** : Création de dashboards interactifs  

## 📂 Structure du projet  
📁 `data/` → Contient les données brutes et nettoyées  
📁 `notebooks/` → Jupyter notebooks avec les analyses et visualisations  
📁 `scripts/` → Scripts Python pour le scraping et le nettoyage  
📁 `reports/` → Rapports et insights issus des analyses  

## 🔍 Objectifs de l'Analyse  
1. **Comparer** le catalogue Netflix aux attentes des utilisateurs  
2. **Identifier** les genres et types de contenu sous-représentés  
3. **Analyser** les tendances en fonction des régions et catégories  
4. **Recommander** des améliorations potentielles pour la plateforme  

## 📈 Résultats clés  
🟢 Netflix couvre bien les catégories les plus populaires, mais…  
🔴 Certains genres demandés par les utilisateurs sont sous-représentés  
📊 La répartition des films et séries varie fortement selon les régions  

## 🚀 Reproduire l'Analyse  
1. Clonez ce repository :  
   ```bash
   git clone https://github.com/username/netflix-analysis.git
   cd netflix-analysis
