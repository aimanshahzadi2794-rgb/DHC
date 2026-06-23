## Task 1: Iris Dataset Exploration and Visualization

### Objective

The objective of this task was to load, inspect, summarize, and visualize the Iris dataset to understand data trends, distributions, feature relationships, and possible outliers.

### Dataset Used

Iris Dataset loaded using the seaborn library.

### Tools and Libraries

* Python
* Pandas
* Matplotlib
* Seaborn

### Work Done

* Loaded the Iris dataset
* Checked dataset shape, columns, and first rows
* Used `.info()` and `.describe()` for summary statistics
* Created scatter plots, histograms, box plots, and pair plots
* Analyzed relationships between features

### Key Findings

Petal length and petal width are strong features for separating Iris species. Setosa is visually easier to distinguish compared to other species.

---

## Task 2: Stock Price Prediction

### Objective

The objective of this task was to predict the next day's closing stock price using historical stock market data.

### Dataset Used

Stock data collected from Yahoo Finance using the yfinance Python library.

### Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* yfinance
* Scikit-learn

### Models Applied

* Linear Regression
* Random Forest Regressor

### Work Done

* Downloaded historical stock data
* Used Open, High, Low, and Volume as input features
* Created Next_Close as the target variable
* Trained regression models
* Evaluated models using MAE, RMSE, and R2 Score
* Plotted actual vs predicted closing prices

### Key Findings

The models were able to follow the general trend of stock prices, but stock prediction is uncertain because market prices depend on many external factors.

---

## Task 6: House Price Prediction

### Objective

The objective of this task was to predict house prices using property-related features.

### Dataset Used

House Prices Advanced Regression Techniques dataset from Kaggle.

### Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Models Applied

* Linear Regression
* Gradient Boosting Regressor

### Work Done

* Loaded and cleaned the dataset
* Selected important numerical features
* Performed exploratory data analysis
* Trained regression models
* Evaluated using MAE, RMSE, and R2 Score
* Visualized actual vs predicted prices
* Displayed feature importance

### Key Findings

Overall quality, living area, garage capacity, and basement size were important factors affecting house prices. Gradient Boosting performed better than simple Linear Regression.

