# UberX's Impact on Public Transit: Complement or Substitute?

**Location**: Los Angeles, California  
**Role**: Analyst | Machine Learning & Big Data (Python)  
**Duration**: March 2024 – June 2024  

---

## Project Overview  

This project explores whether UberX serves as a complement or substitute for public transit. Drawing inspiration from the research detailed in [this paper](https://www.sciencedirect.com/science/article/abs/pii/S0094119018300731#:~:text=We%20find%20that%20Uber%20is,and%20for%20smaller%20transit%20agencies), our analysis leverages advanced regression techniques and feature engineering to revisit these dynamics. Our findings provide a nuanced perspective, challenging earlier assumptions about ride-sharing's role in the urban mobility ecosystem.

---

## Key Findings  

- **Positive Correlation**: The analysis reveals a positive relationship between UberX availability and public transit usage, in contrast to prior studies suggesting a substitution effect.  
- **Enhanced Model Robustness**: Through fixed effects, time effects, interaction terms, and polynomial features, the analysis captures intricate patterns often overlooked in similar research.

---

## Methodology  

### Regression Techniques  

- **Models Used**:  
  - Ordinary Least Squares (OLS)  
  - Panel OLS  
  - Lasso Regression  
  - Double Lasso Regression  
- **Feature Selection**: Cross-validation was used to reduce overfitting and improve generalization.  

### Advanced Features and Adjustments  

- **Fixed and Time Effects**: Controlled for geographic and temporal variations.  
- **Interaction Terms**: Captured complex relationships among variables.  
- **Polynomial Features**: Accounted for non-linear patterns, enhancing model flexibility.

---

## Tools and Technologies  

- **Programming Language**: Python  
- **Libraries**: `pandas`, `numpy`, `statsmodels`, `scikit-learn`  
- **Statistical Techniques**: Advanced regression models with cross-validation  
- **Data Engineering**: Feature engineering for fixed and time effects, polynomial features, and interactions

---

## Repository Contents  

- **Data Processing**: Scripts for cleaning, preprocessing, and feature engineering.  
- **Regression Analysis**: Implementation of OLS, Panel OLS, Lasso, and Double Lasso models.  
- **Results Interpretation**: Notebooks showcasing exploratory analysis, model outputs, and visualizations.  
- **Comparison with Source Study**: Analysis contrasting findings with the referenced [paper](https://www.sciencedirect.com/science/article/abs/pii/S0094119018300731#:~:text=We%20find%20that%20Uber%20is,and%20for%20smaller%20transit%20agencies).

