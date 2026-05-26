# TP3 Individuel - Data Mining S3

## Description
Ce projet est un travail pratique individuel de Data Mining réalisé avec Google Colab et Python.

L’objectif du TP est :
- Charger un fichier CSV avec Pandas
- Afficher les premières lignes du dataset
- Afficher les types des colonnes
- Identifier les valeurs manquantes
- Sauvegarder le notebook sur GitHub

---

## Technologies utilisées
- Python
- Google Colab
- Pandas
- GitHub

---

## Étapes réalisées

### 1. Chargement du fichier CSV

```python
import pandas as pd

df = pd.read_csv("nom_du_fichier.csv")
```

### 2. Affichage des premières lignes

```python
df.head()
```

### 3. Affichage des types des colonnes

```python
df.dtypes
```

### 4. Vérification des valeurs manquantes

```python
df.isnull().sum()
```

### 5. Description statistique

```python
df.describe()
```

---

## Date limite
Mercredi 20 mai 2026 à 23h59
