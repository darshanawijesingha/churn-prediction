# Customer Churn Prediction & Revenue Forecasting

A data-driven customer analytics project that identifies customer churn risk, classifies customer behavior, and forecasts future revenue using historical invoice data.

## 📌 Project Overview

This project analyzes customer purchasing history from invoice transactions to:

- Clean and preprocess sales data
- Build customer-level features
- Classify customers based on purchasing behavior
- Detect customers at risk of churn
- Forecast future customer revenue using regression models
- Visualize customer lifecycle and business performance

The notebook provides a complete end-to-end workflow from raw invoice data to actionable business insights.

---

## 🚀 Features

- Data cleaning and preprocessing
- Customer filtering
- Date transformation
- Monthly customer aggregation
- Customer segmentation
- Churn detection logic
- Revenue forecasting
- Trend visualization
- Business insight generation

---

## 📂 Dataset

Input dataset:

- `invoice.xlsx`
- Sheet: `Sheet2`

Typical columns include:

- Account Code
- Account Name
- Invoice Date
- Sales Amount
- Transaction Date

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Workflow

### 1. Data Loading

- Load invoice data from Excel
- Read required worksheet

### 2. Data Cleaning

- Remove unwanted customer accounts
- Exclude specific companies
- Handle missing values
- Convert dates into datetime format

### 3. Feature Engineering

Create customer-level metrics such as:

- Purchase frequency
- Monthly sales
- Revenue trends
- Customer lifetime value indicators

### 4. Customer Classification

Customers are categorized based on purchasing behavior to identify:

- Active customers
- Declining customers
- Churn-risk customers
- Inactive customers

### 5. Revenue Forecasting

The notebook applies regression techniques including:

- Linear Regression
- Polynomial Regression
- Ridge Regression

Evaluation metrics include:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Time Series Cross Validation

### 6. Visualization

Visual outputs include:

- Revenue trends
- Customer lifecycle charts
- Forecast plots
- Business performance dashboards

---

## 📈 Business Value

This project helps businesses:

- Identify customers likely to churn
- Prioritize customer retention efforts
- Forecast future revenue
- Monitor customer health
- Support sales and marketing decisions

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/customer-churn-analysis.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

3. Place the dataset

```
invoice.xlsx
```

inside the project folder.

4. Open and run

```
CHURN CUSTOMERSfinallogic.ipynb
```

---

## 📁 Project Structure

```
├── CHURN CUSTOMERSfinallogic.ipynb
├── invoice.xlsx
├── README.md
└── requirements.txt
```

---

## 📌 Future Improvements

- Machine Learning-based churn prediction
- Interactive Power BI dashboard
- Streamlit web application
- Automated monthly reporting
- Customer Lifetime Value (CLV) modeling

---

## 📄 License

This project is intended for educational and business analytics purposes.

---

## 👨‍💻 Author

Developed as a customer analytics and revenue forecasting project using Python and Scikit-learn.
