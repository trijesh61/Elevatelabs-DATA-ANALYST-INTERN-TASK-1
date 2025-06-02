# 🧼 Task 1: Data Cleaning & Preprocessing

## 🔍 Objective
Clean and preprocess raw sales data using Python and Pandas. This task involves handling missing values, removing duplicates, standardizing formats, and preparing the dataset for analysis.

---

## 📊 Dataset Information
- **Name**: Sample Sales Data  
- **Source**: [Kaggle - Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)  
- **File**: `sales_data_sample.csv`

---

## ⚙️ Tools Used
- Python 3
- Pandas Library
- Jupyter Notebook

---

## 🧹 Cleaning Summary
| Step | Description |
|------|-------------|
| ✅ Missing Values | Handled using forward fill |
| ✅ Duplicates | Removed using `.drop_duplicates()` |
| ✅ Column Names | Standardized to lowercase with underscores |
| ✅ Date Format | Converted `orderDate` to `datetime` |
| ✅ Data Types | Cast `quantityOrdered` to `int` |
| ✅ Null Rows | Dropped rows with all values missing |

---

## 📁 Output Files
- `cleaned_sales_data.csv` – Final cleaned dataset
- `Task_1_Data_Cleaning.ipynb` – Code notebook with all steps

---

## 🚀 How to Use
1. Clone or download the repository.
2. Open `Task_1_Data_Cleaning.ipynb` in Jupyter/Colab.
3. Run the cells to clean the dataset.
4. Use `cleaned_sales_data.csv` for further analysis or modeling.

---

## 🙋‍♂️ Author
**Trijesh Kondapuram**  
Data Analyst Internship – Task 1 Submission
