# Customer Transaction Prediction

This project involves predicting whether a customer will make a transaction based on various features. The task is binary classification using machine learning techniques, with a focus on model performance and interpretability.

## Project Structure

- `Customer Transaction Prediction PTID-CDS-FEB-25-2431.ipynb`: Jupyter notebook containing data loading, exploratory data analysis, feature engineering, model training, and evaluation.
- `README.md`: Project overview and setup instructions.

## Objective

1. Perform exploratory data analysis to understand patterns in customer behavior.
2. Build classification models to predict the likelihood of a customer making a transaction.
3. Compare multiple models and select the best-performing one.
4. Document challenges and strategies used during the project lifecycle.

## Technologies Used

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- XGBoost or LightGBM (if applicable)

## Model Evaluation

The following models were evaluated:
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Models

Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

The final model was selected based on its performance on the test set and generalization capability.

## Challenges Faced

- Handling class imbalance in the target variable
- Feature selection among high-dimensional anonymized data
- Model tuning to avoid overfitting

## How to Run

1. Clone this repository:
   ```
   git clone https://github.com/mahispro9092/customer-transaction-prediction.git
   ```
2. Install required packages:
   ```
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```
   jupyter notebook Customer\ Transaction\ Prediction\ PTID-CDS-FEB-25-2431.ipynb
   ```
