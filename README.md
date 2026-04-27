
# Decoding Default — Multivariate Analysis of Loan Applicants

### Overview
An exploratory data analysis (EDA) project that investigates the factors influencing loan default among applicants. The analysis uses two datasets — current loan applications and previous application history — to uncover patterns and risk indicators associated with credit default.

### Datasets
- **application_train.csv** — Current loan application data with 307,511 records and 122 features, including applicant demographics, financial details, and a binary `TARGET` column (1 = defaulted, 0 = repaid).
- **previous_application.csv** — Historical loan application data with 1,670,214 records and 37 features, covering past loan types, amounts, statuses, and payment timelines.

### Key Features Analyzed
- Applicant demographics: gender, age, family status, education, housing type
- Financial attributes: income, credit amount, annuity, goods price
- Employment and registration details
- External credit bureau scores (`EXT_SOURCE_1/2/3`)
- Previous loan contract types, statuses, and payment behavior

### Libraries Used
- `pandas`, `numpy` — data manipulation
- `matplotlib`, `seaborn` — visualization
- `itertools` — combinatorial utilities

### How to Run
1. Download the datasets from [Kaggle — Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk/data).
2. Update the file paths in the notebook to point to your local copies of `application_train.csv` and `previous_application.csv`.
3. Open `Decoding Default Multivariate Analysis of Loan Applicants.ipynb` in Jupyter and run all cells.

---



