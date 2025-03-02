# Deep Learning Challenge

---

## Overview
- The purpose of this challenge is to create a model using machine learning for the fictional nonprofit
- Alphabet Soup, to help select applicants with the best chance of success in their ventures to fund.

## Data Preprocessing

- **What variable(s) are the target(s) for your model?**
  - The target (dependent) variable is the `IS_SUCCESSFUL` column from the dataframe.

- **What variable(s) are the features for your model?**
  - The features (independent variables) are all the other columns except the `IS_SUCCESSFUL` column.

- **What variable(s) should be removed from the input data because they are neither targets nor features?**
  - The `EIN` and `NAME` columns were removed because they are neither targets nor features.
  - In future runs, other columns such as `STATUS`, `SPECIAL_CONSIDERATIONS`, and `ASK_AMT` could also be removed.

---

## Compiling, Training, and Evaluating the Model

- **How many neurons, layers, and activation functions did you select for your neural network model, and why?**
  - The first run had four layers:
    - First layer: 110 units
    - Second layer: 100 units
    - Third layer: 80 units
    - Fourth layer: 1 unit
  - Higher unit numbers were selected to improve model accuracy.
  - More layers were added in subsequent runs for the same reason.

- **Were you able to achieve the target model performance?**
  - No, the target performance of **75%** was not achieved.

- **What steps did you take in your attempts to increase model performance?**
  - Added more layers.
  - Changed the activation function types.
  - Adjusted the number of units in each layer.

---

## Summary

- The average accuracy of the model is **73%** for prediction.
- To improve accuracy:
  - Use a larger dataset with stronger correlations between target variables.
  - Run the model with more iterations.

---
