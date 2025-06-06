# Credit Card Fraud Detection – EDA

## Project Summary

This project performs an exploratory data analysis (EDA) on the credit card fraud detection dataset. Key steps taken:

- Loaded and explored the original dataset (`creditcard.csv`).
- Analyzed the distribution of fraudulent vs. non-fraudulent transactions.
- Visualized features using histograms, boxplots, and correlation heatmaps.
- Applied resampling techniques (RandomOverSampler) to address the class imbalance.

The cleaned and balanced dataset is provided in the file `creditcard_cleaned.csv`. It includes the original features and a balanced target variable, ready for use in model training.

## Next Steps

1. Train classification models (e.g., Logistic Regression, Decision Trees, Random Forest).
2. Evaluate model performance using precision, recall, F1-score, and confusion matrix.
3. Explore advanced techniques like SMOTE, Isolation Forest, or autoencoders.
4. Build a full machine learning pipeline with cross-validation and performance metrics.
5. Optional: Deploy a prediction API using Flask or FastAPI.

## Files Included

- `eda_creditcard_fraud.ipynb`: Notebook containing the EDA process.
- `creditcard_cleaned.csv`: Cleaned and resampled dataset for modeling. Downloadable inside the notebook.
