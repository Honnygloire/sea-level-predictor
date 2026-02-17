# Sea Level Predictor

Projet réalisé dans le cadre du cursus **Data Analysis with Python** de freeCodeCamp.

L’objectif est d’analyser l’évolution du niveau moyen des mers depuis 1880 et de prédire sa valeur jusqu’en 2050 à l’aide de régressions linéaires.  
Le projet utilise **Pandas**, **Matplotlib** et **SciPy** pour visualiser les données et tracer deux lignes de tendance.

---

## 📊 Objectifs du projet

À partir du fichier `epa-sea-level.csv`, le programme doit :

### ✔️ 1. Importer et analyser les données
- Charger les données historiques du niveau de la mer.
- Visualiser les valeurs brutes sous forme de scatter plot.

### ✔️ 2. Tracer une première ligne de régression (1880–2050)
- Utiliser **toutes** les données disponibles.
- Calculer la pente et l’intercept avec `linregress`.
- Prolonger la ligne jusqu’en 2050 pour prédire la montée du niveau de la mer.

### ✔️ 3. Tracer une seconde ligne de régression (2000–2050)
- Filtrer les données à partir de l’an 2000.
- Calculer une nouvelle régression linéaire.
- Prolonger cette ligne jusqu’en 2050 pour comparer la tendance récente.

### ✔️ 4. Ajouter les éléments graphiques
- Titre : **Rise in Sea Level**
- Axe X : **Year**
- Axe Y : **Sea Level (inches)**

---

## 📁 Structure du projet

```
sea_level_predictor.py   # Code principal : lecture, régressions, visualisation
epa-sea-level.csv        # Dataset fourni par freeCodeCamp
main.py                  # Script pour exécuter les tests
test_module.py           # Tests unitaires freeCodeCamp
sea_level_plot.png       # Graphique généré automatiquement
README.md                # Documentation du projet
```

---

## 🚀 Exécution

### Installer les dépendances
```bash
pip install -r requirements.txt
```

### Générer le graphique
```bash
python3 main.py
```

Le fichier `sea_level_plot.png` sera généré automatiquement.

---

## 🧠 Exemple d’utilisation

```python
from sea_level_predictor import draw_plot

fig = draw_plot()
```

---

## 📚 Source des données

Global Average Absolute Sea Level Change, 1880–2014  
US Environmental Protection Agency (EPA), CSIRO, NOAA.

---

## Auteur

**Honnygloire MBOMBOTO TO HOUNDA**  
