# 🧠 Customer Segmentation for Credit Card Customers

## 📌 Project Overview

This project aims to segment customers based on their **credit card usage behavior** using unsupervised learning techniques. The dataset provides detailed financial activities and habits of customers, such as purchase types, payment patterns, cash advances, and credit limits.

By analyzing and clustering the data, we aim to:
- Understand customer behaviors and patterns.
- Identify key customer segments.
- Provide business insights to improve marketing strategies, risk management, and customer engagement.

---

## 🎯 Business Objective

The core objective of this analysis is to **help the business understand its customers better**, so they can:
- Target high-value customers with personalized offers.
- Reduce risk by identifying potentially risky users (e.g., frequent cash advances).
- Improve customer retention by understanding long-term loyal users.

---

## 🧾 Dataset Description

The dataset contains anonymized credit card transactions of customers over a period of time. Each row represents a customer with the following features:

| Feature                     | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `BALANCE`                  | Remaining balance in the customer's account.                                |
| `BALANCE_FREQUENCY`        | Frequency of balance updates (0–1).                                         |
| `PURCHASES`                | Total amount of purchases.                                                  |
| `ONEOFF_PURCHASES`         | Purchases made in a single transaction.                                     |
| `INSTALLMENTS_PURCHASES`   | Purchases made in installments.                                             |
| `CASH_ADVANCE`             | Amount of cash advance taken.                                               |
| `PURCHASES_FREQUENCY`      | How frequently purchases are made (0–1).                                    |
| `ONEOFFPURCHASESFREQUENCY` | Frequency of single transaction purchases (0–1).                            |
| `PURCHASESINSTALLMENTSFREQUENCY` | Frequency of installment-based purchases (0–1).                    |
| `CASHADVANCEFREQUENCY`     | Frequency of cash advances (0–1).                                           |
| `CASHADVANCETRX`           | Number of cash advance transactions.                                        |
| `PURCHASES_TRX`            | Number of purchase transactions.                                            |
| `CREDIT_LIMIT`             | Customer's credit limit.                                                    |
| `PAYMENTS`                 | Total amount paid by the customer.                                          |
| `MINIMUM_PAYMENTS`         | Minimum payment made.                                                       |
| `PRCFULLPAYMENT`           | Percentage of full payments made (0–1).                                     |
| `TENURE`                   | Number of months the customer has had the credit card.                      |

---

## 📈 Project Phases

1. **Data Exploration and Preprocessing**  
   - Clean the data and handle missing values.
   - Explore feature distributions and relationships.
   - Initial insights to guide clustering decisions.

2. **Determine Optimal Number of Clusters**  
   - Use Elbow Method and Silhouette Score to identify optimal cluster count.

3. **Customer Segmentation**  
   - Apply clustering algorithms (e.g., K-Means).
   - Label and interpret clusters.

4. **Visualization and Analysis**  
   - Use graphs to show behavioral differences between clusters.
   - Extract business insights from patterns.

5. **Business Recommendations**  
   - Summarize segment characteristics.
   - Propose actions based on customer behaviors.

---

## 🛠️ Tools & Technologies

- Python
- Pandas / NumPy
- Matplotlib / Seaborn / Plotly
- Scikit-learn (KMeans, PCA)
- Jupyter Notebook / Google Colab

---

## 📦 Dataset Source

- [Customer Segmentation - Credit Cards on Kaggle](https://www.kaggle.com/code/des137/customer-segmentation-credit-cards)

---

## 👩‍💻 Created by

Made with 💙 by **Rowaina Reda**  
[LinkedIn](https://www.linkedin.com/in/rowaina-reda) • [GitHub](https://github.com/RowainaReda)
