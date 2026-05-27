# 🧑‍💼 HR Employee Data Validation

## 📌 Project Overview
This project demonstrates **data quality analysis and validation** on an HR employee dataset.  
The goal is to ensure data accuracy and consistency by applying cleaning techniques on **joining dates, salaries, employee IDs, and department names**.

## ⚙️ Tech Stack
- Python 🐍
- Pandas & NumPy
- SQL (extension for validation queries)

## 📊 Tasks Performed
1. **Validate Joining Dates**
   - Convert to correct datetime format.
   - Handle invalid dates.
   - Replace future dates with `NaN`.

2. **Salary Validation**
   - Ensure salaries fall between **20,000 – 200,000**.
   - Flag unrealistic or negative salaries.

3. **Duplicate Employee IDs**
   - Detect and remove duplicate employee records.

4. **Department Standardization**
   - Normalize department names (e.g., `hr → HR`, `ops → Operations`).

## ✅ Outputs
- `cleaned_employee_data.csv` → final cleaned dataset.
- **Summary Report** of:
  - Invalid/Future Dates Fixed  
  - Invalid Salaries Fixed  
  - Duplicate Employee IDs Removed  

## 📂 File Structure
