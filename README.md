# Task-1-Data-Cleaning-Preprocessing


**Files:**
- `data_cleaning_preprocessing.ipynb`  
- `Titanic-Dataset.csv`

**Steps:**
1. **Load & Inspect**: Read data; view types & nulls.  
2. **Impute & Drop**: Fill `Age` (median), `Embarked` (mode); drop `Cabin`.  
3. **Encode**: One-hot `Sex` & `Embarked`.  
4. **Scale**: Standardize numeric features.  
5. **Outliers**: Show boxplots; remove using IQR.  
6. **Save** (optional): Output `titanic_cleaned.csv`.

**Run:**
```bash
pip install pandas numpy matplotlib scikit-learn
python data_cleaning_preprocessing.py
```

