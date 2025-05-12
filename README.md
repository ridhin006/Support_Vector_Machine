# Loan Default Prediction 📊

This repository contains a Jupyter Notebook that analyzes a loan default dataset and builds a classification model to predict loan defaults.

## 📂 Project Structure
- `Untitled.ipynb` → Main Jupyter Notebook with data analysis and model building  
- `Loan_default.csv` → Dataset used in the project (ensure it's in the same directory)  
- `README.md` → Project documentation  

## 📜 Dataset
The dataset **Loan_default.csv** contains customer details and loan-related features.  
Some key columns
- **Education** → Highest education level of the applicant  
- **EmploymentType** → Type of employment (Salaried/Self-employed)  
- **MaritalStatus** → Married or single  
- **HasMortgage** → Whether the applicant has a mortgage  
- **LoanPurpose** → Purpose of taking the loan  
- **HasCoSigner** → Whether the loan has a co-signer  
- **DefaultStatus** → Target variable (1 = Default, 0 = No Default)  

## 🛠 Steps Performed in the Notebook
1. **Data Loading & Exploration**
   - Importing necessary libraries: `pandas`, `numpy`, `sklearn`
   - Reading `Loan_default.csv` using `pandas`
   - Displaying dataset overview  

2. **Data Preprocessing**
   - Dropping irrelevant columns (`LoanID`)
   - Encoding categorical columns using `LabelEncoder`
   - Standardizing numerical features using `StandardScaler`
   - Splitting data into training and testing sets  

3. **Model Training**
   - Using `Support Vector Classifier (SVC)` from `sklearn`
   - Training the model on the dataset  

4. **Model Evaluation**
   - Generating classification reports with **Precision, Recall, and F1-score**  

## 🚀 How to Run the Notebook
1. Clone the repository:  
   ```bash
   git clone https://github.com/ridhin006/Support_Vector_Machine

## 🚀 How to Run the Notebook

```bash
# Navigate to the project folder
cd loan-default-prediction

# Install dependencies
pip install pandas numpy scikit-learn

# Open Jupyter Notebook
jupyter notebook

# Run all cells in Untitled.ipynb

