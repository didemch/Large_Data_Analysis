# Statistical analysis and visual explanation of large climate data


**Exploring statistical methods and principles, with focus on those suitable for non- linear, spatio-temporal autocorrelated data and unsupervised machine learning tools, to effectively extract quantitative information from large climate and earth system science observational and model data.**

*[PROJECT 1: DJF Rainfall Trend Analysis in Los Angeles](https://github.com/didemch/Large_Data_Analysis/blob/main/MK%2C%20MMK%2C%20Vogelsang.ipynb)*

Overview: This project analyzes the trend of DJF (December-January-February) rainfall data in Los Angeles from 1980 to 2018. The goal is to determine if there's a significant trend in the data and if so, whether it is positive or negative. The project explores different trend tests and evaluates their suitability for this dataset.

- Question 1: Mann-Kendall Trend Test
-- Test: A non-parametric Mann-Kendall test was conducted to evaluate the trend in the rainfall data.
-- Results: The test yielded an S statistic and variance, allowing for a Z statistic calculation.
-- Conclusion: The Z statistic and p-value indicated that there was no significant trend in the data.

- Question 2: Modified Mann-Kendall Trend Test
-- Test: A modified Mann-Kendall test, incorporating the Yue-Wang 2004 correction for serial correlation, was applied.
-- Results: The test yielded a significant downward trend, with the Z statistic indicating statistical significance.
-- Conclusion: The test's results indicated a significant negative trend in the rainfall data.

- Question 3: Vogelsang Trend Test
-- Test: The Vogelsang trend test was conducted using robust covariance adjustments.
-- Results: The test produced a linear model slope and statistical significance levels.
-- Conclusion: The slope was insignificant at all levels, indicating no significant trend in the data.

Comparison: MMK vs. Vogelsang: Both tests address autocorrelation. The MMK test is non-parametric and handles serial correlation, while the Vogelsang test assumes a degree of normality and is more suited for linear models.
Autocorrelation and Distribution: The data's low autocorrelation and gamma distribution support the MMK test as a more comprehensive choice for this analysis.
Conclusion:The project concludes that the Modified Mann-Kendall test is a suitable choice for this dataset due to its non-parametric nature and ability to handle autocorrelation effectively.


