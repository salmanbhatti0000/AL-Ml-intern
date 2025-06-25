 Task 1 – Exploring and Visualizing a Simple Dataset (Iris)

🔍 Objective
Explore the classic Iris dataset to understand feature distributions and relationships using Python-based visualization and data analysis.

 📂 Dataset
- **Source**: Seaborn's built-in Iris dataset
- **Records**: 150 rows, 5 features
- **Target Variable**: Species

📊 Steps Performed
- Loaded and inspected dataset (shape, summary statistics, missing values)
- Visualized data using:
  - **Scatter plot** (Petal length vs. width by species)
  - **Histograms** for distribution
  - **Boxplots** for outlier detection

 🛠 Tools & Libraries
- pandas
- matplotlib
- seaborn
  
✅ Outcome
Successfully visualized how sepal and petal dimensions vary across species. Setosa class had the most distinct feature distribution, while versicolor and virginica had slight overlap.


# Task 3 – Heart Disease Prediction

🔍 Objective
Build a machine learning model to predict whether a person is at risk of heart disease based on their health metrics.

📂 Dataset
- **Source**: UCI Heart Disease Dataset (merged CSV, 920 rows)
- **Target Variable**: Converted `num` column to binary `target` (0: no disease, 1: disease)

⚙️ Steps Performed
- Data cleaning: removed rows with missing values, handled categorical columns
- Feature engineering: one-hot encoded categorical variables
- Model training: Logistic Regression
- Evaluation: Accuracy, Confusion Matrix, ROC-AUC, ROC curve

 🧪 Evaluation Results
- **Accuracy**: (varies by run)
- **ROC-AUC**: (varies by run)
- **Visual Output**: ROC curve

🛠 Tools & Libraries
- pandas, seaborn, matplotlib
- scikit-learn (Logistic Regression, train_test_split, ROC-AUC)

 ✅ Outcome
Achieved a balanced classification model with meaningful performance, revealing which health indicators most impact heart disease prediction.

Task 6 – House Price Prediction

 🔍 Objective
Predict house prices using property attributes such as area, number of bedrooms, bathrooms, and other amenities.

📂 Dataset
- **Source**: Local Housing Data (545 rows × 13 features)
- **Target Variable**: `price`

⚙️ Steps Performed
- One-hot encoding of categorical features (e.g. airconditioning, furnishingstatus)
- Train-test split (80/20)
- Trained two regression models:
  - Linear Regression
  - Gradient Boosting Regressor
- Evaluated using MAE, RMSE, and R² Score



 🖼 Visual Output
- Actual vs Predicted Price Scatter Plot (Gradient Boosting)

 🛠 Tools & Libraries
- pandas, seaborn, matplotlib
- scikit-learn (LinearRegression, GradientBoostingRegressor)

 ✅ Outcome
Gradient Boosting model provided improved performance and stable predictions for house price estimates.



