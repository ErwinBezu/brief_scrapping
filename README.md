# Projet Web Scraping - Python

## Présentation

Ce projet regroupe trois notebooks Jupyter permettant de découvrir et de pratiquer le web scraping avec Python.

L'objectif est de récupérer des données depuis des sites web, de les structurer et de les analyser avec pandas, tout en respectant les bonnes pratiques de scraping.

## Contenu du projet

### 1. Books to Scrape

- Extraction des informations des livres : titre, prix, note, disponibilité et description.
- Gestion de la pagination.
- Récupération des informations détaillées.
- Création et manipulation de DataFrames avec pandas.

### 2. Scraping responsable

- Consultation et interprétation du fichier `robots.txt`.
- Utilisation d'un `User-Agent`.
- Ajout de pauses entre les requêtes.
- Gestion des erreurs HTTP (429 et 503).
- Mise en place de nouvelles tentatives avec un délai progressif.

### 3. Quotes to Scrape

- Extraction des citations, auteurs et tags.
- Récupération des fiches biographiques des auteurs.
- Suppression des doublons pour limiter les requêtes.
- Fusion des données avec pandas.
- Analyse des auteurs les plus cités et des tags les plus fréquents.

## Technologies utilisées

- Python
- Requests
- BeautifulSoup4
- pandas
- Jupyter Notebook

## Installation

### 1. Cloner le dépôt

```bash
git clone URL_DU_DEPOT
cd NOM_DU_PROJET
```

### 2. Créer un environnement virtuel

```bash
python -m venv .venv
```

Sous Windows :

```bash
.venv\Scripts\activate
```

### 3. Installer les dépendances

```bash
pip install -r requirements.txt
```

### 4. Lancer Jupyter Notebook

```bash
jupyter notebook
```

Ouvrir ensuite les notebooks pour exécuter les exercices.

## Objectifs pédagogiques

- Comprendre le fonctionnement du web scraping.
- Analyser la structure HTML d'une page.
- Extraire des données avec BeautifulSoup.
- Parcourir plusieurs pages automatiquement.
- Respecter les bonnes pratiques de scraping.
- Nettoyer, structurer et analyser les données avec pandas.
- Limiter les requêtes inutiles et éviter les doublons.