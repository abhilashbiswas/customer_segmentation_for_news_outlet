# customer_segmentation_for_news_outlet
Using Deloitte Digital Democracy survey data (2011) to analyze potential market segmentation for a upcoming news outlet

## How to run the analysis:

- Step 1: git clone https://github.com/abhilashbiswas/customer_segmentation_for_news_outlet.git
- Step 2: Go the the cloned local folder, run market_segmentation_analysis.ipynb

### Overview:

Market segmentation is an important topic for businesses looking to launch new products and services. Using a hypothetical scenario of a news media outlet that is looking to launch in the near future, we use the Deloitte Digital Democracy survey data of 2011 to identify different customer segments that the company should target. We use several methods to identify interesting clusters of customer segments having distinct attitudes and behaviors towards subscriptions, media habits, purchases etc. In general, our focus of this project is to identify customers/segments that may be more willing to purchase a subscription for this news outlet.

#### Topic area 1: Market segmentation using unsupervised learning
Market segmentation is typically done on traditional demographic elements such as age, gender, location etc. In addition to exploring these categories, we apply KMeans unsupervised clustering algorithm to identify latent dimensions in the dataset that can provide important insights on different customer segments. 

#### Topic area 2: Supervised learning
Can we predict people who are more likely to purchase a subscription for the news agency? Using the variable 'willing to pay more news subscription without ads', we train a Random Forest classification model on the features available in the Deloitte digital democracy survey to answer this prediction question and perform some analysis on the outputs
