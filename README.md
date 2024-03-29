# CUSTOMER-SEGMENTATION-UNSUPERVISED-ML-


Customer-Segmentation

Problem Description: In this project, our task is to group the customers in different clusters based on their characteristics. For this, we have a data of 200 mall customers. For each customer, we have the following features:
Customer ID, Age, Gender, Annual Income (k$), Spending Score (1-100)

Customer-Segmentation information:

Also known as market segmentation, customer segmentation is the division of potential customers in a given market into discrete groups. That division is based on customers having similar:

Needs (i.e., so a single whole product can satisfy them) Buying characteristics (i.e., responses to messaging, marketing channels, and sales channels, that a single go-to-market approach can be used to sell to them competitively and economically) There are three main approaches to market segmentation:

A priori segmentation, the simplest approach, uses a classification scheme based on publicly available characteristics—such as industry and company size—to create distinct groups of customers within a market. However, a priori market segmentation may not always be valid since companies in the same industry and of the same size may have very different needs.

Needs-based segmentation is based on differentiated, validated drivers (needs) that customers express for a specific product or service being offered. The needs are discovered and verified through primary market research, and segments are demarcated based on those different needs rather than characteristics such as industry or company size.

Value-based segmentation differentiates customers by their economic value, grouping customers with the same value level into individual segments that can be distinctly targeted.

What is the business use case of project?

Customer segmentation has a lot of potential benefits. It helps a company to develop an effective strategy for targeting its customers. This has a direct impact on the entire product development cycle, the budget management practices, and the plan for delivering targeted promotional content to customers.

What is the potential impact of project? Customer segmentation can have a great effect on customer management in that, by dividing customers into different groups that share similar needs, the company can market to each group differently and focus on what each kind of customer needs at any given moment.

HOW you approached the problem statement? This study started with importing dataset, analyzing dataset after this I have done preprocessing, checked for the null values as our dataset contains many null values in Customer id feature and we have to segment the customers, without customer id we are unable to segment customers therefore removed all the rows without Customer id.

After that did some exploratory data analysis (EDA) and came to know about top customers, Worst customers, periodical purchasing stats, most revenue generated weekdays, purchase stats of country, top and lease purchasing country, top sold product, most revenue generated product, Customer stats, etc.

After that did some feature engineering to build the RFM model (recency, frequency and monetary value) . I have extracted and analyzed RFM scores then created customer segments in 3 categories: bronze, silver and gold.

Then did data preprocessing for clustering with the help of log transformation, reduced Skewness of data, then scaled data. After scaling extracted Silhouette Score Based on the inertia and silhouette score, I got to know that the optimal number of clusters is 3.

Then implemented Kmeans clustering and plotted different graphs to visualize clusters
