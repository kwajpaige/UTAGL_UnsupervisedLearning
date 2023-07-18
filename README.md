# UTAGL_UnsupervisedLearning
In real life, it is easier to get unlabeled data than labeled data. This adds to the tedious task of manual intervention to use any prediction methodology. Unsupervised Learning groups data points based on similarity of data points. The purpose of this project is to employ the most commonly used Unsupervised learning methodologies like K-means Clustering, Hierarchical Clustering, and Dimensionality Reduction.

## Background
AllLife Bank wants to focus on its credit card customer base in the next financial year. They have been advised by their marketing research team, that the penetration in the market can be improved. Based on this input, the Marketing team proposes to run personalized campaigns to target new customers as well as upsell to existing customers. Another insight from the market research was that the customers perceive the support services of the back poorly. Based on this, the Operations team wants to upgrade the service delivery model, to ensure that customer queries are resolved faster.

## Data Dictionary
- Sl_No: Primary key of the records
- Customer Key: Customer identification number
- Average Credit Limit: Average credit limit of each customer for all credit cards
- Total credit cards: Total number of credit cards possessed by the customer
- Total visits bank: Total number of visits that customer made (yearly) personally to the bank
- Total visits online: Total number of visits or online logins made by the customer (yearly)
- Total calls made: Total number of calls made by the customer to the bank or its customer service department (yearly)

## Objective
Identify different segments in the existing customer, based on their spending patterns as well as past interaction with the bank, using clustering algorithms, and provide recommendations to the bank on how to better market to and service these customers.

## Insights and Recommendations
Cluster 0: 47 members
- Median: Average Credit limit approx 91000;
- Median: Total Credit cards: 9
- Median: Total vistis bank: 1
- Median: Total vistis online:8
- Median: total calls made: 1

Cluster 1: 379 members
- Median: Average Credit limit approx 32000;
- Median: Total Credit cards: 6
- Median: Total vistis bank: 3
- Median: Total vistis online:1
- Median: total calls made: 2

Cluster 2: 221 members
- Median: Average Credit limit approx 12000;
- Median: Total Credit cards: 2
- Median: Total vistis bank: 1
- Median: Total vistis online:4
- Median: total calls made: 9

Cluster 0 represents the small number of customers with multiple credit cards and higher average credit limits. these customers appear to monitor their credit online and require very little support
Cluster 1 represent customers with fewer credit cards than those customers in cluster 0; these customers vist the bank more than onlineand also need little support
Cluster 2 customers have the fewest number of credit cards and the lowest average credit limit; these customers require more support and do not visit the bank often

Recommendations:
- Build more models using a variety of hierarchical techniques to seek to improve the hierarchical clustering model
- Build models using data set with outliers replaced (current models are using data set with outliers not replaced)
How can we improve market penetration?
- Customers in cluster 2 might be new customers who have limited credit options and limited experience with banking; educate these customers on the advantages of online banking and icreasing credit limits in order to move these customers into cluster 1, the cluster with the highest number of customers and minimal support needs
How should we personalize our marketing campaigns to new customers? to existing customers?
- New Customers: Cluster 2 customers are likely new custoerms and appear to prefer usisng online banking. To target new custoemrs, provide optimal online services and increase the number of knowledgeable support personnel to advise with their banking needs
- Existing customers: Seek to move custoemrs from one cluster to another (cluster 2 to 1 to 0) by selling more credit services and increasing support options for these customers What steps should we take to upgrade the service delivery models, to "ensure that customer queries are resolved faster?'
- Customers with lower average credit limits and total credit cards are more likely to require support; they also visit online more than in person; to deliver better service, ensure that support personnel are easily accessible online and are trained to advise customers on increasing their credit cards and credit limits; Provide more onine support options to clients, such as chatbots and FAQs and online documentation
