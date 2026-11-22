# Insurance-Cost-Prediction-RollNo.--AD3352
Insurance Cost Prediction using Python and Machine Learning. Includes data analysis, EDA, data preprocessing, feature engineering, feature selection, and Linear Regression to predict medical insurance charges.

# Insurance Cost Prediction Using Machine Learning

## 1. Project Description

The Insurance Cost Prediction project focuses on analyzing medical insurance data and predicting individual insurance charges using Machine Learning.

This project uses Python for data analysis, visualization, data preprocessing, feature engineering, feature selection, and Linear Regression.

The main goal is to identify the important factors that influence medical insurance charges and develop a Machine Learning model to predict insurance costs.

## 2. Project Objectives

- Perform Exploratory Data Analysis (EDA).
- Understand the structure and characteristics of the dataset.
- Identify missing values and duplicate records.
- Perform data cleaning and preprocessing.
- Apply Label Encoding and One-Hot Encoding.
- Perform BMI-based feature engineering.
- Apply Standard Scaling to numerical features.
- Perform feature selection using statistical techniques.
- Build a Linear Regression model.
- Evaluate model performance using Adjusted R².

## 3. Dataset Information

**Dataset Name:** Insurance Dataset

**Dataset File:** `insurance.csv`

**Initial Dataset Size:** 1,338 rows and 7 columns.

### Features Description

| Feature  | Description                                 |
| -------- | ------------------------------------------- |
| age      | Age of the individual                       |
| sex      | Gender of the individual                    |
| bmi      | Body Mass Index                             |
| children | Number of children                          |
| smoker   | Smoking status                              |
| region   | Residential region                          |
| charges  | Medical insurance charges (Target Variable) |

**Target Variable:** `charges`

## 4. Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## 5. Project Implementation

### Step 1: Exploratory Data Analysis (EDA)

- Checked dataset dimensions using `shape`.
- Viewed records using `head()`.
- Inspected dataset information using `info()`.
- Generated statistical summaries using `describe()`.
- Checked missing values using `isnull().sum()`.
- Visualized numerical and categorical features.
- Used Histograms, Count Plots, Box Plots, and Correlation Heatmap.

### Step 2: Data Cleaning and Preprocessing

- Created a copy of the original dataset.
- Removed duplicate records.
- Checked missing values and data types.
- Applied Label Encoding to gender and smoking status.
- Renamed columns for better understanding.
- Applied One-Hot Encoding to the region column.

### Step 3: Feature Engineering

- Created BMI categories:
  - Underweight
  - Normal
  - Overweight
  - Obese
- Applied One-Hot Encoding to BMI categories.
- Applied StandardScaler to age, BMI, and children features.

### Step 4: Feature Selection

Applied statistical techniques to identify relevant features:

**Pearson Correlation:**

- Analyzed relationships between numerical features and insurance charges.
- Identified smoking status as a strongly positively correlated feature.

**Chi-Square Test:**

- Analyzed categorical features.
- Used a significance level of 0.05.
- Identified relevant categorical features based on p-values.

### Step 5: Model Building

- Selected relevant features for model training.
- Separated independent variables (X) and dependent variable (y).
- Split the dataset into training and testing sets.
- Used an 80:20 train-test split.
- Applied Linear Regression.
- Trained the model using training data.
- Generated predictions using testing data.

### Step 6: Model Evaluation

- Evaluated the model using the Adjusted R² score.
- Compared model performance using the test dataset.

## 6. Key Results

- Initial records: 1,338.
- Records after duplicate removal: 1,337.
- Missing values: 0.
- Smoking status showed a strong positive correlation with insurance charges.
- Linear Regression was successfully implemented.
- Adjusted R² Score: Approximately 0.7988 (79.88%).

## 7. Project Files

```text
Insurance-Cost-Prediction/
│
├── insurance project.ipynb
├── insurance.csv
└── README.md
```

## 8. How to Run the Project

1. Download or clone the repository.
2. Install the required Python libraries.
3. Keep `insurance.csv` in the same folder as the notebook.
4. Open `insurance project.ipynb` using Jupyter Notebook.
5. Run all cells sequentially.
6. Observe the data analysis, visualizations, and model evaluation results.

## 9. Learning Outcomes

Through this project, I gained practical knowledge of:

- Python for Data Analysis.
- Exploratory Data Analysis.
- Data Cleaning and Preprocessing.
- Data Visualization.
- Feature Engineering.
- Feature Selection.
- Statistical Analysis.
- Linear Regression.
- Machine Learning Model Evaluation.

## 10. GitHub Submission Details

**GitHub Submission ID:**(https://github.com/complexiota).

**Student Repository:** Add your own public GitHub repository URL here.

**Repository Visibility:** Public

---

**Project Title:** Insurance Cost Prediction Using Machine Learning

**Project Status:** Completed
