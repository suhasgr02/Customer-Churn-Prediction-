# Customer Churn Prediction Using Logistic Regression and Random Forest

## 📌 Project Overview

Customer churn is a major challenge for businesses, as retaining existing customers is generally more cost-effective than acquiring new ones. This project develops machine learning models to **predict customer churn** using features derived from **demographics**, **transaction history**, **customer service interactions**, and **online activity**.

The workflow includes **data exploration**, **feature engineering**, and applying two machine learning algorithms: **Logistic Regression** and **Random Forest Classifier**, followed by thorough **model evaluation and comparison**.

---

## 📂 Dataset

The project utilizes customer data from multiple Excel sheets:

* **Customer\_Demographics** – Basic customer information (e.g., age, gender)
* **Transaction\_History** – Purchase behavior (e.g., spending, frequency)
* **Customer\_Service** – Interactions with support (e.g., service usage, complaints)
* **Online\_Activity** – Web/app usage patterns

---

## 🔎 Exploratory Data Analysis (EDA)

Key steps performed during EDA:

* Visualizing churn vs. non-churn customer distribution
* Analyzing spending patterns and transaction frequency
* Exploring service usage and complaints
* Investigating correlations between features

Visualizations were created using **Matplotlib** and **Seaborn**.

---

## 🛠 Feature Engineering

* Aggregated transaction metrics per customer
* Summarized service usage statistics
* Encoded categorical features using **LabelEncoder**
* Merged all datasets into a unified analytical dataset

---

## 🤖 Machine Learning Models

Two machine learning models were implemented and compared:

* **Logistic Regression** – A simple, interpretable baseline model
* **Random Forest Classifier** – An ensemble model for improved performance

### Evaluation Metrics:

* Accuracy
* Precision, Recall, F1-Score
* ROC-AUC Curve

---

## 📈 Results

* **Logistic Regression** provided a solid baseline for churn prediction.
* **Random Forest Classifier** delivered better performance in terms of **accuracy** and **ROC-AUC**, making it the preferred model.

---

## 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook**

   ```bash
   jupyter notebook Customer_Churn_Prediction.ipynb
   ```

4. **Update dataset file paths** inside the notebook and **run all cells** to reproduce results.

---

## 📦 Requirements

* Python 3.8+
* pandas
* matplotlib
* seaborn
* scikit-learn
* jupyter

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 📜 License

This project is licensed under the **MIT License**.
Feel free to use, modify, and share it for personal or commercial purposes.
