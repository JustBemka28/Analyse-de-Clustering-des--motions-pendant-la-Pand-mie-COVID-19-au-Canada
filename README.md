# 📊 Analyse de Clustering des Émotions pendant la Pandémie COVID-19 au Canada

Ce projet explore les relations entre les émotions exprimées dans les commentaires d'internautes canadiens et applique des techniques de clustering pour regrouper ces émotions de manière non supervisée.

## 🔍 Objectifs du projet

- Étudier la corrélation entre différentes émotions (joie, peur, colère, tristesse, valence).
- Appliquer des algorithmes de clustering (K-means, clustering hiérarchique).
- Évaluer les résultats avec des métriques comme le score silhouette, l’indice de Davies-Bouldin, la précision, le rappel et le F1-score.
- Visualiser les clusters avec UMAP pour une interprétation qualitative.


🛠 Technologies utilisées
Python (pandas, scikit-learn, seaborn, matplotlib)

Jupyter Notebooks

Google Colab (pour UMAP)

LaTeX (pour le rapport)

Git / GitHub
## 🧪 Méthodologie

### 🌀 K-Means Clustering
- Testé pour $k \in \{2, ..., 10\}$.
- Sélection optimale de $k=2$ selon l’indice de Davies-Bouldin et le score silhouette.
- Visualisation avec UMAP pour interprétation.

### 🌳 Clustering Hiérarchique
- Méthodes explorées : Single, Complete, Average, Ward.
- Ward avec un seuil de 5 a permis de détecter 3 groupes pertinents.

### ⚙️ Évaluation
- **Métriques utilisées :**
  - Silhouette Score
  - Davies-Bouldin Index
  - Précision, Rappel, F1-score

- **Résultats notables :**
  - Bonne performance pour les classes négatives, neutres, positives.
  - Difficulté à distinguer les sentiments très positifs.

## 📷 Visualisations

Exemples disponibles dans le dossier `figures/` :
- Corrélations entre émotions
- Dendrogrammes des clusters
- Clusters UMAP colorés par sentiment


