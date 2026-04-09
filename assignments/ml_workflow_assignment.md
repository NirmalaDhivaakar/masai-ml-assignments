# ML Workflow Assignment

## Task 1

### Label (Target Variable)

repeat_purchase_flag

This column is the label because it represents the outcome we want the model to predict — whether the customer makes a repeat purchase within 30 days (1 = yes, 0 = no).

### Feature that Introduces Data Leakage

discount_used_on_repeat_order

This column introduces data leakage because it contains information about the repeat purchase itself, which would not be available at the time of prediction and therefore indirectly reveals the target outcome.

---

## Task 2

### 1. Establish a Baseline Model

Before training a complex model like Gradient Boosting, it is important to create a simple baseline model (for example predicting the majority class). This helps determine whether the advanced model actually improves performance compared to a simple benchmark.

### 2. Perform Data Exploration and Data Quality Checks

Exploratory Data Analysis (EDA) should be done first to understand the dataset, identify missing values, detect possible data leakage, and verify that the features are meaningful before training a complex model.