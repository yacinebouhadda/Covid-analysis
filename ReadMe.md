# Analyser le dataset du covid

# Démarche de travail

## 1. Définir un objectif mesurable : 
    Prédire si une personne est inféctée en fonction des données cliniques disponibles.
### Métrique :
    La précision, Recall, Score F1

## 2. EDA (analyse et exploration)

## 3. pré processing

## 4. Modeling

### 1. Analyse de forme : 
    Identifier la target  "df.describe()"  
    Nombre de ligne et de colonnes "pd.shape"
    Type de variables" value_counts"
    Identifier les valeurs manquantes "pandas"

### 2. Analyse de fond :
    Visualiser la target  "10% de cas posiif"
    Compréhension des differentes varibales "float, int, subject"
    Visualiser les relations features-target 
    Identifier les outils

## Transformer le dataset pour le mettre au format du ML
    1. Creation des Train set / Test set
    2. Elimination des Nan
    3. Encodage
    4. Supression des outils néfastes au modéle
    5. Feature Selection
    6. Feature Engineering
    7. Feature Scalling

## Definir un modéle ML pour notre objectif
    1. Deffinir une fonction d'évaluation
    2. Entrainement des deffirents modéle
    3. Optimisation avec GridSearchCV
    4. Analyse des erreur
    5. Prise de decision
