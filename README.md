# K-Nearest Neighbors (KNN) Classification  

## Objective  
Implement and understand the **K-Nearest Neighbors (KNN)** algorithm for classification problems. Learn about instance-based learning, the effect of K, normalization importance, and distance metrics.


## Tools & Libraries  
- Python  
- Scikit-learn  
- Pandas  
- Matplotlib  
- NumPy  


## Dataset  
- **Iris Dataset** (loaded from Scikit-learn)  
- Features: Sepal length, Sepal width, Petal length, Petal width  
- Target: Species classification (Setosa, Versicolor, Virginica)  


## Steps Implemented  

1. **Data Loading** – Imported Iris dataset.  
2. **Feature Normalization** – Standardized features using `StandardScaler`.  
3. **Train-Test Split** – Split data into training and test sets (80-20).  
4. **KNN Model** – Used `KNeighborsClassifier` from Scikit-learn.  
5. **Experiment with K** – Tested K = 3, 5, 7 and compared accuracy.  
6. **Evaluation** – Calculated accuracy score, confusion matrix, classification report.  
7. **Visualization** – Plotted decision boundaries for the first two features.  


## Results  
- Accuracy varied with different K values.  
- Normalization significantly improved accuracy.  
- Decision boundary visualization helped understand classification regions.


## Key Learnings  
- KNN is an **instance-based** and **lazy learning** algorithm.  
- The choice of K affects bias-variance trade-off.  
- Normalization is essential for distance-based algorithms.  
- KNN can handle multi-class classification using majority voting.
