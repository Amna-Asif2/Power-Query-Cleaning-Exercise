# Power-Query-Cleaning-Exercise

This repository contains a hands-on exercise for cleaning and transforming a dataset using **Power Query** in **Excel**. The exercise was completed as part of the course at **Hadielearning**, taught by **Aroosa Rehman**.

---

## 📂 Dataset

- **Source:** `Dirty_Dataset` sheet
- **Purpose:** Practice data cleaning, transformation, and preparation skills

---

## 🛠 Tasks Completed

1. **Import Dataset**  
   - Imported `Dirty_Dataset` into Power BI / Excel Power Query

2. **Department Column**  
   - Removed blanks and nulls  
   - Standardized names: Finance, IT, HR, Marketing, Operations

3. **Salary Column**  
   - Removed 'PKR' text  
   - Converted values like `55k` or `55 K` → `55000`  
   - Converted column data type to **Whole Number**

4. **FTE Column**  
   - Converted `Full = 1` and `Half = 0.5`  
   - Ensured numeric format

5. **Employee Type Column**  
   - Standardized values: Full Time, Part Time, Contract, Intern

6. **Work Location Column**  
   - Standardized capitalization: Karachi, Lahore, Islamabad, Remote, Dubai

7. **Start Date Column**  
   - Converted to **Date** format

8. **Handling Null Values**  
   - Department → 'Not Specified'  
   - Salary → 0

9. **Load Cleaned Dataset**  
   - Loaded back to Excel 

---

## 💡 Bonus Task

- Created a new column: `Annual Salary = Salary × 12`

---

## 🚀 Skills Practiced

- Data cleaning & transformation  
- Handling nulls and inconsistent values  
- Standardizing text and numeric formats  
- Power Query operations in Excel 

