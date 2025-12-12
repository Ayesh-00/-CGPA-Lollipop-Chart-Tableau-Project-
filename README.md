# 🎓 CGPA Lollipop Chart (Tableau Project)

This repository contains a Tableau project that classifies student CGPA into **High** and **Low** categories using a calculated field with the **ABS() absolute function**.  
The project also includes a **Lollipop Chart** to visually compare High and Low CGPA distributions.

---

## 📊 Features
- Categorization of CGPA based on threshold **3.5**
- Uses **ABS() function** for clean and consistent classification
- Attractive **Lollipop Chart** visualization
- Includes workbook (.twbx), sample dataset, and calculated fields

---

## 🧮 Calculated Field (High VS Low CGPA)

```tableau
IF ABS([CGPA]) >= 3.5 THEN "High CGPA"
ELSE "Low CGPA"
END
