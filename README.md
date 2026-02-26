# 🏡 Analyse du Marché Immobilier - Projet Python Avancé

**Auteurs** : Ibrahima BA, Mahamat Nour MAHAMAT SULTAN, Moustapha MENDY

## 📋 Description

Pipeline complet d'analyse de données immobilières scrapées sur SeLoger : extraction, nettoyage, géolocalisation, visualisation et prédiction de prix.

## 🛠️ Stack Technique

- **Scraping** : Selenium
- **Data Processing** : Pandas, Regex, Geopy
- **Visualisation** : Matplotlib, Seaborn, Folium
- **Machine Learning** : Scikit-learn (Régression Linéaire)

## 📊 Dataset

- **Source** : SeLoger
- **Volume** : 2 740 annonces nettoyées
- **Features** : Prix, Surface, Pièces, Type, Localisation (GPS), Prix/m²

## 🚀 Pipeline

1. **Scraping** → Extraction automatisée des annonces
2. **Cleaning** → Conversion types, gestion des valeurs manquantes, filtrage des outliers
3. **Enrichissement** → Géocodage des adresses (Lat/Lon)
4. **Analyse** → Statistiques descriptives et cartographie interactive
5. **ML** → Prédiction des prix par régression linéaire

## 📈 Résultats Clés

| Métrique | Valeur |
|----------|--------|
| **R² Score** | 0.51 |
| **MAE** | 144 395 € |
| **Corrélation Surface/Prix** | Forte |

**Insight principal** : Distribution asymétrique des prix (majorité de biens accessibles + queue de luxe), fortes disparités régionales.

## 🗺️ Cartographie

Carte interactive Folium avec clustering des annonces par type (Appartement/Maison).

## 🤖 Modèle Prédictif

⚡ Lancement Rapide

pip install pandas numpy matplotlib seaborn folium scikit-learn geopy selenium
python enrichissement_geo_smart.py  # Scraping + géocodage
jupyter notebook analyse_immobiliere.ipynb

Estimation du prix basée sur la surface :
```python
# Exemple : 50m² → ~233 500€


**Version ultra-courte** si besoin :

```markdown
# 🏡 Analyse Immobilière SeLoger

Pipeline Python complet : Scraping (Selenium) → Cleaning (Pandas) → Géocodage (Geopy) → Visualisation (Folium) → Prédiction (Scikit-learn).

**Dataset** : 2 740 annonces | **Modèle** : Régression Linéaire (R²=0.51)  
**Stack** : Python, Pandas, Folium, Scikit-learn

*Auteurs : Ibrahima BA



