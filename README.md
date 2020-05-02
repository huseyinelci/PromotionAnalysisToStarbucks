# Starbucks Promotion Analysis
The data for this exercise consists of about 120,000 data points split in a 2:1 ratio among training and test files. In the experiment simulated by the data, an advertising promotion was tested to see if it would bring more customers to purchase a specific product priced at $10. Since it costs the company 0.15 to send out each promotion, it would be best to limit that promotion only to those that are most receptive to the promotion. Each data point includes one column indicating whether or not an individual was sent a promotion for the product, and one column indicating whether or not that individual eventually purchased that product.

## Table of Contents
1. [Project Motivation](#pd) <br>
2. [Files](#an)<br>
3. [Results](#rs)<br>
4. [Build with](#bw)<br>
5. [Credits and Acknowledgements](#ca)<br>

<a name="pd"></a>
## 1. Project Motivation

The objective of this project is to understand customers behavior. We'll try to analyze different attributes of Starbucks customers,
analyze their behavior and understand how they respond to promotions. Idea is to analyze if there is a group of customer which responds differently to a kind of promotion, check the drivers which make a particular offer click compared to other. This will help us design an effective promotion strategy

In this particular repository try to cluster the customer based on their behavior to certain promotions and provide recomendation on what other promotion shall be offered to the respective customers.

<a name="an"></a>
## 2. Files
Inside Starbucks folder, there are :

- Jupyter notebook that illustrate the analysis, comments, and rationale

- Data folder inside Starbukcs contained these three files:
  - portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
  - profile.json - demographic data for each customer
  - transcript.json - records for transactions, offers received, offers viewed, and offers completed
  


<a name="rs"></a>
## 3. Results
KMeans is used to build the cluster. As a result,  4 group of customers with a quite differentiated characteristics are identified,

- cluster 0: Low income group cluster, they typically respond to low difficulty offers. Overall their completion rate is lowest

- cluster 1: High Income group, Behavior to BOGO offer is different than discounts, Starbucks could target them more with BOGO offers as their completion rate for these type of offer is significantly higher

- cluster 2: Highest Income group, respond to all kinds of promotions similarly. Starbucks can cut down on the amount of money they lose by better designing their offers to this cluster. Also, lower #offers can also help, as this group is already highly engaged.

- cluster 3: Middle income group, doesn't really respond good to offers with higher difficulty.
![alt text](https://github.com/manish0013/starbucks_promo_analysis/blob/master/personal_transactions_clusters.png)

<a name="bw"></a>
## 4. Build with
- Python 3+
- Machine Learning Libraries: NumPy, Pandas, SciKit Learn

<a name="ca"></a>
## 5. Credits and Acknowledgements
- **Udacity** for providing such a complete Data Science Nanodegree Program
- **Starbucks** for providing the datasets



