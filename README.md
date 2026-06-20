Housing Price Prediction

A data science internship project that explores, cleans, and models the Kaggle Housing Prices Dataset to predict house prices using Linear Regression and Random Forest Regressor.

📁 Project Structure

.
├── analysis.ipynb          # Complete notebook with all 5 tasks
├── Housing.csv              # Dataset used (545 rows, 13 columns)
├── summary.pdf               # 1-page written summary of findings
└── charts/
    ├── chart1_price_distribution.png
    ├── chart2_correlation_heatmap.png
    └── chart3_actual_vs_predicted.png

📊 Dataset


Source: Kaggle — Housing Prices Dataset
Rows: 545
Columns: 13
Target variable: price
Features: area, bedrooms, bathrooms, stories, mainroad, guestroom, basement, hotwaterheating, airconditioning, parking, prefarea, furnishingstatus


🔧 Tasks Covered


Data Loading & Exploration — Load CSV, inspect shape, identify target/features, check missing values
Data Cleaning — Handle missing values, remove duplicates, one-hot encode categorical columns
Model Building — 80/20 train-test split, train Linear Regression and Random Forest, evaluate with MAE, RMSE, R²
Visualization — Price distribution histogram, correlation heatmap, actual vs predicted scatter plot
Insights & Summary — Key findings, model accuracy in plain terms, and a business recommendation


📈 Results

MetricLinear RegressionRandom ForestMAE₹970,043₹1,022,560RMSE₹1,324,507₹1,401,497R²0.650.61

Key insight: Linear Regression slightly outperformed Random Forest on this dataset — a reminder that more complex models don't always win, especially on smaller datasets (545 rows) where Random Forest can overfit.

Top features influencing price: area, bathrooms, airconditioning

🛠️ Tech Stack


Python, Pandas, NumPy
scikit-learn (LinearRegression, RandomForestRegressor)
Matplotlib, Seaborn


▶️ How to Run

bashpip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook analysis.ipynb

✍️ Author

Shaik Mustaq
