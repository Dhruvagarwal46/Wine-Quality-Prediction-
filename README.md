# Wine Quality Prediction – Machine Learning

## Introduction
In this project, we aim to predict the quality of wine based on various features using machine learning techniques. By leveraging a dataset containing fundamental features affecting wine quality, we'll explore different machine learning models to achieve accurate predictions. This README provides an overview of the project, including dataset analysis, data preprocessing, exploratory data analysis (EDA), model development, and evaluation.

## Dataset
The dataset used in this project comprises features such as acidity, alcohol content, pH level, and quality ratings for various types of wine. It is obtained from a publicly available source on the internet. The dataset contains both continuous and categorical features.

## Libraries Used
- Pandas: For data manipulation and analysis.
- Numpy: For numerical computations.
- Matplotlib and Seaborn: For data visualization.
- Scikit-learn: For model development and evaluation.
- XGBoost: For implementing the XGBoost classifier algorithm.

## Data Preprocessing
- Handling missing values: Missing values in the dataset were imputed with the mean value of the respective columns.
- Data type conversion: Object data types were replaced with numerical values for model compatibility.
- Feature selection: Highly correlated features such as 'total sulfur dioxide' were removed to improve model performance.
- Normalization: Data normalization was performed to scale the features within a certain range.

## Exploratory Data Analysis (EDA)
EDA was conducted to understand the distribution of features and relationships between variables. Histograms, count plots, and heatmaps were utilized to visualize the data and identify patterns.

## Model Development
- Target variable creation: A binary target variable ('best quality') was created based on the wine quality ratings.
- Model selection: Three machine learning models, namely Logistic Regression, XGBoost Classifier, and Support Vector Classifier (SVC), were trained on the dataset.
- Model training and evaluation: The models were trained on the training data and evaluated using both training and validation data. The performance metrics such as accuracy and confusion matrix were analyzed to select the best-performing model.

## Model Evaluation
- Logistic Regression and SVC classifiers exhibited better performance on the validation data compared to XGBoost Classifier.
- Confusion matrix and classification report were generated for the best-performing model (Logistic Regression) to assess its performance on the validation data.

## Conclusion
The project successfully predicts the quality of wine using machine learning techniques. By analyzing various features and leveraging different classification algorithms, we can accurately classify wine quality. Further optimizations and fine-tuning of models can be explored to enhance prediction accuracy and applicability in real-world scenarios.

Feel free to explore the provided code and dataset for detailed insights into the project. If you have any questions or suggestions, please don't hesitate to reach out. Cheers! 🍷
