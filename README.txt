1st task: evaluate 9 hypotheses using ICE and RICE approaches.
2nd task: launch adequate AB-test.

I. Data preprocessing - we need the data to be brought to the required types and uniformity, otherwise it is difficult to filter.

II. Hypothesis prioritization on the Ice Rice methods to help managers decide which product hypothesis will hit the team the least but will (probably) bring the most value to the business.

III. Visualize data, pay attention to anomalies. Our task also includes this: to prevent hasty decisions from being made on the basis of superficial data analysis. This is what happens when you just look at charts. Catching mind traps.

IV. Find outliers that affect the result and interpretation of the graphs.

V. We analyze ab-test, the threshold of statistical significance is 0.05. We look at whether we reject the null hypothesis (that groups A and B are equal) or whether there is reason to believe that there is a tangible difference. We clean the data and check what has changed.

VII. We give our vision in [Results of the work] (#concl). We are trying to convince the "decision makers".


=== Recommendations from the analyst and ideas===

I. Choice of product hypothesis.

The use of different methods revealed two solutions that, according to the Impact and Reach indicators, came out in the top 3. There are two that differ in the same parameters. Launching a promotion and adding a block about products cannot be considered unconditionally useful. The promotion will increase purchases, and information blocks will increase audience coverage. Two hypotheses were in the top of both ratings, two more require preparation:

Add product recommendation blocks to your online store website to increase conversion and average order value' is an inexpensive solution.

Add two new traffic acquisition channels, which will allow you to attract 30% more users - a potentially costly solution, before launching, you should optimize landing pages and email collection, as well as see how the buttons work, what is the user's path to purchase. Before applying this solution, we need to conduct at least usability testing.

→ To launch a promotion, we will first need to calculate the unit-economy and choose for whom and what services, goods, we can launch the promotion and in what amount. Consider seasonality, view historical data on the product.

Add product recommendation blocks to the online store website to increase conversion and average order check - this may be needed for retargeting.

II. Data analysis. There are anomalous values ​​in the data. We removed one very large purchase of 1,294,500 rubles on August 13th. A benchmark of 58,000 rubles per order and 4 purchases per unique per day was chosen as a filter for the cost of the order. We see that at the start, the conversion of group B is half a point higher. Then it sags and gives way to the first week of August. Then it goes forward from August 8 to 13, although the graph of the average check shows that since the second week the average check of group B relative to group A has been in drawdown. This happens when, for example, there is a promotion for an accompanying product. The average check will be less, but the hype fuels the conversion, it is high.

Since we relied on cumulative and relative graphs, we can only mark dates with extreme values. But anomalies in the cumulative data affect the results for a long time. In order to rely not on a visual graph, but to draw conclusions based on the data, we had to conduct an ab-test analysis.

Both groups are independent. Threshold 0.05. We measure the statistical difference between groups in order to answer the question: can we consider that the samples are equal or there is a statistically significant difference in them. **Null hypothesis: samples are equal. Alternative: no, they are different, there is a statistically significant difference**. To evaluate the difference, we will measure the relative metric.

III. AV testing We test hypotheses on two types of samples: 100% of users and 99% of users. The fact is that we cannot take into account the most extreme values. Even without obvious outliers, these extreme values ​​affect the results.

Conversions: Based on raw base data, group B does not convert much better than group A, based on the data. Although based on the graph, one could come to a false conclusion. According to the cleaned data, group B converts much better. But: conversion to sales is better in and of itself. But the income is higher or not? The conversion may be higher, but for an inexpensive popular product.

According to the average invoice: according to raw data, B loses to A by 0.016, and according to cleared data, by 0.014. It still ends up making less money.

For business purposes, we recommend abandoning the experiment that was rolled out on group B and moving on to other growth experiments. And also set up retargeting and find a consultant to call "dear" customers, if the product being sold is of regular use.
