# Association Rule Mining on Online Transactional Dataset

Online retail company XYZ sells various products and looking to increase its revenue by promoting cross-selling (i.e. selling related or complementary items) opportunities to its customers. 
Through association rule mining, the analytics team can uncover hidden patterns to determine which products should be recommended when certain products are bought by users. This is a sample dataset hence, has only 2k unique transactions.

The notebook has the following flow:

1. Data Check - Generating stats about dataset and basic EDA to gauge cleanliness of data
2. Identifying frequent itemsets using Apriori package. Here, the support value is very low at 0.02 ( owing to small sample size)
3. Finding association rules using minimum confidence level of 0.2
4. Visualizing lift, support and confidence metric to assess rules performance
5. Interpretation of results and generating recommendations.
6. Limitations of this analysis
