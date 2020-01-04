Customer maganize purchase prediction 
--

Objective: 
--
- Implement a binary classification model that will take inputs as features and predict if customers will purchase the maganize or not. 

Data Set Description
---

- 17 columns and 673 observations. 

Featured Variables
---
1. Household Income : household income rounded to the nearest $1,000.00
2. Is Female: gender ( 1 = female, 0 = other)
3. Is Married : ( 1 = married, 0 = married)
4. Has College : (1 = 1 or more years of college , 0 = other)
5. Is Professional : ( 1 = working in a profession , 0 = other)
6. Is Retired : ( 1 = is retired , 0 = other)
7. Unemployed : ( 1 = unemployed , 0 = other)
8. Residence Length : ( time lived in current city (years))
9. Dual Income : ( 1 = dual income, 0 = other)
10. Minors : ( 1 = children under 18 in house, 0 = other)
11. Own : (1 = own residence, 0 = other)
12. House : (1 = residence is single- family house, 0 = other)
13. White : ( 1 = white, 0 = other)
14. English : ( 1 = English is the primary language , 0 = other)

Target Variable
--
Buy ( 1 = buy, 0 = other)

Train Test Split
--- 
Split 80% of the data into training set while 20% of the data to test set.

Fit the model into a logistic regression 
--
Evaluated the model using a confusion matrix

The model predicted the target with about 91% accuracy which is good.

Precision: The model predicted that customers will buy the magazine 69% of the time

Recall or Sensitivity: This will identity 85% of the purchases that customers made. 

AUC score for the case is 0.94 which represents good classifer.
