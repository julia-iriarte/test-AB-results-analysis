# Analyze A/B Test Results

## Introduction

A/B tests are very commonly performed by data analysts and data scientists.

For this project from Udacity's Nanodegree *Data Analyst*, I will be working to understand the results of an A/B test run by an e-commerce website. This company has developed a new web page in order to try and increase the number of users who "convert", meaning the number of users who decide to pay for the company's product. My goal here was to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

Here I use statistical techniques to answer questions about the data and report my conclusions and recommendations.

This project was already reviewed and met all the specifications. 


## Project Overview: Analyze A/B Test Results

This Project was divided into 3 parts:

### Part I - Probability
First we have a look into the dataset and do some cleaning to be sure that we only compute rows where group and ab_page were correctly aligned. Finaly we compute statistics to find out the probabilities of converting given the old or the new page.

### Part II - A/B Test
Subsequently, a hypothesis test was performed under the assumption that the previous page was superior, unless the new page could conclusively demonstrate superiority at a 5% Type I error rate. Bootstrapping was employed, and the sampling distributions for both pages were established. The results of the conversion rates for both pages were then determined through the calculation of p-values.

### Part III - Regression
A logistic regression analysis was then carried out to validate the findings from earlier stages. The null and alternative hypotheses associated with this regression model were stated and verified using the statsmodel tool. Finally we added a new variable (countries where users live) and tried some more regression models.

## Conclusions
According to the statistical tests performed, including the Z-test, the logistic regression model, and the observed difference, the results indicate that there is no significant difference in the conversion rate between the new and old page. Therefore, the null hypothesis cannot be rejected. Based on these findings, it is recommended that the e-commerce company maintain the use of the old page, as this will result in a reduction of time and expenses associated with developing a new page.

#### What you may know about this Jupyter Notebook
The following libraries need to be installed:
- Numpy
- Pandas
- Matplotlib
- Statsmodels

This is a project from Udacity website for the *Data Analyst* Nanodegree. Part of the guide text was provided by Udacity.