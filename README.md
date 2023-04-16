# Marketing Campaign Analysis for Food Company
## Introduction, Business Insights, and Dataset Source
The food company is planning to launch a direct marketing campaign with the goal of maximizing profits. In a pilot campaign with 2,240 customers, those who purchased the offer were labeled as successful. The cost of the pilot campaign was 6,720MU and the revenue from customers who accepted the offer was 3,674MU, resulting in a loss of 3,046MU and a success rate of 15%.

The team's goal is to create a model that predicts customer behavior and apply it to the rest of the customer base. Additionally, the Chief Marketing Officer wants to identify the characteristics of customers who are likely to purchase the offer, in addition to maximizing campaign profits. The plan includes data exploration, segmentation, and building a classification model.

The dataset for this analysis was sourced from Kaggle (https://www.kaggle.com/datasets/jackdaoud/marketing-data).

## Research Question
The research question for this project is: Can we predict customer behavior and identify the characteristics of customers who are likely to purchase the offer in the direct marketing campaign in order to maximize profits?

## Results
Using a Random Forest model, we were able to predict 72% of customers who responded to the marketing campaign out of all the customers predicted to respond. Overall, the model had a high level of accuracy in predicting customer responses to the marketing campaign.

Based on the data analyzed, we recommend targeting middle class customers with incomes between 53,413 and 106,827 for higher success rates in marketing campaigns. Additionally, utilizing recent purchases as a targeting factor and targeting loyal and long-lasting customers may also lead to higher success rates. Younger customers, particularly those with an age of 25 and lower, and customers with no dependencies should also be targeted for higher success rates. To increase success, focus on targeting customers with higher spending, particularly those with total purchases of more than 2,000. Utilizing web-based and catalog-based marketing campaigns may also lead to higher success rates, as these types of purchases show a strong correlation with campaign success. In terms of customer demographics, consider targeting divorced, single, and widow customers as they tend to respond well to campaigns. It is also recommended to target customers who responded well to previous campaigns, particularly the first, second, third, and fifth campaigns. On the other hand, it may be wise to avoid targeting married customers and those with education levels of "Basic" or "2nd Cycle", as they tend to not respond well to campaigns.

## Statistical Conclusion
Based on the analysis using ANOVA and chi-square tests, several predictors such as Income, Recency, Customer Days, Dependencies, MntTotal, and NumWebPurchases showed a significant difference in the target (i.e., successful purchase) based on the predictor. This indicates that these predictors are important in predicting customer behavior and can be used to identify the characteristics of customers who are likely to purchase the offer in the direct marketing campaign. However, predictors such as NumDealsPurchases did not show a significant difference in the target based on the predictor. Further analysis and modeling are needed to determine the best predictors for the classification model.

## Further Research
Based on the findings of this study, further research can be conducted in the following areas:

1. Refining the classification model: The team can further explore and evaluate different machine learning algorithms, such as logistic regression, decision trees, or random forests, to build a predictive model with higher accuracy and better interpretability.
2. Feature engineering: The team can explore additional features or transform existing features to create more informative predictors for the classification model. For example, creating new features based on customer demographics, purchasing patterns, or engagement with previous marketing campaigns may improve the accuracy of the model.
3. Customer segmentation: The team can conduct further analysis to segment customers based on their behavior and characteristics, and develop targeted marketing strategies for each segment. This can help optimize the marketing campaign by tailoring the offer and messaging to different customer segments.
4. Cost-benefit analysis: The team can conduct a cost-benefit analysis to determine the potential return on investment (ROI) of the direct marketing campaign. This can help the company make informed decisions about resource allocation and budgeting for the campaign, and assess the overall profitability of the campaign.
