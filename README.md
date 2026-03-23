# Bootstrap Analysis of Sampling Distributions in R

This project explores the bootstrap as a method for estimating sampling distributions and estimator bias.

Using R I generated bootstrap resamples from a gamma-distributed sample and analyzed the behavior of two estimators: the sample mean and the sample median. The bootstrap distribution of the sample mean was also compared to its theoretical sampling distribution.

## Objectives

* Estimate bootstrap sampling distributions for the mean and median
* Evaluate bootstrap bias for each estimator
* Compare empirical bootstrap results with a known theoretical distribution
* Interpret how skewness affects estimator variability

## Tools Used

* R
* R Markdown
* Statistical simulation
* Bootstrap methods

## Methods

* Generated a random sample of size 16 from a Gamma distribution
* Performed 100,000 bootstrap resamples with replacement
* Calculated bootstrap estimates of the mean and median
* Estimated bootstrap bias for each estimator
* Compared the bootstrap distribution of the sample mean with the theoretical Gamma sampling distribution

## Key Findings

* The bootstrap distribution of the sample mean closely matches the theoretical sampling distribution.
* The sample mean shows very little estimated bootstrap bias.
* The bootstrap distribution of the sample median is more irregular and right-skewed.
* The median shows greater sampling variability when data come from a skewed population.

## Files

* [Source Analysis (R)](bootstrap_analysis.Rmd)
* [Rendered Report (PDF)](bootstrap_analysis.pdf)
