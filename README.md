# 📊 Customer Churn Analysis

This project predicts telecom customer churn using machine learning. It analyzes customer behavior, usage patterns, and contract details to identify customers who are likely to leave the service. The project was built using Python (Pandas, Seaborn, Scikit-learn) and visualized using Power BI.

---

## 🔧 Tools & Technologies Used

- Python (Jupyter Notebook)
- Pandas, Numpy
- Seaborn, Matplotlib
- Scikit-learn (Logistic Regression)

---

## 📁 Project Files

- `customer_churn.ipynb` – Main Jupyter Notebook with data cleaning, EDA, modeling, and evaluation.
- `cleaned_data.csv` – Final dataset exported for dashboard and analysis.
- `README.md` – Project summary and documentation.

---

## 📊 Project Objectives

- Predict whether a customer is likely to churn.
- Understand key drivers that influence churn.
- Provide actionable insights through visualization and dashboards.

---

## 🧪 Methodology

1. **Data Cleaning & Preprocessing**
   - Handled missing values and converted data types
   - Encoded categorical variables using Label Encoding and One-Hot Encoding

2. **Exploratory Data Analysis (EDA)**
   - Used Seaborn to identify trends and patterns
   - Visualized churn rates by contract type, tenure, payment method, and monthly charges

3. **Model Building**
   - Applied Logistic Regression using Scikit-learn
   - Trained and tested the model (80/20 split)
   - Evaluated with Accuracy, Confusion Matrix, Precision, Recall, F1-Score

4. **Visualization**
   - Built an interactive Power BI dashboard showing churn metrics and KPIs

---

## 📉 Model Performance

- **Accuracy**: ~80%
- **Confusion Matrix**:
  - True Positives (Churn correctly predicted): High
  - False Negatives (Missed churns): Moderate – could improve with tuning
- **Precision & Recall**:
  - Good balance; effective for business use-case with clear interpretation

---

## 💡 Business Insights

- Customers with **month-to-month contracts** have the highest churn rate.
- **Electronic check** as a payment method is highly associated with churn.
- **Short-tenure customers** (new customers) are more likely to leave.
- Recommendations:
  - Offer loyalty discounts for at-risk customers
  - Promote annual contracts to increase retention

---

## 📎 Dataset Source

- [Telco Customer Churn Dataset – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 📌 How to Run

1. Clone the repository
2. Open `customer_churn.ipynb` in Jupyter Notebook
3. Run all cells to reproduce the analysis

---

## 📬 Contact

Feel free to connect or ask questions!  
**Sarabjeet Singh**  
[LinkedIn](https://www.linkedin.com/in/your-link/) | [Email](mailto:your-email@example.com)

---

⭐ *If you like this project, consider starring the repo!*
