# Healthcare Data Analysis

This project analyzes and visualizes health data to identify trends and risk factors related to heart health. The dataset includes demographic, lifestyle, and clinical information. The analysis uses Python and its data science libraries to explore patterns, categorize health indicators, and produce informative visualizations.

---

## 📂 Project Files
All files are in one folder:
- `healthcareDS.csv` → raw healthcare dataset   
- `health_data_analysis.ipynb` → Jupyter Notebook version of the analysis  

---

## ⚙️ What the code does
1. **Reads the dataset** from CSV.  
2. **Cleans the data**:
   - Splits `Blood Pressure` into `Systolic BP` and `Diastolic BP`  
   - Removes unnecessary columns (`Patient ID`, `Family History`, `Country`, etc.)  
   - Checks for missing values and ensures correct data types  
3. **Feature engineering**:
   - Categorizes blood pressure into `BP Category`  
   - Categorizes BMI into `BMI Category`  
   - Calculates heart attack risk category (`Heart Attack Risk`) based on cholesterol, blood pressure, diabetes, smoking, and obesity  
4. **Visualizations**:
   - Bar plots of age distribution by BP category and gender  
   - Box plots of BMI by BMI category  
   - Pie charts showing heart attack risk for smokers vs. non-smokers  
   - Risk distribution by age group, obesity, and diabetes  
   - Count plots of heart attack risk by gender  

---

## 🛠️ Technologies Used
- Python   
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
