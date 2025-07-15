

## Project Overview

This repository showcases a simulated case study of ship price estimation for a capesize vessel named **Bet Performer**. 
Using statistical tools in R, the project evaluates how various ship attributes like **Age at Sale**, **Deadweight Tonnage (DWT)**, and the **Capesize Index** influence the final market price.

---

## Key Objectives

- Apply **single-variable** and **multi-variable linear regression** techniques.
- Identify most influential predictors of ship pricing.
- Use statistical tools like **correlation matrix**, **regression coefficients**, and **R² values** to evaluate the model.
- Estimate Bet Performer's price within a standard error margin.

---

## Data & Methods

- Sample of **48 comparable ship transactions**.
- Filtered using **Euclidean Distance**, **Z-Scores**, and **Empirical Rule**.
- Applied multiple regression in R:
  ```
  Price = 44.22 + (-4.54 × Age) + (0.24 × DWT) + (0.0072 × Capesize Index)
  ```
- **Adjusted R²: 0.915** → Model explains 91.5% of the price variation.

---

## Key Insights

- **Age at Sale** has a strong negative impact on price.
- **DWT** and **Capesize Index** positively influence pricing.
- Final estimated price: **$132.79 million** (±9.88M).

---

## Visuals Included

- Correlation matrix
  
![Correlation Values](https://github.com/user-attachments/assets/434e3532-97eb-4fa5-b35b-6593bf424fb5)

 
- Regression plots: Age vs Price, DWT vs Price, Capesize Index vs Price

![Age~Price](https://github.com/user-attachments/assets/fa27ca8e-20a7-4b7e-9aa5-b3e4de457d46)
![Capesize~Price](https://github.com/user-attachments/assets/e632f81f-3979-4509-9068-31595b1a6b88)
![DWT~Price](https://github.com/user-attachments/assets/31c54b79-a41a-4f54-8143-0978c014a683)


- Residual statistics and coefficient output
![Corplot](https://github.com/user-attachments/assets/1813ce43-ff34-4f23-9aa4-04a2b84bde6a)
![Model Statistics](https://github.com/user-attachments/assets/22f0c304-d1c9-4f20-b829-ef45dc1b9e03)

  
- Price distribution histogram
![Price Histogram](https://github.com/user-attachments/assets/bc27d24a-37e6-4990-a393-85545ffbaaf4)



## Commands Used

- **R Programming**
- `ggplot2`, `lm()`, `cor()`, `hist()`, and base R plotting
- Statistical techniques: Euclidean distance, Z-score filtering

