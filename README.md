## Drug Classification Model

A Jupyter Notebook on drug classification using machine learning techniques such as decision trees and random forest classifiers. The dataset used (`drug200.csv`) contains information about patients including their age, sex, blood pressure, cholesterol level, sodium to potassium ratio, and the drug type they were prescribed.

## Installation

### To run this script, you'll need to install the following Python packages:

- [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
- [numpy](https://numpy.org/install/)
- [matplotlib](https://matplotlib.org/stable/users/installing.html)
- [seaborn](https://seaborn.pydata.org/installing.html)
- [scikit-learn](https://scikit-learn.org/stable/install.html)
- [imblearn](https://imbalanced-learn.org/stable/install.html)

### You can install these packages using pip:

#### `pip install pandas numpy matplotlib seaborn scikit-learn imblearn`

## Usage

1. Clone the repository: `https://github.com/richie-0/drug_classification_tree`

2. Navigate to the directory: `cd repository`

3. Run the script: `python decision_trees.ipynb`
### Contents:

1. **Data Preprocessing and Exploration:**
   - Importing necessary libraries and loading the dataset.
   - Displaying summary statistics and checking for missing values.
   - Examining data types and addressing any imbalances in categorical data.
   - Visualising the dataset with pair plots and correlation heatmaps.

2. **Model Development:**
   - Label encoding ordinal features and one-hot encoding nominal features.
   - Training a decision tree classifier and evaluating its performance.
   - Determining optimal tree depth through visualisation.
   - Training a pruned decision tree for improved generalisation.
   - Utilising a random forest classifier and assessing its accuracy.
   - Analysing feature importances to understand predictive factors.
   - Conducting hyperparameter tuning using random search and evaluating the best model.

3. **Handling Class Imbalance:**
   - Exploring oversampling (SMOTE) and undersampling techniques.
   - Training new random forest models with oversampled/undersampled data.
   - Evaluating and comparing the performance of these models.

4. **Results Interpretation:**
   - Analysing feature importances in the undersampled model.
   - Visualising decision trees from the random forest models for better understanding.

### Instructions:

- Ensure you have Jupyter Notebook installed to run the provided `.ipynb` file.
- Download the `drug200.csv` dataset and place it in the same directory as the notebook.
- Execute each cell sequentially to observe data preprocessing, model development, and evaluation steps.
- Experiment with hyperparameters to improve model performance.

### Note:

- This Jupyter Notebook is just practise using a dataset from [Kaggle](https://www.kaggle.com/datasets/pablomgomez21/drugs-a-b-c-x-y-for-decision-trees/data).
