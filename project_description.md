
##  Creating Customer Segments- PCA, GMM and K_Means Clustering. 

#### Unsupervised Learning

## Project Overview

Application of unsupervised learning techniques on product spending data collected for customers of a wholesale distributor in Lisbon, Portugal to identify customer segments hidden in the data. 
From Data exploration to selecting a small subset to sample and determine if any product categories highly correlate with one another. Afterwards, I have preprocessed the data by scaling each product category and then identifying (and removing) unwanted outliers. With the good, clean customer spending data, applied PCA transformations to the data and implement clustering algorithms to segment the transformed customer data. Then compared the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes.

## Project Highlights
developed conclusions for a potential client on a real-world dataset. Many companies today collect vast amounts of data on customers and clientele, and have a strong desire to understand the meaningful relationships hidden in their customer base. Being equipped with this information can assist a company engineer future products and services that best satisfy the demands or needs of their customers.

Learning Experience:

- How to apply preprocessing techniques such as feature scaling and outlier detection.
- How to interpret data points that have been scaled, transformed, or reduced from PCA.
- How to analyze PCA dimensions and construct a new feature space.
- How to optimally cluster a set of data to find hidden patterns in a dataset.
- How to assess information given by cluster data and use it in a meaningful way.

## Description
A wholesale distributor recently tested a change to their delivery method for some customers, by moving from a morning delivery service five days a week to a cheaper evening delivery service three days a week. Initial testing did not discover any significant unsatisfactory results, so they implemented the cheaper option for all customers. Almost immediately, the distributor began getting complaints about the delivery service change and customers were canceling deliveries, losing the distributor more money than what was being saved. I've been hired by the wholesale distributor to find what types of customers they have to help them make better, more informed business decisions in the future. I have employed ****unsupervised learning techniques**** to see if any similarities exist between customers, and how to best segment customers into distinct categories.

## Software and Libraries Used:

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
-[seaborn](https://seaborn.pydata.org/)
-[Jupyter Notebook](http://ipython.org/notebook.html).



This project contains three files:

- `customer_segments.ipynb`: This is the main file where I have  performed my work. 
- `customers.csv`: The project dataset. You'll load this data in the notebook.
- `visuals.py`: This Python script provides supplementary visualizations for the project. Just to differentiate visual section and model analyses. 



