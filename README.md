# 🧹 Data Preprocessing & Cleaning – Purchase Dataset

This project focuses on preprocessing and cleaning a raw dataset related to customer purchases. It demonstrates essential data preparation techniques needed before any meaningful analysis or machine learning can take place.

---

## 📌 Project Objectives

- Handle missing or inconsistent data.
- Format and standardize columns.
- Remove duplicates and irrelevant entries.
- Convert data types where necessary.
- Prepare a clean version of the dataset ready for further analysis.

---
## 📋 Dataset Overview

| Column         | Description                                      |
|----------------|--------------------------------------------------|
| `invoice_number` | Encoded invoice identifier                      |
| `invoice_time`   | Timestamp of the transaction (MM/DD/YY HH:MM)   |
| `store_id`       | Identifier of the store where purchase occurred |
| `product_id`     | Product identifier                              |
| `category_id`    | Product category code                           |
| `num_item`       | Number of items purchased                       |
| `price`          | Price per item                                  |

---

## 🧰 Processing Goals

- Convert scientific notation in `invoice_number` to readable integers
- Convert `invoice_time` to datetime format
- Remove duplicate transactions
- Identify and handle missing or zero values
- Normalize column types and names
- Create a cleaned dataset ready for analysis
---

## 🛠️ Techniques Used

- Handling **NaN**, **null**, and **zero-value** entries.
- Using `pandas` for:
  - Filtering invalid or irrelevant records
  - Renaming and reformatting columns
  - Converting data types (e.g., dates, numerics)
  - Identifying and removing duplicates
- Data exploration (shape, types, descriptive stats) to guide cleaning steps.

---

## 🧪 Output

After processing, the cleaned dataset:
- Has consistent and meaningful values
- Is free of duplicates and format issues
- Is ready for downstream tasks like visualization or model training

---

## 📁 Files Included

- `purchase_data.csv` – original dataset
- `pandas+practice.py` – Python script with all preprocessing steps

---

## ✅ How to Use

1. Clone the repository.
2. Ensure you have `pandas` installed:
   ```bash
   pip install pandas
## 📌 Note
Cleaning and preprocessing is one of the most critical steps in any data pipeline. This project is a solid foundation for anyone looking to strengthen their real-world data handling skills.
