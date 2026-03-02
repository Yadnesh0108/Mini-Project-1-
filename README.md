# Mini-Project-1-
# 🎓 Student Math Score Predictor

An end-to-end Machine Learning project that predicts a student's math score based on their demographic background, preparation history, and scores in other subjects. 

This project demonstrates data preprocessing, categorical encoding, feature scaling, and the implementation of a **Multivariable Polynomial Regression** model to capture non-linear relationships between student features and their academic performance.

## 🚀 Features
* **Data Preprocessing:** Handles missing values and uses `LabelEncoder` for categorical variables.
* **Feature Engineering:** Applies `StandardScaler` and `PolynomialFeatures` (degree 2) to improve model accuracy.
* **Predictive Modeling:** Uses Scikit-Learn's `LinearRegression` on polynomial features.
* **Custom Predictions:** Includes a command-line interface to input custom student data and get instant math score predictions.

## 📊 Model Performance
The model was trained and evaluated on an 80/20 train-test split, achieving the following results:
* **R² Score:** 0.869 (The model explains ~87% of the variance in math scores)
* **Training MSE:** 28.56
* **Testing MSE:** 31.81

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib
* **Environment:** Jupyter Notebook

## 📁 Repository Structure
```text
student-score-predictor/
│
├── data/
│   └── StudentsPerformance.csv     # Dataset
│
├── Student_Score_Prediction.ipynb  # Main Jupyter Notebook with code and analysis
├── requirements.txt                # Python dependencies
├── .gitignore                      # Ignored files
└── README.md                       # Project documentation
