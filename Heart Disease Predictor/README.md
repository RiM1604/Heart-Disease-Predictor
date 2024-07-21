## NAME: RITESAH MADHUNALA
## ROLL NO: 21CS30042

# Assignment 1 - Heart Disease Prediction using Exploratory Data Analysis and Classification
This project utilizes Python, pandas, and scikit-learn to explore a dataset named `framingham.csv`, which contains information related to heart disease risk factors and outcomes. The project involves data preprocessing, exploratory data analysis (EDA), and classification tasks.

# Dependencies/ Requirements
Before running the code, ensure the following libraries are installed:
- Python (3.7+)
- pandas
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn (imblearn)

Install these dependencies using pip:
  ```bash
  pip install pandas matplotlib seaborn scikit-learn imbalanced-learn
  ```
- All required dependencies are listed in the `requirements.txt` file.
- To install the dependencies, use the following command:
  ```bash
  pip install -r requirements.txt
  ```
Ensure the dataset file is in the same folder as the Jupyter Notebook.

# Implementation
To implement the code, follow these steps in the order they appear in the Jupyter Notebook:

- Import Data: Run the code block for importing and visualizing the dataset.

- Explore and Visualize Data: Execute the code to explore and visualize the dataset. This includes handling missing values, obtaining basic statistics of numeric columns, and creating visualizations of data distributions and correlations.

- Feature Selection by PCA: Execute the code for feature selection using Principal Component Analysis (PCA), involving dimensionality reduction to improve efficiency.

- Train and Test Split: Run the code to split the dataset into training (80%) and testing (20%) sets, which is crucial for evaluating model performance.

- Resampling: Execute the code to apply resampling techniques such as SMOTE, ADASYN, and RandomUnderSampler to address class imbalance.

- Pipeline and Measuring Accuracies: Run the code to create pipelines for different classifiers (Logistic Regression, Decision Tree, KNN, and SVM) with resampling techniques. This step includes hyperparameter tuning using GridSearchCV and measuring accuracy.

- Printing the Final Results: The final results, including accuracy scores and classification reports for each model and resampling strategy, will be printed in the Jupyter Notebook.

# Sample Output
A sample output of the code execution is provided in the `Output.pdf` file. Refer to this file to see the results of running the code.

# Code Description and Analysis
The code is thoroughly documented with comments within the Jupyter Notebook, explaining each step and its purpose. Additionally, the strengths and weaknesses of Logistic Regression, Support Vector Machines (SVM), Decision Tree, and KNN for predicting heart disease are discussed in the `report.pdf` file. The report also identifies the most suitable model based on accuracy and efficiency.

Feel free to adjust or update any part as needed!