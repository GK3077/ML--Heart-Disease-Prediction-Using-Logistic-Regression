# Heart Disease Prediction Using Logistic Regression
This project aims to predict the risk of heart disease using logistic regression based on various patient attributes. It utilizes a dataset from the Framingham Heart Study, focusing on factors such as age, gender, smoking habits, cholesterol levels, blood pressure, and glucose levels to predict the likelihood of developing coronary heart disease (CHD) within ten years.

### Overview
The project involves several key steps:

1. **Importing Necessary Libraries**: Initial setup involves importing essential Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn for data manipulation, visualization, and logistic regression modeling.

2. **Data Preparation**:  This section involves loading the dataset, handling missing values, and preparing the data for analysis.

3. **Exploratory Data Analysis (EDA)**: An overview of the dataset is provided through exploratory data analysis, including visualizations to understand the distribution of the target variable (CHD) and other relevant features.

4. **Model Development**: Logistic regression is utilized to build the predictive model. The dataset is split into training and testing sets, and the logistic regression model is trained on the training set.

5. **Model Evaluation**: The trained model is evaluated using various metrics such as accuracy, confusion matrix, precision, recall, and F1-score to assess its performance in predicting heart disease risk.

### Usage
To use this project:

1. Ensure Python and necessary libraries are installed.
2. Download the dataset (Framingham Heart Study dataset).
3. Clone this repository.
4. Execute the provided Python script.

### Results
The logistic regression model achieved an accuracy of approximately 84.9% on the test set. However, the model's performance varied for different classes, with higher precision and recall for the 'not affected' class compared to the 'affected' class. The confusion matrix and classification report provide detailed insights into the model's performance.

### Future Work
Future enhancements to this project could include:

- Feature engineering to improve model performance.
- Trying different machine learning algorithms for comparison.
- Hyperparameter tuning to optimize model performance further.
- Deployment of the model for real-time predictions.

### Contributors
Gayathri Krishnan

### License
This project is licensed under the MIT License.
