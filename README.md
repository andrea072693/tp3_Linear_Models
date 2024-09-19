# TP3: Predicting Ozone Concentration Using Multiple Linear Regression  
*Master 1 in Modelisation Statistique Project*  
Université Franche-Comté, Besançon (2022–2023)  

## **Project Overview**  
This project focused on building and validating **multiple linear regression models** to predict the maximum daily ozone concentration using the Ozone dataset. The predictors included environmental variables such as temperature, cloud cover, wind speed, and ozone concentration from the previous day. The analysis involved checking model assumptions, detecting influential data points, and applying model selection techniques to identify the best-performing model.

### **Key Objectives**:
1. **Model Assumptions**: Investigated linear regression assumptions, such as linearity, normality, and homoscedasticity.
2. **Influential Points**: Detected and managed influential data points that could distort model performance.
3. **Model Selection**: Applied selection techniques like **AIC**, **BIC**, and **Adjusted \(R^2\)** to choose the most effective model.
4. **Cross-Validation**: Implemented cross-validation techniques to assess model performance and generalization capability.

## **Project Files**:
- `TP3HURTADOAndrea.Rmd`: R Markdown file containing the full analysis and code.
- `index.html`: Rendered HTML report showing results of the analysis.

## **R Packages Used**:
- `lm()`: For building linear regression models.
- `corrplot`: For visualizing correlation between variables.
- `leaps`: For model selection based on AIC, BIC, and adjusted \(R^2\).


