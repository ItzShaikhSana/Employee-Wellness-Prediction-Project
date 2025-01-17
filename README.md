# Employee-Wellness-Prediction-Project
This project aims to predict employee wellness using machine learning models.A drastic thing happened and XYZ Technical Solutions have lost one of their important employees. The company is now very concerned about the health of their employees and would want you to find that set of employees who are in need or may be in need of treatment, taking into account multiple attributes that are already stored in the database.The goal is to help the organization to better understand the factors that contribute to employee health and wellbeing. 

**Dataset Information**

The dataset contains the following columns:

- **Timestamp**: Time of data collection
- **Age**: Age of the employee
- **Gender**: Gender of the employee
- **Country**: Country of residence
- **State**: If you live in the United States, which state or territory do you live in?
- **Self-Employed**: Are you self-employed?
- **Family History**: Do you have a family history of mental illness?
- **Treatment**: Does he or she really need treatment?
- **Work Interfere**: If you have a mental health condition, do you feel that it interferes with your work?
- **No Employees**: How many employees does your company or organization have?
- **Remote Work**: Do you work remotely (outside of an office) at least 50% of the time?
- **Tech Company**: Is your employer primarily a tech company/organization?
- **Benefits**: Does your employer provide mental health benefits?
- **Care Options**: Do you know the options for mental health care your employer provides?
- **Wellness Program**: Has your employer ever discussed mental health as part of an employee wellness program?
- **Seek Help**: Does your employer provide resources to learn more about mental health issues and how to seek help?
- **Anonymity**: Is your anonymity protected if you choose to take advantage of mental health or substance abuse treatment resources?
- **Leave**: How easy is it for you to take medical leave for a mental health condition?
- **Mental Health Consequence**: Do you think that discussing a mental health issue with your employer would have negative consequences?
- **Physical Health Consequence**: Do you think that discussing a physical health issue with your employer would have negative consequences?
- **Coworkers**: Would you be willing to discuss a mental health issue with your coworkers?
- **Supervisor**: Would you be willing to discuss a mental health issue with your direct supervisor(s)?
- **Mental Health Interview**: Would you bring up a mental health issue with a potential employer in an interview?
- **Physical Health Interview**: Would you bring up a physical health issue with a potential employer in an interview?
- **Mental vs Physical**: Do you feel that your employer takes mental health as seriously as physical health?
- **Observed Consequence**: Have you heard of or observed negative consequences for coworkers with mental health conditions in your workplace?
- **Comments**: Any additional notes or comments. itional notes or comments.

**Objective**

The objective is to predict if the employee needs treatment, from the given features of the Test data.

### **Project Workflow**

**Data Preprocessing:**

- Checked for missing values and visualized the patterns in data.

- Handled missing values using appropriate imputation techniques.

- Encoded categorical variables for model compatibility.

- Scaled numerical features for models requiring normalization.

**Model Implementation:**

- Applied Logistic Regression, Gradient Boosting, Decision Tree, Support Vector Classifier (SVC), and K-Nearest Neighbors (KNN).

- Evaluated each model using metrics like accuracy, precision, recall, and F1-score.

**Hyperparameter Tuning:**

- Performed Grid Search CV on Gradient Boosting to optimize performance.

**Model Comparison:**

Compared all models based on performance metrics to determine the most suitable one for this dataset.

-------------------------------------------------------------------------------------------------------------

**Key Insights**

**Logistic Regression:**

Achieved the highest accuracy (0.82), indicating strong linear relationships in the data.

Simple and interpretable, making it a reliable baseline model.

**Gradient Boosting:**

Accuracy improved to 0.82 after hyperparameter tuning, matching Logistic Regression.

Captures non-linear patterns but didn’t significantly outperform simpler models due to data simplicity.

**Decision Tree Classifier:**

Accuracy of 0.73 suggests overfitting and less suitability for this dataset.

**Support Vector Classifier (SVC):**

Accuracy of 0.76, with potential for improvement through kernel tuning and preprocessing.

**K-Nearest Neighbors (KNN):**

Accuracy of 0.74, dependent on optimal k selection and scaling.

**Technologies Used** 

**Programming Language:** 

Python

**Libraries:**

- Data Manipulation and Analysis: Pandas, NumPy

- Data Visualization: Matplotlib, Seaborn

- Machine Learning Models: Scikit-learn

- Hyperparameter Tuning: GridSearchCV (Scikit-learn)

**Future Work**

- Feature Engineering: Explore advanced feature extraction techniques to derive more meaningful insights from the dataset.

- Ensemble Learning: Combine multiple models like Random Forest and Gradient Boosting for better predictive performance.

- Cross-Dataset Validation: Test the model on similar datasets to assess generalizability.


**Contributing**

Contributions are welcome! Please fork the repository and submit a pull request.
