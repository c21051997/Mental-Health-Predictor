# Predictive Mental Health Analysis using BRFSS Data

This project presents an end-to-end data science workflow designed to predict mental health status using data from the US Behavioral Risk Factor Surveillance System (BRFSS) [`21051997-part-2.ipynb`]. The primary objective is to build and evaluate a machine learning model that classifies an individual's mental health into one of three categories—**Good**, **Okay**, or **Poor**—based on a range of demographic, lifestyle, and behavioral factors [`21051997-part-2.ipynb`].

The project demonstrates a comprehensive process, from initial data ingestion and database management to feature engineering, exploratory data analysis, model training, and in-depth performance evaluation.

## Key Features & Workflow

- **Database Management**  
  Designed and implemented a relational database schema in MySQL to structure, store, and query the dataset efficiently [`21051997-part-11.ipynb`].

- **Data Analysis & Visualization**  
  Performed Exploratory Data Analysis (EDA) to uncover the relationships between mental health and key factors like sleep duration, income level, and education. Visualizations were created using Matplotlib to present these findings clearly [`21051997-part-2.ipynb`].

- **Feature Engineering**  
  Created new composite features, such as `total_alcohol_consumption`, by combining existing variables to provide more meaningful input for the machine learning models [`21051997-part-2.ipynb`].

- **Data Preprocessing**  
  Cleaned the dataset by systematically handling special codes and missing values based on the data codebook. Categorical variables were converted into a numerical format using one-hot encoding with Pandas [`21051997-part-2.ipynb`].

- **Model Training & Evaluation**  
  Trained and evaluated four distinct classification models to compare their effectiveness. Performance was measured using accuracy, precision, recall, and F1-score, with careful consideration for the class imbalance present in the dataset [`21051997-part-2.ipynb`].

## Models Implemented

The following models were trained and evaluated using Scikit-learn:

- Logistic Regression [`21051997-part-2.ipynb`]
- Decision Tree Classifier [`21051997-part-2.ipynb`]
- MLP Classifier (Multi-layer Perceptron) [`21051997-part-2.ipynb`]
- Random Forest Classifier [`21051997-part-2.ipynb`]

## Technologies Used

- **Languages**: Python, SQL  
- **Data Manipulation & Analysis**: Pandas, NumPy  
- **Data Visualization**: Matplotlib  
- **Machine Learning**: Scikit-learn  
- **Database**: MySQL  
- **Environment**: Jupyter Notebook
