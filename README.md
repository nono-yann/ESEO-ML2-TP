# Machine Learning 2 — Travaux pratiques (ESEO, E4e)

Travaux pratiques de Machine Learning appliqué aux données financières (S&P 500 et Bitcoin), réalisés en Python dans des notebooks Jupyter.

## Contenu

| TP | Sujet | Notions clés |
|---|---|---|
| [TP1](TP1_ML2_nono_E4e.ipynb) | Prédiction de la direction du marché (SPY) | Classification, fuite d'information, split temporel, régression logistique, Random Forest, réseau de neurones, biais/variance |
| [TP2](TP2_ML2_nono_E4e.ipynb) | Séries temporelles financières (SPY) | Stationnarité (test ADF), autocorrélation, ARIMA, analyse des résidus, clustering de volatilité, GARCH |
| [TP3](TP3_ML2_nono_E4e.ipynb) | Machine learning temporel (BTC-USD) | Features retardées, régression du rendement futur, ARIMA vs Random Forest vs MLP, split aléatoire vs temporel, validation rolling |
| [TP4](TP4_ML2_nono_E4e.ipynb) | Clustering et régimes de marché (BTC-USD) | Normalisation, K-Means, méthode du coude, silhouette, DBSCAN, sensibilité à eps, HDBSCAN |

Chaque notebook contient le code, les explications des concepts et l'analyse des résultats.

## Installation

Python 3.12 recommandé (TensorFlow, utilisé dans le TP1, ne supporte pas encore les toutes dernières versions de Python).

```bash
pip install yfinance pandas numpy matplotlib seaborn scikit-learn statsmodels arch tensorflow
```

Les données sont téléchargées automatiquement depuis Yahoo Finance avec `yfinance` : une connexion internet est nécessaire.

## Utilisation

Ouvrir un notebook dans VS Code ou Jupyter, puis exécuter toutes les cellules dans l'ordre (« Run All »).

## Auteur

Yann Monkam Nono — élève ingénieur en Data & IA, ESEO Paris–Vélizy
