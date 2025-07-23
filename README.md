# Non-Parametric Regression using k-NN Density Estimation
This project explores **non-parametric regression** using the **k-Nearest Neighbors (k-NN)** algorithm on a multivariate animal dataset. The aim is to predict the average lifespan of animals using various features and assess the model performance across multiple strategies.

##  Project Overview
- Apply **k-NN Regression** to predict animal lifespan.
- Use **Mean Squared Error (MSE)** and **Root Mean Squared Error (RMSE)** for evaluation.
- Perform **dimensionality reduction (PCA)** to identify dominant features.
- Conduct **density estimation** to understand data distribution across different feature sets.
- Compare performance between:
  - All features
  - 2 Dominant PCA features
  - Top 7 PCA components

##  Dataset

- **Source:** [Kaggle Dataset – Animal Lifespan](https://www.kaggle.com/datasets/jad201012/animals-lifespan)
- **File:** `animal_lifespan.csv` (located in `dataset/` folder)

## Preprocessing

- Corrected spelling errors
- Handled missing values
- Consolidated living places
- Applied one-hot encoding
- Cleaned dataset saved as `cleaned_animals_lifespan.csv`

## Experiments

1. **k-NN Regression on All Features**
   - RMSE vs K-value plot

2. **PCA Analysis**
   - Scree plot of eigenvalues
   - Extracted top 2 and top 7 principal components

3. **k-NN Regression on PCA-reduced data**
   - Compared RMSE for:
     - All features
     - Top 2 PCA features
     - Top 7 PCA components

4. **Density Estimation**
   - Estimated volume and density across different input spaces
  
  ## Conclusion
This project demonstrated the effectiveness of k-NN for both regression and density 
estimation on animal data. By analyzing RMSE across different k-values, the optimal k 
for accurate prediction was identified. Dimensionality reduction using PCA improved 
efficiency without significant loss of information.
  
