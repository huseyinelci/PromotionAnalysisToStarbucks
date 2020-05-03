# Starbucks Promotion Analysis
The data for this exercise consists of about 120,000 data points split in a 2:1 ratio among training and test files. In the experiment simulated by the data, an advertising promotion was tested to see if it would bring more customers to purchase a specific product priced at $10. Since it costs the company 0.15 to send out each promotion, it would be best to limit that promotion only to those that are most receptive to the promotion. Each data point includes one column indicating whether or not an individual was sent a promotion for the product, and one column indicating whether or not that individual eventually purchased that product.

## Table of Contents
1. [Project Motivation](#1) <br>
2. [Installation](#2)<br>
3. [Files](#3)<br>
4. [Results](#4)<br>
5. [Credits and Acknowledgements](#ca)<br>

<a name="1"></a>
## 1. Project Motivation

The objective of this project is to understand customers behavior. We'll try to analyze different attributes of Starbucks customers,
analyze their behavior and understand how they respond to promotions. Idea is to analyze if there is a group of customer which responds differently to a kind of promotion, check the drivers which make a particular offer click compared to other. This will help us design an effective promotion strategy.

<a name="2"></a>
## 2. Installation

The necessary libraries to run this project, along with Python 3.+:
* numpy
* pandas
* statsmodels
* sklearn
* scipy
* matplotlib
* seaborn
* imblearn


<a name="3"></a>
## 3. Files
Inside Starbucks folder, there are :

- Data folder inside Starbukcs contained these three files:
  - data/training.csv : The training data provided by Starbucks
  - data/test.csv : The test data provided by Starbucks that Udacity uses in their scoring script
  - StarbucksPromotionAnalys.ipynb : A Jupyter notebook which contains the repoducible analysis on the Starbucks dataset
  - test_results.py : A scoring script provided by Udacity to determine the IRR and NIR of the promotional strategy on the test dataset



<a name="4"></a>
## 4. Results
In this analysis, the main takeaways:
- Using several statistical tests we have seen the effect of promotion on both metrics of interest.
- Using a decision tree classifier (built with scikit-learn), we devised a promotional. 


<a name="5"></a>
## 5. Credits and Acknowledgements
- **Udacity** for providing such a complete Data Science Nanodegree Program
- **Starbucks** for providing the datasets


## Post to Medium
https://medium.com/@huseyinelci2000/the-importance-of-data-visualization-bba9fcaa67a3

## Github Link
https://github.com/huseyinelci2000/PromotionAnalysisToStarbucks

