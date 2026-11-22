# 📊 Spread Locator – Statistical Distribution Analysis

<p align="center">
  <b>An Advanced Statistical Analysis Project Using Python</b>
  <br>
  Exploring E-Commerce Transaction Behavior Through Probability Distributions, Statistical Modeling & Data Visualization.
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

**Spread Locator** is an advanced statistical analysis project designed to explore customer transaction behavior in an e-commerce environment.

The project applies probability distributions, descriptive statistics, statistical transformations, hypothesis testing, and mathematical modeling to understand the spread and characteristics of transaction data.

Using Python and Jupyter Notebook, the analysis investigates transaction patterns, probability behavior, distribution fitting, and statistical relationships.

The primary objective is to identify suitable statistical models for transaction amounts and generate meaningful insights that can support data-driven business decisions.

## 🎯 2. Project Objectives

- Analyze customer transaction data using descriptive statistics.
- Understand transaction success and failure probabilities.
- Model transaction counts using discrete probability distributions.
- Fit continuous statistical distributions to transaction amounts.
- Examine data normality using Q-Q plots and statistical tests.
- Apply Box-Cox transformation to reduce skewness.
- Calculate Z-scores and transaction probabilities.
- Analyze Probability Density Functions (PDF) and Cumulative Distribution Functions (CDF).
- Compare statistical models using AIC, Log-Likelihood, and KS statistics.
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
| transaction_count | Recorded transaction count |
| region | Customer region |
| transaction_status | Transaction outcome (Success/Fail) |

### Initial Dataset Statistics

| Metric | Value |
|---|---:|
| Total Records | 220 |
| Missing Values | 0 |
| Successful Transactions | 98 |
| Failed Transactions | 122 |
| Success Rate | 44.55% |
| Failure Rate | 55.45% |

## 🛠️ 4. Technologies & Libraries Used

| Technology | Purpose |
|---|---|
| Python | Programming and statistical analysis |
| Jupyter Notebook | Interactive development environment |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| SciPy | Probability distributions and statistical testing |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |

## 📈 5. Project Methodology

The project follows a structured statistical analysis workflow.

### Part A – Theoretical Foundation

Study of fundamental probability and statistical concepts, including probability distributions, descriptive measures, statistical transformations, and hypothesis testing.

### Part B – Practical Statistical Analysis

**Task 1: Bernoulli and Binomial Distributions**

- Binary encoding of transaction outcomes.
- Calculation of success and failure probabilities.
- Bernoulli Probability Mass Function (PMF).
- Binomial modeling of weekly transaction counts.

**Task 2: Poisson Distribution**

- Daily transaction count analysis.
- Estimation of Lambda (λ).
- Poisson probability calculations.
- Actual versus expected frequency comparison.

**Task 3: Log-Normal and Power Law Distributions**

- Fitting Log-Normal distribution.
- Fitting Pareto-based Power Law distribution.
- Probability density visualization.
- Comparative statistical analysis.

**Task 4: Q-Q Plot and Normality Testing**

- Normal Q-Q Plot generation.
- Shapiro-Wilk normality test.
- Logarithmic transformation.
- Comparison of original and transformed data.

**Task 5: Box-Cox Transformation**

- Optimal Lambda estimation.
- Transformation of positive transaction amounts.
- Comparison of original and transformed distributions.
- Skewness, kurtosis, and normality analysis.

**Task 6: Z-Score and Probability Analysis**

- Calculation of transaction Z-scores.
- Theoretical probability estimation.
- Empirical probability calculation.
- Analysis of transactions exceeding ₹5,000.

**Task 7: PDF and CDF Analysis**

- Probability Density Function estimation using KDE.
- Empirical Cumulative Distribution Function calculation.
- PDF and CDF visualization.
- Cumulative probability analysis.

**Task 8: Best-Fit Distribution Analysis**

- Normal distribution fitting.
- Log-Normal distribution fitting.
- Pareto-based Power Law fitting.
- Log-Likelihood calculation.
- Akaike Information Criterion (AIC) comparison.
- Kolmogorov-Smirnov (KS) testing.
- Comparative model evaluation.

## 📊 6. Key Statistical Findings

The following results were obtained from the analyzed dataset.

### Transaction Status Analysis

| Transaction Status | Count | Percentage |
|---|---:|---:|
| Success | 98 | 44.55% |
| Failure | 122 | 55.45% |
| Total | 220 | 100% |

### Transaction Threshold Analysis

The project investigated transactions exceeding ₹5,000.

