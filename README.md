# 📊 Spread Locator: Statistical Distribution Analysis Model

---

## 📌 Project Overview

The **Spread Locator: Statistical Distribution Analysis Model** is a data analysis project designed to identify, model, and interpret statistical distributions in customer transaction data from an e-commerce platform.

The goal of this project is to apply probability distributions, statistical transformations, and visualization techniques to understand transaction patterns, detect anomalies, and derive meaningful business insights.

This project uses Python and key data science libraries such as NumPy, Pandas, SciPy, Statsmodels, Matplotlib, and Seaborn.

---

## 🎯 Objectives

- Understand statistical distributions in real-world data
- Fit data to Bernoulli, Binomial, Poisson, Log-Normal, and Power Law distributions
- Analyze transaction behavior using probability theory
- Detect skewness and normalize data using Box-Cox transformation
- Identify outliers using Z-score analysis
- Visualize data using Q-Q plots, PDF, and CDF
- Determine the best-fitting statistical distribution

---

## 📂 Dataset Description

The dataset contains customer transaction information with the following fields:

| Field Name | Description |
|---|---|
| `transaction_id` | Unique identifier for each transaction |
| `customer_id` | Unique identifier for each customer |
| `transaction_amount` | Amount of transaction (₹) |
| `transaction_date` | Date of transaction |
| `transaction_count` | Number of transactions per week |
| `region` | Customer region |
| `transaction_status` | Transaction success or failure |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook

**Python Libraries:**

- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Seaborn

---

## 📊 Statistical Methods Applied

### 1. Bernoulli Distribution

Used to model transaction success or failure.

$$P(X = x) = p^x (1 - p)^{(1 - x)}$$

### 2. Binomial Distribution

Used to model number of successful transactions over multiple trials.

$$\text{Mean} = n \times p$$

### 3. Poisson Distribution

Used to model number of transactions per time period.

$$P(x) = \frac{e^{-\lambda} \times \lambda^x}{x!}$$

### 4. Log-Normal Distribution

Used to model transaction amounts (financial data typically follows log-normal distribution).

### 5. Power Law Distribution

Used to analyze heavy-tailed financial transaction behavior.

$$P(x) \propto x^{-\alpha}$$

### 6. Q-Q Plot

Used to check normality of transaction amount data.

- If points lie on straight line → data is **normally distributed**
- If points deviate → data is **skewed**

### 7. Box-Cox Transformation

Used to stabilize variance and normalize skewed data.

$$y(\lambda) = \frac{x^{\lambda} - 1}{\lambda}$$

### 8. Z-Score Analysis

Used to detect outliers and extreme transaction values.

$$Z = \frac{X - \mu}{\sigma}$$

### 9. PDF and CDF Visualization

Used to understand probability density and cumulative probability.

$$\text{CDF} = \int \text{PDF} \, dx$$

---

## 📈 Key Insights

- Transaction status follows **Bernoulli distribution**
- Transaction counts follow **Poisson distribution**
- Transaction amounts follow **Log-Normal distribution**
- Financial data shows **right-skewed heavy-tail** behavior
- **Box-Cox transformation** improves data normality
- High-value transactions can be detected using **Z-score**

---

## 📊 Visualizations Included

- Histogram plots
- Q-Q Plot
- Box-Cox transformation plots
- PDF and CDF plots
- Distribution fitting visualizations

---

## 📁 Project Structure
```
Spread-Locator-Statistical-Distribution-Analysis/
│
├── spread_locator_dataset.xlsx
├── spread_locator_analysis.ipynb
├── README.md
└── screenshots/
```

---

## ▶️ How to Run the Project

### Step 1: Clone Repository
```bash
git clone https://github.com/yourusername/spread-locator-statistical-analysis.git
```

### Step 2: Install Required Libraries
```bash
pip install pandas numpy scipy matplotlib seaborn statsmodels openpyxl
```

### Step 3: Run Jupyter Notebook
```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## 📊 Applications

This project can be used for:

- Financial data analysis
- Fraud detection systems
- Customer behavior analysis
- Risk modeling
- E-commerce analytics

---

## 👨‍💻 Author

**Arnob Maity**

Aspiring Data Scientist | Python Developer | AI/ML Enthusiast

---

## 📜 License

This project is for educational and academic purposes.

---

## ⭐ Acknowledgement

This project was developed as part of a statistical data analysis learning program to understand real-world application of probability distributions.

## Project Explanation Video
(

)
