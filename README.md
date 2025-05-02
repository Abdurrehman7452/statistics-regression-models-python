# Statistical Analysis with Python

This repository contains solutions to a series of statistical analysis problems implemented in Python. It covers core concepts such as standard error, confidence intervals, hypothesis testing, linear regression, and data analysis using real-world datasets.

---

## 📘 Table of Contents

- [Question 1: Confidence Interval for Mean]
- [Question 2: Confidence Interval for Proportion]
- [Question 3: BMI Confidence Interval from Dataset]
- [Question 4: Real Estate Linear Regression]
- [Question 5: One-Sample Proportion Z-Test]
- [Question 6: One-Sample Z-Test for Mean]
- [Question 7: Two-Sample T-Test for BMI]

---

## 📊 Question 1: Confidence Interval for Mean

- Calculates the Standard Error (SE) and constructs a 95% confidence interval for the sample mean using a known standard deviation.
- Manual computation of margin of error and confidence bounds.

## 📈 Question 2: Confidence Interval for Proportion

- Computes SE for proportions and calculates a 95% confidence interval.
- Uses both manual formula and built-in libraries to verify the result.

## 📉 Question 3: BMI Confidence Interval from Dataset

- Loads a dataset and computes mean, standard deviation, and SE for the "BMI" feature.
- Constructs a 95% confidence interval for the population mean BMI using the z-distribution.

## 🏠 Question 4: Real Estate Linear Regression

- Loads real estate data and performs:
  - Data visualization (scatter plot).
  - Data normalization.
  - Linear regression using gradient descent.
  - Risk (loss) function implementation.
  - Plotting the regression model.
  - Outputting the learned coefficients.

## ⚡ Question 5: One-Sample Proportion Z-Test

- Tests whether more than 65% of users report an energy boost from a drink.
- Performs a one-tailed z-test using `statsmodels`.

## 💵 Question 6: One-Sample Z-Test for Mean

- Uses a dataset to test whether the average 'percentage expenditure' is below 500.
- Performs a left-tailed z-test using custom code and statistical library tools.

## 👨‍🔬 Question 7: Two-Sample T-Test for BMI

- Tests whether males have significantly higher BMI than females using a dataset.
- Performs a two-sample t-test using `scipy.stats.ttest_ind`.

---

## 📂 Datasets Used

- `Life_Expectancy_Data.csv`
- `Real_Estate_Price.csv`
- `BMIDataset.csv`

---

## ⚙️ Requirements

Install the required Python packages using:

```bash
pip install pandas numpy matplotlib scikit-learn scipy statsmodels
```
## 📬 Author
- Muhammad Abdurrehman BS Data Science (NUCES)
- Created as part of a statistics and data analysis project using Python.

