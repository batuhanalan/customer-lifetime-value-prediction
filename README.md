# Customer Lifetime Value Prediction (BG-NBD & Gamma-Gamma)

This project predicts customer lifetime value (CLTV) using probabilistic models:
**BG-NBD** for purchase frequency and **Gamma-Gamma** for monetary value.

## Dataset
- Online Retail II dataset (UK-based online retailer)
- Date range: 01/12/2009 – 09/12/2011
- Dataset is not included in the repository due to size.

## Methodology
1. Data preprocessing and cleaning
2. BG-NBD model for expected number of transactions
3. Gamma-Gamma model for expected average profit
4. CLTV calculation for a given time horizon
5. Customer segmentation based on CLTV
6. End-to-end CLTV prediction function

## Output
- Expected purchases (weekly / monthly / quarterly)
- Expected average profit per customer
- Predicted CLTV
- CLTV-based customer segments (A, B, C, D)

## Tools & Libraries
- Python
- pandas
- lifetimes
- matplotlib
- scikit-learn

## Author
Batuhan Alan