| Measurement | Result |
|---|---:|
| Total Transactions | 220 |
| Transactions ≤ ₹5,000 | 195 |
| Transactions > ₹5,000 | 25 |
| Cumulative Probability | 0.8864 |
| Probability Above ₹5,000 | 0.1136 |

**Key Insight:** Approximately 88.64% of the observed transactions were ₹5,000 or below, while 11.36% exceeded ₹5,000.

### Distribution Model Comparison

The fitted models were compared using Akaike Information Criterion (AIC).

| Distribution | AIC | Rank |
|---|---:|---:|
| Log-Normal | 3821.03 | 1 |
| Normal | 3968.57 | 2 |
| Power Law (Pareto) | 4083.34 | 3 |

**Finding:** The Log-Normal distribution achieved the lowest AIC among the three fitted models, making it the relatively preferred model for this dataset under the specified fitting approach.

*Note: AIC provides a relative model comparison, not proof of the true underlying distribution. Further goodness-of-fit and tail analysis may be required.*

## 📉 7. Data Visualizations

The project includes multiple statistical visualizations:

- Transaction Amount Histogram
- Transaction Amount Boxplot
- Bernoulli Distribution Graph
- Binomial Distribution Graph
- Poisson Distribution Graph
- Actual vs Expected Poisson Distribution
- Log-Normal Distribution Fit
- Power Law Distribution Fit
- Original Transaction Q-Q Plot
- Log-Transformed Q-Q Plot
- Box-Cox Transformation Comparison
- Z-Score Probability Graph
- Probability Density Function (PDF)
- Cumulative Distribution Function (CDF)
- Statistical Distribution Comparison

## 📁 8. Project Structure

```text
Spread-Locator-Statistical-Analysis/
│
├── Spread_Locator_Analysis.ipynb
│
├── spread_locator_dataset.xlsx
│
├── README.md
│
├── LICENSE
│
├── .gitignore
│
├── charts/
│   └── Statistical Visualization Files
│
└── documentation/
    └── Theory_Concepts.pdf
```

## ⚙️ 9. Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Yashraj-datascience-ml/Spread-Locator-Statistical-Analysis.git
```

### Step 2: Navigate to Project Directory

```bash
cd Spread-Locator-Statistical-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install numpy pandas scipy matplotlib seaborn openpyxl jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Analysis

Open `Spread_Locator_Analysis.ipynb` and execute the notebook cells sequentially.

*Dataset access is required to reproduce the analysis. The repository owner should ensure the dataset is authorized for sharing before making the repository public.*

## 🔍 10. Statistical Concepts Applied

| Concept | Application |
|---|---|
| Descriptive Statistics | Mean, Median, Mode, Variance, Standard Deviation |
| Skewness & Kurtosis | Distribution shape analysis |
| Bernoulli Distribution | Binary transaction outcomes |
| Binomial Distribution | Transaction count modeling |
| Poisson Distribution | Daily transaction modeling |
| Log-Normal Distribution | Transaction amount modeling |
| Power Law Distribution | Heavy-tail modeling |
| Q-Q Plot | Distribution comparison |
| Shapiro-Wilk Test | Normality assessment |
| Box-Cox Transformation | Distribution transformation |
| Z-Score | Standardized values |
| PDF & CDF | Probability analysis |
| AIC | Model selection |
| KS Test | Distribution goodness-of-fit assessment |

## 💡 11. Business Insights

The analysis provides several useful observations:

1. The observed transaction success rate was approximately 44.55%.
2. Most observed transaction amounts were within the ₹5,000 threshold.
3. Probability distributions help describe transaction frequency and amount patterns.
4. Distribution transformations help investigate the effects of skewness.
5. The Log-Normal model achieved the lowest AIC among the three fitted models.
6. Statistical modeling can support better understanding of customer transaction behavior.

These findings describe the analyzed dataset and should not automatically be generalized to all e-commerce businesses.

## 🚀 12. Future Enhancements

Potential improvements include:

- Advanced Power Law tail estimation and goodness-of-fit testing.
- Bootstrap-based statistical validation.
- Interactive dashboards using Streamlit or Power BI.
- Regional transaction behavior analysis.
- Customer segmentation using statistical techniques.
- Transaction trend forecasting using Machine Learning.
- Automated statistical reporting.

## 👨‍💻 13. Author

**Yashraj Datascience ML**

GitHub: [Yashraj-datascience-ml](https://github.com/Yashraj-datascience-ml)

Project: **Spread Locator – Statistical Distribution Analysis**

## 📜 14. License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

<p align="center">
  <b>Spread Locator – Turning Transaction Data into Statistical Insights.</b>
  <br>
  <i>Built with Python, Statistics and Data Analysis.</i>
</p>
