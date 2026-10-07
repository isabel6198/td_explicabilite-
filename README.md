# Interprétabilité de modèles : Boston Housing

Comparaison d'une régression linéaire et d'un random forest pour prédire la valeur des logements du Boston Housing Dataset, avec un focus sur l'interprétation des modèles (TP du Master 2 Économétrie et Statistiques Appliquées, IAE Nantes).

## Contenu
- Nettoyage des données et création de variables (log, termes quadratiques)
- Modèles de référence : régression linéaire et random forest, puis optimisation des hyperparamètres du random forest
- Interprétation globale : PDP / ALE, permutation feature importance
- Interprétation locale (par individu) : ICE, LIME, SHAP waterfall
- Graphiques SHAP : beeswarm et scatter

## Données
Boston Housing Dataset : caractéristiques socio-économiques et immobilières de quartiers de Boston, utilisé pour un problème classique de régression.

## Technologies
Python · scikit-learn · SHAP · LIME
