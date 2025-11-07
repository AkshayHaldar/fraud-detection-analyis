# Machine Learning Project: Credit Card Fraud Detection

This project follows a complete machine learning workflow to detect fraudulent credit card transactions.

**Key Steps:**
1.  Load and explore an imbalanced dataset from Kaggle.
2.  Preprocess and scale the data.
3.  Balance the training data using the SMOTE technique.
4.  Train and evaluate three base models: SVM, Random Forest, and KNN.
5.  Apply and compare four ensemble techniques: Hard Voting, Soft Voting (Averaging), Weighted Averaging, and Stacking.
6.  Generate a final comparison chart to visualize model performance.

## How to Run
1.  Create a virtual environment and activate it.
2.  Install the required packages: `pip install -r requirements.txt`
3.  Place the `creditcard.csv` dataset in the `data/raw/` directory.
4.  Run the Jupyter Notebook located at `notebooks/1_fraud_detection_analysis.ipynb`.