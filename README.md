# LaLiga Data Analysis
Projet de data mining sur les données officielles de LaLiga de la saison 1993-1994 à 2024-2025.

## Fonctionnalités
- **Visualisation des buts** : line chart de l'évolution des buts marqués et concédés saison après saison
- **Résultats de matchs** : line chart comparatif victoires / défaites / nuls par saison
- **Répartition des tirs** : stacked area chart tirs / tirs cadrés / buts par saison
- **Corrélations** : heatmap (Seaborn) de la matrice de corrélation entre toutes les statistiques
- **Prédiction de buts** : régression linéaire (SelectKBest + StandardScaler) à partir des tirs et tirs cadrés
- **Prédiction de victoires** : Ridge Regression avec validation temporelle (entraînement sur les saisons passées uniquement)
- **Calcul de cote** : comparaison pondérée des statistiques de deux clubs pour estimer les chances de victoire selon le lieu du match (domicile / extérieur)

## Technologies
Python · Pandas · Matplotlib · Seaborn · scikit-learn

## Données
Fichiers CSV issus des statistiques officielles de LaLiga, une saison par fichier (de 1993-1994 à 2024-2025).  
Source : [datahub.io/core/spanish-la-liga](https://datahub.io/core/spanish-la-liga) — licence PDDL (domaine public)  
Données originales : [football-data.co.uk](http://www.football-data.co.uk/)
