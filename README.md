# Predicting-Attorney-Representation-In-Insurance-Claims-Using-Logistic-Regression
Business Problem : 
Insurance companies often face challenges in managing claims efficiently.
One critical aspect is understanding whether a claimant will hire an attorney to represent them in the claim process. This can significantly impact the cost ,duration and outcome of the claims

Problem Discussion :
Why is this important ?
when claimants hire attorneys, it often leads to higher settlement costs and longer processing times for insurance companies Predicting the likelihood of attorney involvement helps insurers allocate resources more efficiently, streamline claim processing and potentially reduce unnecessary legal expenses.

Prediction : 
The goal is to build a logistic regression model that predict whether a claimant will hire an attorney (ATTORNEY = 1) or not (ATTORNEY =0) based on the feature such as :

Claimant's demographics(Age,gender)

insurance detail(claim insurance status)

Accident -related factors (seatbelt usage,loss amount)

## Dataset
- Source: Kaggle (file: claimants.csv)
- Target variable: ATTORNEY (1 = hired attorney, 0 = did not hire)

## Features Used
- CLMAGE – Claimant's age
- CLMSEX – Claimant's gender
- CLMINSUR – Insurance status
- SEATBELT – Seatbelt usage
- LOSS – Loss amount

## Methodology
1. Data cleaning & handling missing values
2. Exploratory Data Analysis (EDA)
3. Feature encoding
4. Train-test split
5. Logistic Regression model training
6. Model evaluation

## Results
- Accuracy: 0.70
- AUC-ROC: 0.72

## Tools & Libraries
- Python, Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn

## How to Run
1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Open `Predicting Attorney.ipynb` in Jupyter

## Conclusion
The logistic regression model achieves moderate predictive performance (Accuracy: 70%, AUC-ROC: 0.72), indicating it can reasonably distinguish between claimants likely to hire an attorney and those who aren't. This can help insurers proactively allocate resources and anticipate higher-cost claims.
