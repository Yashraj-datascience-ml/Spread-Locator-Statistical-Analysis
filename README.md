# 📊 Spread Locator – Statistical Distribution Analysis

<p align="center">
  <b>An Advanced Statistical Analysis Project Using Python</b>
  <br>
  Exploring E-Commerce Transaction Behavior Through Probability Distributions, Statistical Modeling and Data Visualization.
</p>

<p align="center">
  ![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
  ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
  ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
  ![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
  ![SciPy](https://img.shields.io/badge/SciPy-Statistical%20Analysis-8CAAE6)
  ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
  ![Status](https://img.shields.io/badge/Project-Completed-success)
</p>

---

## 📌 1. Project Overview

**Spread Locator** is a Python-based statistical analysis project developed to explore and understand customer transaction behavior in an e-commerce environment.

The project applies probability distributions, descriptive statistics, statistical transformations, normality testing, probability calculations and mathematical modeling to analyze transaction data.

Using Python and Jupyter Notebook, the project investigates transaction patterns, distribution characteristics, probability behavior and statistical relationships.

The main objective is to identify suitable statistical models for transaction amounts and extract meaningful insights that can support data-driven business decisions.

## 🎯 2. Project Objectives

- Analyze transaction data using descriptive statistics.
- Understand transaction success and failure probabilities.
- Apply discrete probability distributions to transaction counts.
- Fit continuous statistical distributions to transaction amounts.
- Examine normality using Q-Q plots and statistical tests.
- Apply Box-Cox transformation to study distribution characteristics.
- Calculate Z-scores and transaction probabilities.
- Analyze Probability Density Functions (PDF) and Cumulative Distribution Functions (CDF).
- Compare statistical models using AIC, Log-Likelihood and KS statistics.
- Identify the relatively best-fitting distribution.

## 📂 3. Dataset Description

The project uses an e-commerce transaction dataset containing **220 transaction records**.

### Dataset Features

| Column | Description |
|---|---|
| transaction_id | Unique transaction identifier |
| customer_id | Customer identifier |
| transaction_amount | Transaction amount |
| transaction_date | Date of transaction |
| transaction_count | Transaction count |
| region | Customer region |
| transaction_status | Success or Failure status |

### Dataset Summary

| Metric | Result |
|---|---:|
| Total Records | 220 |
| Missing Values | 0 |
| Successful Transactions | 98 |
| Failed Transactions | 122 |
| Success Rate | 44.55% |
| Failure Rate | 55.45% |

## 🛠️ 4. Technologies & Libraries

| Technology | Application |
|---|---|
| Python | Programming and statistical analysis |
| Jupyter Notebook | Interactive development |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| SciPy | Statistical analysis and probability distributions |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |

## 📈 5. Project Methodology

The project follows a structured statistical analysis workflow.

### Task 1 – Bernoulli and Binomial Distributions

- Binary encoding of transaction status.
- Calculation of success and failure probabilities.
- Bernoulli PMF.
- Binomial modeling of weekly transaction counts.

### Task 2 – Poisson Distribution

- Daily transaction count analysis.
- Estimation of Lambda (λ).
- Poisson probability calculations.
- Actual versus expected frequency comparison.

### Task 3 – Log-Normal and Power Law Distributions

- Log-Normal distribution fitting.
- Pareto-based Power Law distribution fitting.
- Probability density visualization.
- Comparative distribution analysis.

### Task 4 – Q-Q Plot and Normality Testing

- Normal Q-Q plot generation.
- Shapiro-Wilk normality test.
- Logarithmic transformation.
- Comparison of original and transformed data.

### Task 5 – Box-Cox Transformation

- Optimal Lambda parameter estimation.
- Transformation of positive transaction amounts.
- Skewness and kurtosis comparison.
- Normality assessment after transformation.

### Task 6 – Z-Score and Probability Analysis

- Calculation of transaction Z-scores.
- Probability estimation.
- Analysis of transactions exceeding ₹5,000.
- Standardized statistical analysis.

### Task 7 – PDF and CDF Analysis

- Probability Density Function estimation using KDE.
- Empirical Cumulative Distribution Function calculation.
- PDF and CDF visualization.
- Cumulative probability analysis.

### Task 8 – Best-Fit Distribution Analysis

- Normal distribution fitting.
- Log-Normal distribution fitting.
- Power Law (Pareto) distribution fitting.
- Log-Likelihood calculation.
- Akaike Information Criterion (AIC) comparison.
- Kolmogorov-Smirnov (KS) testing.
- Comparative model evaluation.

## 📊 6. Key Statistical Findings

### Transaction Status Analysis

| Status | Count | Percentage |
|---|---:|---:|
| Success | 98 | 44.55% |
| Failure | 122 | 55.45% |
| Total | 220 | 100% |

### Transaction Threshold Analysis

The project analyzed transaction amounts using a threshold of ₹5,000.

| Measurement | Result |
|---|---:|
| Total Transactions | 220 |
| Transactions ≤ ₹5,000 | 195 |
| Transactions > ₹5,000 | 25 |
| CDF P(X ≤ 5000) | 0.8864 |
| P(X > 5000) | 0.1136 |
| Percentage ≤ ₹5,000 | 88.64% |

**Key Insight:** Approximately 88.64% of observed transactions were ₹5,000 or below, while 11.36% exceeded ₹5,000.

### Best-Fit Distribution Comparison

The fitted statistical models were compared using Akaike Information Criterion (AIC).

| Distribution | AIC | Rank |
|---|---:|---:|
| Log-Normal | 3821.03 | 1 |
| Normal | 3968.57 | 2 |
| Power Law (Pareto) | 4083.34 | 3 |

**Result:** The Log-Normal distribution achieved the lowest AIC among the three fitted models and was identified as the relatively preferred model.

*Note: AIC provides relative model comparison. Additional goodness-of-fit validation and tail analysis are required before making a definitive distributional conclusion.*

## 🖼️ 7. Statistical Visualization Gallery

All visualizations below were captured from the Jupyter Notebook analysis and uploaded as separate PNG files.

### 7.1 Transaction Analysis

**Transaction Amount Distribution**

![Transaction Amount Distribution](./Distribution%20of%20Transaction%20Amounts.png)

**Transaction Amount Boxplot**

![Transaction Boxplot](./Boxplot%20of%20Transaction%20Amounts.png)

### 7.2 Discrete Probability Distributions

**Bernoulli Distribution**

![Bernoulli Distribution](./Bernoulli%20Distribution%20of%20Transaction%20Status.png)

**Binomial Distribution**

![Binomial Distribution](./Binomial%20Distribution%20of%20Weekly%20Transaction%20Counts.png)

**Poisson Distribution**

![Poisson Distribution](./Poisson%20Distribution%20of%20Daily%20Transactions.png)

**Actual vs Expected Poisson Distribution**

![Actual vs Expected Poisson](./Actual%20vs%20Expected%20Poisson%20Distribution.png)

### 7.3 Continuous Distribution Fitting

**Log-Normal Distribution**

![Log Normal Fit](./Log-Normal%20Distribution%20Fit.png)

**Power Law Distribution**

![Power Law Fit](./Power%20Law%20Distribution%20Fit.png)

**Distribution Comparison**

![Distribution Comparison](./Comparison%20of%20Statistical%20Distributions.png)

### 7.4 Normality and Transformation Analysis

**Original Q-Q Plot**

![Original QQ Plot](./Q-Q%20Plot%20of%20Transaction%20Amounts.png)

**Log Transformation Q-Q Plot**

![Log Transformation](./Q-Q%20Plot%20after%20Log%20Transformation.png)

**Box-Cox Transformation Comparison**

![Box Cox Transformation](./Before%20and%20After%20Box-Cox%20Transformation.png)

**Box-Cox Q-Q Plot**

![Box Cox QQ Plot](./Q-Q%20Plot%20After%20Box-Cox%20Transformation.png)

### 7.5 Probability Analysis

**Probability of Transactions Above ₹5,000**

![Transaction Probability](./Probability%20of%20Transactions%20Above%20%EF%B9%965000.png)

**Probability Density Function**

![PDF](./Probability%20Density%20Function%20of%20Transaction%20Amounts.png)

**Cumulative Distribution Function**

![CDF](./Cumulative%20Distribution%20Function%20of%20Transaction%20Amounts.png)

## 📁 8. Repository Structure

```text
Spread-Locator-Statistical-Analysis/
│
├── Spread_Locator_Analysis.ipynb
│
├── spread_locator_dataset.xlsx
│
├── Actual vs Expected Poisson Distribution.png
├── Before and After Box-Cox Transformation.png
├── Bernoulli Distribution of Transaction Status.png
├── Binomial Distribution of Weekly Transaction Counts.png
├── Boxplot of Transaction Amounts.png
├── Comparison of Statistical Distributions.png
├── Cumulative Distribution Function of Transaction Amounts.png
├── Distribution of Transaction Amounts.png
├── Log-Normal Distribution Fit.png
├── Poisson Distribution of Daily Transactions.png
├── Power Law Distribution Fit.png
├── Probability Density Function of Transaction Amounts.png
├── Probability of Transactions Above ₹5000.png
├── Q-Q Plot After Box-Cox Transformation.png
├── Q-Q Plot after Log Transformation.png
├── Q-Q Plot of Transaction Amounts.png
│
├── README.md
├── LICENSE
└── .gitignore
```

## ⚙️ 9. Installation and Setup

### Step 1 – Clone the Repository

```bash
git clone https://github.com/Yashraj-datascience-ml/Spread-Locator-Statistical-Analysis.git
```

### Step 2 – Navigate to Project Directory

```bash
cd Spread-Locator-Statistical-Analysis
```

### Step 3 – Install Required Libraries

```bash
pip install numpy pandas scipy matplotlib seaborn openpyxl jupyter
```

### Step 4 – Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5 – Run the Project

Open `Spread_Locator_Analysis.ipynb` and execute the notebook cells sequentially.

The Excel dataset must be available in the expected project location for successful execution.

## 💡 10. Business Insights

The analysis provides the following observations:

1. The observed transaction success rate was approximately 44.55%.
2. Most observed transactions were within the ₹5,000 threshold.
3. Probability distributions help describe transaction frequency and amount patterns.
4. Statistical transformations help investigate the effect of skewness.
5. The Log-Normal model achieved the lowest AIC among the three fitted models.
6. Statistical modeling can support better understanding of customer transaction behavior.

These findings describe the analyzed dataset and should not automatically be generalized to all e-commerce businesses.

## 🚀 11. Future Enhancements

Potential improvements include:

- Advanced Power Law tail estimation.
- Bootstrap-based goodness-of-fit validation.
- Interactive dashboards using Streamlit or Power BI.
- Regional transaction behavior analysis.
- Customer segmentation using statistical techniques.
- Transaction trend forecasting using Machine Learning.
- Automated statistical reporting.

## 👨‍💻 12. Author

**Yashraj Datascience ML**

GitHub Profile:  
https://github.com/Yashraj-datascience-ml

Project Repository:  
https://github.com/Yashraj-datascience-ml/Spread-Locator-Statistical-Analysis

## 📜 13. License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

---

<p align="center">
  <b>Spread Locator – Turning Transaction Data into Statistical Insights.</b>
  <br>
  <i>Built with Python, Statistics and Data Analysis.</i>
</p>
