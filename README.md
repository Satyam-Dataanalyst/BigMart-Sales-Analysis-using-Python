# Bigmart Sales Data Analysis

This project demonstrates a quick exploratory data analysis (EDA) using **Python** and **Pandas**. It was developed in Google Colab to showcase core data manipulation skills, including data loading, summarization, and cross-tabulation.

---

## 🚀 Project Overview
The analysis focuses on understanding the Bigmart sales dataset by reviewing item characteristics (like weight and type) and store metrics (like size and type).

---

## 🛠️ Key Python Features Used
*   **Data Loading:** Importing the `pandas` library and reading CSV data into a DataFrame.
*   **Initial Review:** Using `.head()` to inspect the first 5 rows of the dataset.
*   **Data Summarization:** 
    *   Created pivot tables to calculate the **Mean Weight** of items per category (e.g., Dairy: 13.42, Starchy Foods: 13.69).
    *   Analyzed **Average Item Price (MRP)** across different `Outlet_Size` and `Outlet_Type`.
*   **Frequency Tables:** Used `pd.crosstab()` to generate a contingency table counting occurrences of `Item_Type` within various `Outlet_Size` categories.

---

## 📊 Summary of Findings

| Item Type | Mean Weight |
| :--- | :--- |
| Dairy | 13.426069 |
| Fruits and Vegetables | 13.224769 |
| Snack Foods | 12.987880 |
| Household | 13.384736 |

*Refer to the full PDF for the complete breakdown of item counts and outlet pricing.*

---

## 📂 Repository Contents
*   `bigmart_data.csv`: The source dataset.
*   `notebook.ipynb`: Python code and scripts.
*   `Bigmart_Sales_Data.pdf`: A summary of the code and visual outputs.

---
*Developed as a portfolio starter project to demonstrate data analysis proficiency.*
