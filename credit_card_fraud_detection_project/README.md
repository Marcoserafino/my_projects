
# Credit card fraud detection project

In this project, we perform various steps in the data analysis process, including data cleaning, preprocessing, model training, and evaluation. The primary goal is to build a model that can detect fraudulent transactions based on features such as transaction amount, time, and other relevant factors.




## Authors

- [@Marcoserafino](https://www.github.com/Marcoserafino)

## Files

- `creditcard_2023.csv`: The dataset containing credit card transactions. Each row represents a transaction, with a `Class` column indicating whether the transaction is fraudulent (`1`) or not (`0`).
- `fraud_detection_project.ipynb`: The Jupyter notebook where the entire analysis pipeline is implemented.

## Dataset
The dataset used in this project contains credit card transactions, with the target variable `Class` indicating whether a transaction is fraudulent (1) or not (0).

## Steps & Analysis
1. **Data Preprocessing**: The dataset is loaded and cleaned, checking for missing values and scaling the features using `StandardScaler`.
2. **Modeling**: A **Random Forest Classifier** is trained on the preprocessed data. We use 5-fold cross-validation to assess the model's performance.
3. **Model Evaluation**: The model's performance is evaluated using a **classification report**, **confusion matrix**, and **ROC curve**.

## Results
The model achieved an accuracy of 99%, with high precision and recall for both classes (fraudulent and non-fraudulent transactions). The confusion matrix and ROC curve show the model's effectiveness in distinguishing fraudulent transactions.

## Conclusion
The **Random Forest Classifier** is effective in detecting fraudulent transactions, though further model tuning and improvements are possible.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## License
This project is licensed under the MIT License.

