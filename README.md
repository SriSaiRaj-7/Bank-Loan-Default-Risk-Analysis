# Bank Loan Default Risk Analysis

This Data Science mini project analyzes historical bank loan data to understand patterns between borrower attributes, such as credit score, interest rate, and loan purpose, and loan repayment outcome. It uses NumPy, Pandas, Matplotlib, SciPy, and scikit-learn.

## Dataset

The dataset contains 148,670 records and 34 columns. The target column is `Status`, where `1` means the loan defaulted and `0` means it was repaid. Every record is an already-approved loan, so this project analyzes repayment outcomes, not loan approval decisions.

## Tasks Covered

1. NumPy Arrays
2. Pandas DataFrames
3. Matplotlib Plots
4. Frequency Distributions
5. Averages
6. Variability
7. Normal Curves
8. Correlation & Scatter Plots
9. Correlation Coefficient
10. Regression

## Key Findings

- About 24.6% of the loans in the dataset defaulted.
- The total loan amount disbursed across all records is 49,227,275,000.
- Average credit scores are nearly the same for repaid loans (about 699.5) and defaults (about 700.6), so credit score alone does not strongly separate the two groups in this dataset.
- The interest rate mean is 4.0455 and the median is 3.9900; the notebook describes the column as not heavily skewed. Its distribution is also described as approximately normal.
- Loan purposes are coded as `p1`–`p4`. The most frequent codes are `p3` (55,934 loans) and `p4` (54,799); the notebook does not provide a mapping to plain-language purpose names.
- Credit score and interest rate have almost no linear correlation (-0.00133). The regression has an R² of 0.000002, indicating very little predictive power for this relationship.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/SriSaiRaj-7/Bank-Loan-Default-Risk-Analysis.git
   cd Bank-Loan-Default-Risk-Analysis
   ```

2. Install the dependencies:

   ```bash
   pip install numpy pandas matplotlib scipy scikit-learn notebook
   ```

3. Place the dataset CSV named `Loan_default_Dataset.csv` in the repository folder, next to the notebook.
4. Start Jupyter Notebook, open `Bank_Loan_Default_Risk_Mini_Project_claude.ipynb`, and run the cells from top to bottom:

   ```bash
   jupyter notebook
   ```

## Team

- SRI SAI RAJ  •  SRINIVASH M  •  SUPRIYA K M  •  THIRUMURUGAN  •  YUVAN P