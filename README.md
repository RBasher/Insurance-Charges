# 📊 Insurance Rate Key Influencers Analysis

## 📌 Project Overview
This project analyzes **1,300 insurance customers** to identify which customer characteristics have the greatest impact on insurance rates.

The goal is to help insurance agents better explain why premiums vary across customers by using statistical analysis instead of assumptions.

---

# 🎯 Business Problem

Insurance agents often need to explain why one customer pays more than another.

This project answers four key business questions:

- What does a typical insurance customer look like?
- Which customer characteristics increase insurance rates?
- Does gender influence insurance costs?
- Which single factor has the largest impact on insurance charges?

---

# 🛠️ Tools Used

- Microsoft Excel
- PowerPoint

---

# 📈 Analytical Methods

### Statistical Techniques
- Multiple Linear Regression
- Univariate Analysis

### Metrics Used
- Average (Mean)
- Median
- Count
- Sum
- Regression Coefficients

---

# 👤 Average Customer Profile

| Metric | Value |
|---------|-------|
| Average Insurance Charge | **$13,270.42** |
| Average Age | **39 years** |
| Average BMI | **30.66** |
| Male Customers | **51%** |
| Female Customers | **49%** |
| Non-Smokers | **80%** |
| Smokers | **20%** |

---

# 📊 Regression Model Performance

A **Multiple Linear Regression** model was built using:

- Age
- BMI
- Number of Children
- Gender
- Smoking Status
- Region

### Model Accuracy

- **R² = 0.751**
  - The model explains **75.1%** of the variation in insurance charges.

- **Significance F ≈ 0**
  - The overall regression model is statistically significant.

---

# 🔍 Key Cost Drivers

| Variable | Impact on Insurance Cost | P-value | Interpretation |
|-----------|-------------------------:|---------|----------------|
| 🚬 Smoker | **+$23,848.53** | <0.001 | Strongest Predictor |
| 👶 Children | **+$475.50** | <0.001 | Significant |
| ⚖️ BMI | **+$339.19** | <0.001 | Significant |
| 🎂 Age | **+$256.86** | <0.001 | Significant |
| 👩 Female | **+$131.31** | 0.693 | Not Significant |
| 📍 Northeast | **+$1,035.02** | 0.031 | Small Effect |

---

# 💡 Key Insights

## 🚬 Smoking Has the Largest Impact

Smoking is by far the strongest predictor of insurance costs.

- Smokers pay approximately **$23,849 more** than non-smokers after controlling for other variables.
- This makes smoking the single most influential factor in determining insurance charges.

---

## ⚖️ Higher BMI Increases Costs

Insurance charges increase as BMI rises.

- Every 1-point increase in BMI is associated with an average increase of approximately **$339** in insurance charges.

---

## 🎂 Older Customers Pay More

Age is positively associated with insurance costs.

- Each additional year of age increases expected charges by approximately **$257**.

---

## 👶 More Children Slightly Increase Costs

Each additional child increases expected insurance charges by approximately **$476**.

---

## 👩 Gender Has No Meaningful Effect

After accounting for age, BMI, smoking status, and other variables, gender does **not** significantly affect insurance charges.

---

## 📍 Region Has Minimal Influence

Most regions show little to no statistically significant effect on insurance costs.

The Northeast shows a small increase in average charges, but its impact is much smaller than smoking, age, or BMI.

---

# 📌 Business Recommendations

- Prioritize smoking status when estimating customer premiums.
- Consider BMI and age as key indicators during risk assessment.
- Avoid making pricing assumptions based on gender, as it is not a statistically significant predictor.
- Use regression analysis to support transparent, data-driven conversations with customers.

---

# 📈 Conclusion

This analysis demonstrates that **customer lifestyle and health characteristics are far more influential than demographic factors** when determining insurance costs.

The regression model explains **75.1%** of the variation in insurance charges, with **smoking status emerging as the most significant predictor**, followed by BMI, age, and number of children.

These findings provide insurance agents with actionable insights to better explain premium differences and support more informed, data-driven decision-making.
.
