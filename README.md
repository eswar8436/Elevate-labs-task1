# Task 1: Data Cleaning & Preprocessing  
**Elevate Labs AI & ML Internship**

Hi, this is my submission for Task 1 (Eswar K).

I followed the hints step by step:
1. Loaded Titanic dataset and checked info, nulls, data types.
2. Handled missing values – median for Age, mode for Embarked, dropped Cabin.
3. Encoded categorical columns (manual map for Sex + one-hot for Embarked).
4. Standardized Age and Fare using Z-score.
5. Used boxplots to visualize outliers and removed them with IQR method.

I added extra prints and saved plots so I could see the changes clearly.

**Files included:**
- data_cleaning_preprocessing.ipynb (full code)
- titanic_cleaned.csv (final cleaned dataset)
- outliers_before.png & outliers_after.png (visualizations)

**What I learned:**
- Why preprocessing matters a lot before ML
- Median works better than mean for Age
- Difference between label encoding and one-hot encoding
- How outliers affect scaling

Took some time debugging but learned a lot! Ready for review 😊

Submitted on 09-April-2026
