# Supervised Machine Learning: Predicting Hypertension
**Dataset:** `patient_records_dataset.csv` (500 patient records)  
**Task:** Binary Classification (`0` = No Hypertension, `1` = Hypertension)  

---
### Notebook Content Summary:
1. **Step 1: Data Inspection & Cleaning** — Removing non-predictive IDs and checking for missing values.
2. **Step 2: Feature Encoding** — Converting text categories (like `gender` and `smoker_status`) into numbers.
3. **Step 3: Splitting the Data (Train, Validation, Test)** — Why we never test a model on the exact same data it studied!
4. **Step 4: Feature Scaling** — Putting measurements like `weight_kg` and `systolic_bp_mmHg` on a fair scale.
5. **Step 5: Training & Validating Two Models** — Comparing **Logistic Regression** and a **Decision Tree** on the Validation set.
6. **Step 6: Cross-Validation** — Double-checking model stability across multiple data folds.
7. **Step 7: Final Evaluation on the Test Set** — Measuring real-world accuracy, precision, recall, and plotting a Confusion Matrix.


## Preliminaries
If you are running this locally, Execute the following commands in your CLI.

### a. create a virtual environment
`python -m venv venv`

### b. activate the virtual environment
`source venv/bin/activate` - <i>if you use a Linux/Unix OS</i><br>
`venv\Scripts\activate.bat` - <i>if you use a Windows OS</i><br>

### c. install the dependencies
Before running this command, ensure there's a (venv) at the beginning of your terminal's current directory text.<br/>
`pip install pandas matplotlib seaborn scikit-learn`