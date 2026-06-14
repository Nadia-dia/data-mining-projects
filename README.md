# Data Mining & Machine Learning Portfolio

This repository contains comprehensive Exploratory Data Analysis (EDA) and predictive modeling projects conducted in **Python (Google Colab)** using `pandas`, `scikit-learn`, and `seaborn`. 

*Note: For the Adult Income project, the scripted Python models serve as a direct validation and comparison against baseline enterprise workflows previously executed in **Oracle Data Miner**.*

---

## 📊 Projects & Datasets

### 1. Wine Quality Dataset (UCI Machine Learning Repository)
* **Goal:** Analyze and model the physicochemical properties of red and white wine variants to evaluate their quality scores.
* **Scope in Python:** Advanced data preparation including automated delimiter detection, column standardization, and dataset merging (`pd.concat`). Extensive statistical and exploratory visualization of chemical properties (acidity, pH, alcohol content).

### 2. Loan Evaluation Dataset (Financial Risk Analytics)
* **Goal:** Inspect applicant profiles (income, credit history, loan amount) to evaluate features determining credit risk and loan approval outcomes.
* **Scope in Python:** Statistical data profiling, missing value assessment, and behavioral inspection of financial data distributions.

### 3. Adult Income Dataset (Census Data)
* **Goal:** Predict whether an individual's income exceeds $50K/year based on demographic and census variables.
* **Scope in Python:** Full pipeline implementation—including data cleaning (handling hidden missing values), One-Hot Encoding, and training a **Decision Tree Classifier**.
* **Methodology:** The Python model's metrics (Accuracy, Precision, Recall, and AUC/ROC) are deeply evaluated and compared against pre-computed benchmarks from Oracle Data Miner (GLM, Naive Bayes, SVM, and tuned Decision Trees).

## 🛠️ Tech Stack & Libraries
* **Environment:** Google Colab / Jupyter Notebooks
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `seaborn`, `matplotlib`
* **Machine Learning & Metrics:** `scikit-learn`

---

## 🚀 Setup & Installation
Since the project is structured within Jupyter Notebooks, you can easily open them in Google Colab. To install the required dependencies locally, clone the repository and run:

```bash
pip install -r requirements.txt
