# EDA Findings – California Housing Dataset

## 1. Three Findings

**Finding 1: Feature Correlation**
- `median_income` has the strongest positive relationship with `median_house_value`.
- `total_rooms` has a positive relationship with `median_house_value`.
- `latitude` shows a negative relationship with `median_house_value`.

**Finding 2: Feature Distribution**
- `total_rooms`, `total_bedrooms`, `population`, and `households` have right-skewed distributions.
- Most observations have smaller values.
- A few observations have very large values.

**Finding 3: Feature Relationships**
- `total_bedrooms` and `households` have a strong positive relationship.
- `total_rooms` and `total_bedrooms` also have a strong positive relationship.
- Some numerical features are highly correlated with each other.

## 2. One Data Quality Issue

- Duplicate rows may exist in the dataset.
- I checked duplicate rows using `df.duplicated().sum()`.
- I used `df.drop_duplicates()` to remove duplicate records.

## 3. Project Reflection

**What I built:**  
I performed Exploratory Data Analysis (EDA) on the California Housing Dataset using Pandas, Histograms, and a Correlation Heatmap.

**What broke:**  
I found duplicate records that needed to be checked and removed before further analysis.

**What I learned:**  
I learned how to check duplicate data, understand feature distributions, analyze correlations, and identify relationships between numerical features.
