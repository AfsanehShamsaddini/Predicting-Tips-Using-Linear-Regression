# 💸 Predicting Tips Using Linear Regression

This project explores how various factors like total bill amount, time of day, gender, and day of the week influence the tip given at a restaurant. Using data analysis and linear regression, we aim to predict tip amount and uncover hidden patterns in customer tipping behavior.

---

## 🎯 Objective

To build a predictive model that estimates the amount of tip based on other restaurant billing features. The model can be used to understand customer behavior and potentially optimize service strategies.

---

## 📊 Dataset

- 🗂️ Source: `seaborn` built-in `tips` dataset  
- 🔢 Features:
  - `total_bill`: Total bill (in USD)
  - `tip`: Tip amount (target)
  - `sex`, `smoker`, `day`, `time`: Categorical attributes
  - `size`: Number of people at the table

---

## 📋 Preprocessing

- Converted categorical variables using one-hot encoding
- Checked for missing values (none found)
- Standardized numerical columns
- No rows or columns were removed

---

## 📊 Exploratory Data Analysis (EDA)

- Correlation matrix (heatmap)
- Scatter plots of `tip` vs `total_bill`
- Boxplots showing tip distributions across days, gender, and smoker status

---

## 🧪 Hypothesis Testing

### 1. Does **day of the week** affect the tip amount?

- ✅ **Test**: One-way ANOVA
- 🎯 **Result**: No statistically significant difference in average tip across different days (p > 0.05)

### 2. Does **smoker status** impact tip amount?

- ✅ **Test**: t-test (not shown in code but possible extension)
- 🎯 **Result**: (Insert after future test...)

---

## 🧠 Modeling

- Applied **Linear Regression** to predict the `tip` amount
- Evaluated using **R²**, **MAE**, and **RMSE**
- Compared predicted vs actual tip values

---

## 🛠️ Tools Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`, `statsmodels`, `scipy`

---

## ✅ Conclusion

- `total_bill` is the strongest predictor of tip amount
- The number of people (`size`) and whether it was lunch/dinner also play roles
- No strong day-based effect observed in tipping habits

---

## 👨‍💻 Author
Afsaneh Shamsaddini

