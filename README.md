# Logistic Regression - DonorsChoose Dataset

This project implements **Logistic Regression (LR)** to predict whether a project proposal on DonorsChoose.org will be approved. The analysis includes extensive feature engineering, text preprocessing, and hyperparameter tuning to optimize model performance.

## Dataset
- **DonorsChoose.org project proposals**:
  - Text data: Project titles, essays, resource summaries.
  - Categorical data: Grade categories, subject categories, and school state.
  - Numerical data: Resource quantity and price.

## Key Features
- **Text Processing**:
  - Preprocessed project titles and essays using BOW and TF-IDF techniques.
  - Applied Word2Vec embeddings and sentiment analysis to essays and titles.
  
- **Categorical Data**:
  - One-hot encoded grade categories, teacher prefixes, subject categories, and school states.

- **Numerical Data**:
  - Normalized resource quantities and prices.

## Modeling
- **Logistic Regression**:
  - Applied LR to the processed data using L2 regularization.
  - Tuned hyperparameters using grid search for optimal results.

## Results
- **AUC (Area Under Curve)**: Achieved 0.77 AUC score with the best-performing model.
- **Accuracy**: Model accuracy improved with hyperparameter tuning and feature engineering.

## Conclusion
The Logistic Regression model effectively predicts project approvals using text, categorical, and numerical features, with text features playing a significant role in determining project success.
