 K-Nearest Neighbors (KNN) Classifier

This project uses Python’s built in library called NumPy to implement K-Nearest Neighbors Algorithm from scratch to classify wine types based on their physicochemical properties.

 Project Overview
- Objective: Classify wines into three distinct categories based on a dataset of 13 features (e.g., alcohol content, malic acid, ash).
- Methodology: - Data ingestion and preprocessing using Google Colab.
  - Z-score standardization to ensure features contribute equally to distance calculations.
  - Custom implementation of Euclidean distance, neighbor retrieval, and majority voting.

 Key Tasks
1. KNN Implementation: Built a custom classifier using Euclidean distance for proximity measurement.
2. Hyperparameter Tuning: Evaluated model performance across different $K$ values ($K \in \{1, 3, 5, 7\}$).
3. Performance Analysis: Visualized the relationship between $K$ and classification accuracy, identifying $K=5$ and $K=7$ as the optimal settings (97.22% accuracy).

 Key Findings
- Increasing $K$ improved classification accuracy from 94.4% to 97.2%, suggesting that higher values of $K$ help mitigate the influence of noisy data points.
- The consistency in results between neighboring $K$ values (1 & 3, 5 & 7) highlights the stable decision boundaries within the feature space.

 Technologies Used
- Language: Python
- Environment: Google Colab
- Libraries: `numpy` (math/distance), `pandas` (data handling), `matplotlib` (performance visualization)
