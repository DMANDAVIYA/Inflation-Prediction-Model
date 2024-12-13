# Inflation Prediction Model

This project is a data-driven approach to predicting inflation rates using interest rate data, such as saving account and loan interest rates. The model uses historical data to analyze trends and provide predictions that can aid in understanding the relationship between interest rates and inflation.

---

## Features

- Predicts inflation rates based on bank saving and loan interest rates.
- Analyzes historical data trends to derive meaningful insights.
- Evaluates the model using statistical metrics to ensure accuracy.
- Visualizes the relationship between interest rates and inflation.

---

## Objectives

- Understand the correlation between saving account and loan interest rates with inflation trends.
- Develop a predictive model to estimate future inflation rates based on historical data.

---

## Workflow

### **1. Data Gathering**
- Historical data on:
  - Saving account interest rates.
  - Loan interest rates.
  - Inflation rates (CPI or similar indicators).

### **2. Data Preparation**
- Cleaned the dataset by handling:
  - Missing or inconsistent values.
  - Normalized data for optimal model performance.

### **3. Model Selection**
- Used **Linear Regression** to predict inflation rates based on input features.

### **4. Model Training and Testing**
- Data split into:
  - **Training Set**: 80% for building the model.
  - **Testing Set**: 20% for evaluation.

### **5. Evaluation Metrics**
- Evaluated the model's performance using:
  - Mean Absolute Error (MAE)
  - Root Mean Square Error (RMSE)
  - R-squared (R²)

### **6. Visualization**
- Plotted:
  - Predicted vs. Actual inflation rates.
  - Trends in saving and loan interest rates and their impact on inflation.

---

## Technologies Used

- **Python**:
  - For data analysis and building the predictive model.
- **Jupyter Notebook**:
  - For interactive coding and data visualization.
- **Libraries**:
  - **Pandas**: For data manipulation.
  - **NumPy**: For numerical operations.
  - **Scikit-learn**: For implementing machine learning models.
  - **Matplotlib/Seaborn**: For visualization.

---

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/inflation-prediction.git
   cd inflation-prediction

2. **Install Required Libraries**3:
pip install pandas numpy scikit-learn matplotlib seaborn

3. **Run the Jupyter Notebook**:
Open the notebook file (inflation_prediction.ipynb) and execute the cells.

4. **Input Your Data**: 
Replace the placeholder data with your own dataset in the provided CSV file.

**Example Output**
Predicted vs. Actual Inflation Rates: A graph showing the model's predictions compared to actual inflation rates.
Impact of Interest Rates: Visualizations demonstrating how changes in saving/loan interest rates correlate with inflation trends.