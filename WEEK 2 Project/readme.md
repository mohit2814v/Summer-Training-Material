# 🏡 California Housing Price Prediction using Linear Regression

## 📌 Project Overview

This project focuses on predicting the **median house value** of California districts using the **California Housing Dataset** and a **Linear Regression** model. It demonstrates the complete machine learning workflow, from data loading and preprocessing to model training, evaluation, and interpretation.

The project is designed to provide a practical understanding of regression algorithms and how machine learning can be used to solve real-world price prediction problems.

---

# 🎯 Objective

The objective of this project is to develop a **Linear Regression** model that predicts the median house value of California districts using demographic, geographic, and housing-related features from the California Housing dataset. The project aims to demonstrate the complete machine learning workflow, including data exploration, preprocessing, model training, evaluation, and interpretation of results.

---

# 📂 Dataset

The project uses the **California Housing Dataset** available through **Scikit-learn**.

The dataset contains:

- **20,640 observations**
- **8 numerical input features**
- **1 target variable**

### Features

| Feature | Description |
|----------|-------------|
| MedInc | Median income in the district |
| HouseAge | Median age of houses |
| AveRooms | Average number of rooms |
| AveBedrms | Average number of bedrooms |
| Population | District population |
| AveOccup | Average occupants per household |
| Latitude | Geographic latitude |
| Longitude | Geographic longitude |

### Target Variable

**MedHouseVal**

Median house value for each district (measured in hundreds of thousands of dollars).

---

# 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

# 📁 Project Structure

```
California-Housing-Price-Prediction/

│── housing_prediction.py
│── README.md
│── predictions.csv
│── output.png
│── requirements.txt
```

---

# ⚙️ Machine Learning Workflow

The project follows the standard machine learning pipeline:

1. Load the California Housing dataset
2. Explore the dataset
3. Check for missing values
4. Separate features and target
5. Split data into training and testing sets
6. Train a Linear Regression model
7. Predict house prices
8. Evaluate model performance
9. Interpret the results
10. Visualize predictions

---

# 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset shape
- Data types
- Summary statistics
- Missing value analysis
- Feature distributions
- Correlation analysis

These steps help understand the characteristics of the dataset before training the model.

---

# 🤖 Model Used

**Linear Regression**

Linear Regression predicts the target variable by learning a linear relationship between the input features and house prices.

---

# 📈 Evaluation Metrics

The model is evaluated using:

### Mean Absolute Error (MAE)

Measures the average prediction error.

Lower values indicate better performance.

---

### Mean Squared Error (MSE)

Measures the average squared prediction error.

Large errors receive a higher penalty.

---

### Root Mean Squared Error (RMSE)

Square root of the Mean Squared Error.

Provides prediction error in the same unit as the target variable.

---

### R² Score

Measures how well the model explains the variation in house prices.

- R² = 1 → Perfect prediction
- R² = 0 → No explanatory power

---

# 📉 Visualization

The project includes:

- Actual vs Predicted House Price Scatter Plot
- Feature Coefficient Analysis
- Correlation Heatmap (optional)

---

# 📌 Key Insights

After training the model, the following insights can be obtained:

- Median income is one of the strongest predictors of house prices.
- Geographic location (latitude and longitude) significantly influences housing values.
- Some features contribute more strongly than others to price prediction.
- The Linear Regression model provides a good baseline but may struggle with highly expensive properties because it assumes linear relationships.
- Model evaluation metrics help assess prediction accuracy and generalization.

---

# 🚀 How to Run the Project

## 1. Clone the repository

```bash
git clone <repository_link>
```

---

## 2. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 3. Run the project

```bash
python housing_prediction.py
```

---

# 📦 Requirements

```
numpy
pandas
matplotlib
scikit-learn
```

---

# 📄 Output

The project generates:

- Predicted house prices
- Model evaluation metrics
- Scatter plot of actual vs predicted prices
- CSV file containing predictions

---

# 📚 Learning Outcomes

By completing this project, you will learn:

- Data preprocessing techniques
- Exploratory Data Analysis (EDA)
- Train-test splitting
- Supervised learning using Linear Regression
- Regression evaluation metrics
- Model interpretation
- Visualization of machine learning results

---

# 🔮 Future Improvements

Possible enhancements include:

- Feature scaling using StandardScaler
- Cross-validation
- Hyperparameter tuning
- Polynomial Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Models
- XGBoost for improved prediction accuracy

---

# 👨‍💻 Author

**Mohit Gupta**

B.Tech Student | Data Analytics & Machine Learning Enthusiast
