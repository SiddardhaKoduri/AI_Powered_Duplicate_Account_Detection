# AI-Powered Duplicate Account Detection

## Overview
This project detects customers holding multiple bank accounts using similarity matching techniques. It helps financial institutions identify duplicate accounts and suspicious identities.

## Features
- Name similarity matching using RapidFuzz
- Phone number matching
- PAN matching
- Risk score calculation
- Suspicious account identification

## Technologies Used
- Python
- Pandas
- NumPy
- RapidFuzz
- Scikit-learn
- Google Colab

## Sample Output

| Customer1 | Customer2 | Name Similarity | Risk Score |
|------------|------------|----------------|------------|
| 101 | 102 | 77.78 | 100 |
| 101 | 105 | 100.00 | 100 |
| 102 | 105 | 77.78 | 100 |

## Folder Structure

```
AI_Powered_Duplicate_Account_Detection/
│
├── AI_Powered_Duplicate_Account_Detection.ipynb
├── customers.csv
├── suspicious_accounts.csv
├── requirements.txt
├── README.md
└── .gitignore
```

## Author
**Siddardha Koduri**
