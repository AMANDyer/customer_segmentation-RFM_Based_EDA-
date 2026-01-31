# RFM Customer Segmentation Analysis

Modern customer segmentation using the classic **RFM** method (Recency, Frequency, Monetary).

This project helps businesses understand customer value, identify high-value loyal customers, at-risk customers, lost customers, and potential big spenders — all from transactional data.

## What is RFM?

| Metric    | Meaning                          | Business interpretation                     |
|-----------|----------------------------------|----------------------------------------------|
| **R**ecency  | How recently did the customer buy? | Lower = more recent = usually better       |
| **F**requency| How often do they purchase?      | Higher = more engaged/loyal                |
| **M**onetary | How much money do they spend?    | Higher = higher lifetime value             |

## Project Features

- Clean and prepare transactional data
- Calculate RFM scores
- Apply popular segmentation models:
  - 5×5 RFM matrix (25 segments)
  - Classic named segments (Champions, Loyal, At Risk, Hibernating, Lost, etc.)
  - Optional quantile-based or k-means clustering
- Visualizations: bar charts, heatmaps, scatter plots, box plots

## Project Structure
rfm-analysis/
├── data/
│   ├── raw/                ← data(raw)
│   └── processed/          ← rfm
├── notebooks/
│   └── rfm_project.ipynb   ← exploratory analysis & model building
├── requirements.txt
├── README.md
└── .gitignore


## Requirements

```text
pandas>=2.0
numpy>=1.24
matplotlib>=3.7
seaborn>=0.12
plotly>=5.14
scikit-learn>=1.3      # optional (if using k-means)
openpyxl               # if reading .xlsx


