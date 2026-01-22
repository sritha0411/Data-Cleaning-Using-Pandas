# Data-Cleaning-Using-Pandas

**Overview**

This project demonstrates basic data cleaning and preprocessing techniques using Python (Pandas).
The objective is to read a dataset, identify and handle missing values, remove duplicates, perform basic feature engineering, and export a cleaned dataset for further analysis.

---

**Dataset**

Dataset Name: Titanic Dataset
Source: Loaded directly from a GitHub link
Format: CSV

The dataset contains passenger information such as age, fare, gender, embarkation port, and family details.

---

**Tools & Technologies:**

Language: Python

Libraries: Pandas, NumPy

Environment: Google Colab

---

**Data Cleaning Steps Performed:**

-> Loaded the dataset using pandas.read_csv().

-> Inspected the dataset structure using head() and info().

-> Identified missing values using isnull().sum().

-> Filled missing numerical values (Age, Fare) using median.

-> Filled missing categorical values (Embarked) using mode.

-> Avoided inplace=True to prevent chained assignment warnings.

-> Removed duplicate rows using drop_duplicates().

---

**Created new features:**

Age_Group (Child, Adult, Senior)

Family_Size

Exported the cleaned dataset using to_csv().

---

**Feature Engineering:**

Age_Group: Categorizes passengers based on age.

Family_Size: Combines siblings/spouses and parents/children count to determine family size.

These transformations help improve data usability for analysis and modeling.

---

**Output Files:**

Task5_Cleaning.ipynb → Jupyter notebook with code and markdown explanations

cleaned_data.csv → Final cleaned dataset ready for analysis

---

**Key Learnings:**

Handling missing data effectively in Pandas

Understanding the importance of datatype consistency

Applying basic feature engineering

Writing clean, warning-free Pandas code

Documenting data preprocessing steps clearly
