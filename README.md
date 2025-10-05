# AI-Data-Cleaning-Automation
AI-Powered Data Cleaning Automation System 🤖✨

This project demonstrates a robust, multi-module system built in Python to automate the most challenging data cleaning tasks using Machine Learning (ML) and Large Language Model (LLM) logic.

****

## 🎯 Project Goal

To replace time-consuming, manual data cleaning with intelligent, scalable automation across three core data quality pillars.

---

## 🛠️ Technology Stack

* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn (KNNImputer, IsolationForest)
* **AI Logic:** K-Nearest Neighbors (K-NN), Isolation Forest, and Simulated GPT Logic.
* **Dataset:** Heart Disease UCI Dataset

---

## 💡 Automated Cleaning Modules

### 1. Missing Value Imputation (K-NN ML Model)
* **Problem Solved:** High volumes of missing data (e.g., 66% missing in the `ca` column).
* **Method:** Used **K-NN Imputer** to predict and fill missing values based on the data of the 5 most similar records in the dataset.
* **Result:** Reduced missing value count from **~600 to 0** records.

### 2. Anomaly Detection (Isolation Forest ML Model)
* **Problem Solved:** Identification of statistical outliers and errors in numerical columns (e.g., impossible Cholesterol readings).
* **Method:** Applied the **Isolation Forest** algorithm to flag unusual records.
* **Result:** Automatically flagged **275 suspicious records** in the `chol` column for review.

### 3. Categorical Standardization (Simulated GPT Logic)
* **Problem Solved:** Inconsistent text, typos, and synonyms in categorical features (e.g., 'ASymptomatic', 'Non-classic Angina').
* **Method:** Implemented **LLM-like logic** to standardize messy input strings into clean categories and flag completely unknown terms.
* **Result:** Ensured **100% text consistency** for downstream analysis.
