DSCI 552 – Homework 3

Name: Nithya Prasasthani Eeri
USC ID: 9182042369
GitHub Username: Nithya0605-eeri

Homework Overview

This repository contains my solutions for DSCI 552 Homework 3.

Question 1: Time Series Classification – Feature Creation/Extraction

I used the AReM dataset from the UCI Machine Learning Repository to analyze human activities using time-series sensor data.

The work includes:

* Preparing training and test datasets.
* Extracting 42 time-domain features from 88 instances.
* Calculating standard deviations and 90% bootstrap confidence intervals.
* Selecting three important time-domain features for classification.

Question 2: ISLR 3.7.4

This section contains written answers comparing linear and cubic regression models using training and test residual sum of squares (RSS).

Repository Structure

* data/AReM/ – Activity recognition dataset.
* notebook/Eeri_NithyaPrasasthani_HW3.ipynb – Homework solutions and executed outputs.
* requirements.txt – Python dependencies.

Requirements

The notebook uses Python 3 with NumPy and pandas.

Install the dependencies using:

pip install -r requirements.txt

Running the Notebook

1. Clone or download this repository.
2. Open the notebook in Jupyter Notebook.
3. Make sure the AReM dataset is available in data/AReM/.
4. Run the notebook cells in order.

References

* UCI Machine Learning Repository – AReM Dataset.
* An Introduction to Statistical Learning – Chapter 3, Exercise 7.4.
