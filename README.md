# Projet : Prédiction de Survie du Titanic (Machine Learning)

**Objectif du Projet**
Ce projet vise à développer un modèle de Machine Learning capable de prédire la probabilité de survie ou de décès d'un passager du Titanic lors du naufrage de 1912.

Le modèle utilise des variables démographiques et sociales pour déterminer les facteurs clés ayant influencé le statut de survie.

**Modèle Développé**
- Algorithme : K-Nearest Neighbors (KNeighborsClassifier)
- Fiabilité du Modèle : **80,95%** (Score en test)

**Outils et Technologies:**
- Langage: Python
- Modélisation: Scikit-learn
- Visualisation: Matplotlib, Seaborn
- Environnement: Jupiter Notebook

**Analyse et Étapes Clés**

**1. Sélection et Exploration des Caractéristiques**

Le modèle se concentre sur les trois caractéristiques (features) principales jugées les plus pertinentes pour la prédiction de survie :
- pclass (Classe du passager : 1ère, 2ème, 3ème)
- sex (Sexe : Homme/Femme)
- age (Âge)

  **2. Nettoyage et Préparation des Données**
  - Gestion des Valeurs Manquantes : Suppression des lignes contenant des valeurs manquantes (data.dropna(axis=0)).
  - Encodage des Données : La variable textuelle sex a été encodée numériquement :
    * Homme (Male) $\rightarrow$ 0
    * Femme (Female) $\rightarrow$ 1
   
  **3. Entraînement et Validation du Modèle**
  - Les données ont été divisées en ensembles d'entraînement et de test (test_size=0.2).
  - Le modèle KNeighborsClassifier a été entraîné.
  - Le modèle a atteint une fiabilité de 80,95% sur l'ensemble de test, indiquant une forte capacité prédictive.
 
    
    
    
  
