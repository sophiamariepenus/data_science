# data_science

# 🧪 Exploratory Data Analysis (EDA) on Pima Indians Diabetes Dataset

## 📌 Project Overview

The Pima Indians Diabetes dataset contains medical diagnostic data for female patients of Pima Indian heritage, aged 21 and older. The objective is to explore this dataset to uncover trends, patterns, and potential insights about diabetes onset.

---

## 🧬 Dataset Description

- **Source**: UCI Machine Learning Repository / Kaggle
- **Rows**: 768
- **Columns**: 8 features + 1 target

### Features:
| Column | Description |
|--------|-------------|
| Pregnancies | Number of times pregnant |
| Glucose     | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skinfold thickness (mm) |
| Insulin      | 2-Hour serum insulin (mu U/ml) |
| BMI          | Body Mass Index (weight in kg/(height in m)^2) |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age          | Age (years) |
| Outcome      | Target variable (1 = diabetes, 0 = no diabetes) |

---

## 📊 Key Steps in the EDA

1. **Data Cleaning**
   - Checked for missing or zero values in medical columns
   - Replaced zeros with NaNs and handled appropriately

2. **Univariate Analysis**
   - Histograms and boxplots for feature distribution
   - Summary statistics (mean, median, std)

3. **Bivariate Analysis**
   - Correlation heatmap
   - Comparison of feature distributions by diabetes outcome

4. **Multivariate Analysis**
   - Pair plots
   - Feature interaction exploration

5. **Outlier Detection**
   - Visualized with boxplots
   - Discussed possible removal strategies

6. **Insights & Observations**
   - Higher glucose and BMI levels are strongly associated with diabetes
   - Age and pregnancy count also show trends with diabetes onset

---

## 📌 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn` (optional for preprocessing)


