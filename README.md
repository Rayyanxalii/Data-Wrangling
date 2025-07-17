

# 🧹 Employee Data Cleaning Project

This project focuses on cleaning and preparing raw employee data for further analysis or machine learning workflows. It includes handling missing values, correcting data types, standardizing text entries, and restructuring the dataset for consistency and clarity.

---

## 📁 Dataset

The dataset includes various employee-related fields such as:

* Employee ID
* Name
* Department
* Gender
* Age
* Join Date
* Salary
* and more

---

## 🛠 What I Did

* ✅ **Handled Missing Values**: Identified and filled or removed null entries.
* 🔤 **Standardized Text Data**:

  * Replaced inconsistent department labels (e.g., “Hr” → “Human Resources”).
  * Capitalized names properly using string functions.
* 🔢 **Converted Data Types**:

  * Converted `Gender` column from object to category.
  * Parsed and formatted `Join_Date` to datetime.
* 🆔 **Transformed Identifiers**:

  * Renumbered Employee IDs from arbitrary values to clean integer indices.
* 📄 **Reorganized Records**:

  * Moved all entries with missing or unknown names to the bottom of the dataset.

---

## 📦 Tools Used

* **Python**
* **Pandas**
* **NumPy**
* **Jupyter Notebook**

---

## 📂 File Structure

```
📁 employee-data-cleaning/
├── employee_raw.csv
├── employee_cleaned.csv
├── data_cleaning.ipynb
└── README.md
```

---

## 🧠 Learnings

* Strengthened data wrangling and preprocessing skills using Pandas.
* Improved understanding of data types and categorical encoding.
* Practiced systematic cleaning steps for real-world HR datasets.

---

## 📬 Feedback

Have suggestions or want to collaborate? Feel free to reach out or fork the repo!

---

