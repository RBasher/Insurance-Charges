Insurance Rate Key Influencers Analysis
Project Overview
The goal of this project is to provide insurance agents with a data-driven guide to understanding how customer characteristics influence insurance rates
. By analyzing a dataset of 1,300 customers, this study aims to identify the specific traits that raise or lower insurance costs to help agents make more informed decisions
.
Problem Statement
Management requires better-informed agents who can explain insurance rate fluctuations based on customer profiles
. This project addresses four key questions:
What does a typical customer profile look like?
Which customer traits significantly raise or lower rates?
Does gender impact the charged rate?
What is the single trait that most significantly skyrockets costs?
Methodology
The analysis was conducted using the following tools and techniques:
Tools: Microsoft Excel and PowerPoint
.
Techniques: Regression Analysis (specifically Multiple Linear Regression) and Univariate Analysis
.
Metrics: Average (Mean), Median, Sum, Count, and Regression Coefficients
.
Average Customer Profile
Based on the univariate analysis, the "average" customer in this dataset has the following characteristics:
Average Rate: $13,270.42
Average Age: ~39 years
Average BMI: 30.66
Gender Distribution: 51% Male, 49% Female
Smoker Status: 80% Non-smokers, 20% Smokers
Statistical Model & Results
A Multiple Linear Regression model was used to predict medical charges based on Age, BMI, Children, Gender, Smoking Status, and Region
.
Model Performance
R 
2
  = 0.751: The model explains 75.1% of the variance in medical charges
.
Significance F ≈ 0: The model is statistically reliable and the results are unlikely to be due to chance
.
Key Influencers (Coefficients)
Variable
Coefficient (Impact on Cost)
P-value
Significance
Smoker
+$23,848.53
<0.001
Strongest Predictor
Children
+$475.50
<0.001
Significant
BMI
+$339.19
<0.001
Significant
Age
+$256.86
<0.001
Significant
Female
+$131.31
0.693
Not Significant
Northeast
+$1,035.02
0.031
Small Significance
Key Business Takeaways
Smoking is the primary driver: Smoking status is the single largest factor, with smokers incurring charges approximately four times higher than non-smokers
.
Physical Metrics: Both Age and BMI are strong predictors of increasing healthcare costs
.
Non-Factors: After accounting for other variables, gender and most geographic regions do not have a statistically significant effect on medical charges
.
