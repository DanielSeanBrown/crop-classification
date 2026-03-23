# Crop Classification

### Overview
This project aimed to create a classification model for suggesting the ideal crop to grow given a set of soil characteristics. This was achieved through a variety of supervised learning models and further work was done to test how models fair with distorted data. Coefficient analysis also revealed which soil characteristics affect which crops and how. For full documentation, please refer to the report file.

### Aims and Goals
1 - Construct a high-performance model for crop classification.
2 - To interpret models for understanding which properties of soil are most crucial for differing crops.


### Methods
- After data cleaning and exploratory analysis, logistic regression was used as a baseline high interpretability model.
- Regularisation techniques were used to reduce overfitting on initial modelling and for feature selection.
- Various classical ML models were used to compare and select a good classifier. These included Logistic Regression, Random Forest, Support Vector, Naive Bayes, KNN, XGBoost and GradientBoosting models.
- Models were evaluated using precision, recall and F-1 scores.
- Noise and Null value injection as used to observe model robustness to real life varying conditions in agricultural measurements.
- Coefficient simulation was used to produce datasets for clustering.
- Clustering was performed to observe how and which crop types group together.

### Key Results and Insights
A tuned Random Forest model met the goal of producing a high-performance classification model and the extensive analysis in the dataset found which features are most significant in aiding crop growth.

### Further Extensions
Revisiting this project, I would like to extend the clustering performed to be more informative on how dis/similar crops are. This could mean adding some sort of distance metric beyond a dendrogram. I would also like to add further data sources to gain more data variety and to extend the robustness testing section of the project. these would be important as I would like to put heavier emphasis on measuring soil characteristics in conditions where readings may be slightly dubious.

### Tools & Technologies
Language: Python
Environment: JupyterLabs
Techniques: Machine Learning, Clustering, Dimensionality Reduction, Simulation


Project Details
Duration: 2 months
Dataset: 22 crop types, 7 features, 2200 rows

Grade: [73% (Distinction)].

