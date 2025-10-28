 🧹 Text Cleaning with Formulas — Week 1

### 🗓 Date: 26/10/2025  
### 📁 File: Week1_Cleaned.xlsx  

---

### 🧠 Goal:
Practice Excel text-cleaning formulas to standardize and tidy messy text fields.

---

### 🧩 Steps Taken:

| **Task** | **Formula Used** | **Purpose** | **Result** |
|-----------|------------------|--------------|-------------|
| Removed extra spaces | `=TRIM(A2)` | Cleans leading/trailing spaces | Text became cleaner and more consistent |
| Removed hidden characters | `=CLEAN(A2)` | Deletes non-printable symbols | Fixed rows that had invisible errors |
| Capitalized names/titles | `=PROPER(A2)` | Converts text to proper case | Improved readability (e.g., “john doe” → “John Doe”) |
| Standardized case | `=UPPER(A2)` / `=LOWER(A2)` | Ensures uniform capitalization | Standardized product names and categories |
| Extracted text segments | `=LEFT()` / `=RIGHT()` / `=MID()` / `=FIND()` | Split long strings (like order IDs or email domains) | Created separate columns for components |

---

### ✅ Summary:
- Cleaned and standardized multiple text fields using built-in Excel functions.  
- Learned how each formula targets a specific data issue.  
- Discovered that combining `TRIM`, `CLEAN`, and `PROPER` together provides professional, presentation-ready text.  
