# 📉 Product Churn Prediction – Capstone Project (Chartway Credit Union)

This project was completed as my final capstone for my Business Analytics program at William & Mary. In partnership with Chartway Credit Union, the goal was to analyze mdata to identify early signs of churn for their non-maturity financial products and build a predictive model to support strategic retention efforts.

---

## 📌 Problem Statement

Chartway Credit Union sought to understand the behavioral patterns and attributes that indicate a customer is likely to close a financial product. The project aimed to answer:

> **Can we predict early signs of product churn using historical customer data?**

---

## 🧠 Project Objectives

- Define and quantify "churn" for non-maturity products
- Explore and prepare data from multiple Tables (Product, Member, Account, and Transaction)
- Engineer meaningful features to represent financial behavior
- Build and evaluate classification models to predict churn
- Provide business insights and recommendations for intervention strategies

---

## 🔧 Tools & Technologies

- **Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
- **Environment:** Jupyter Notebook, SQL Server Management Studio (SSMS), Docker
- **Data Handling:** 8GB `.bak` file restored and queried via SQL Server

---

## 🗂️ Project Structure

```

product-churn-prediction/
│
├── data/                    # Sample or transformed datasets
├── notebooks/               # Jupyter Notebooks for analysis and modeling
├── scripts/                 # Python scripts for loading, cleaning, and modeling
├── visuals/                 # Charts, confusion matrices, and plots
├── Docker/                  # Docker setup for SQL Server
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies

```

---

## 📊 Key Steps

1. **Data Ingestion:** Loaded a large `.bak` SQL backup file into Dockerized SQL Server.
2. **Data Cleaning:** Addressed data integrity issues and joined `Product`, `Account`, and `Member` tables.
3. **Feature Engineering:** Created `Churn` (non-null `ProductCloseDate`), `Tenure`, and `TotalBalanceCombined`.
4. **Modeling:** Used Random Forest Classifier; tuned hyperparameters for optimal performance.
5. **Evaluation:** Assessed using accuracy, precision, recall, and AUC-ROC; presented findings to stakeholders.

---

## 🚀 Results

- Developed a robust churn prediction model with interpretable features
- Delivered actionable insights to Chartway for proactive customer retention
- Simplified complex transaction data into high-value business indicators

---

## 🏆 Recognition

This project was submitted as part of the William & Mary MSBA program and showcased at the final capstone presentation. It demonstrated strong application of business analytics to solve real-world problems and contributed meaningful insights to the client partner.

---

## 🤝 Acknowledgments

- **Chartway Credit Union** – for providing the dataset and problem context  
- **William & Mary Faculty** – for guidance and mentorship  
- **MSBA Capstone Team Members** – for collaborative effort and execution  

---

## 📬 Contact

**Thokozile Munthali**  
📧 thokomunthali22@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/thokozile-munthali) | [GitHub](https://github.com/Thokozile23)
```




