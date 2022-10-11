# We Rate Dog (Udacity Twitter Data Analysis)
## by PRINCE BOADI


## Dataset

 The dataset that I will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as __WeRateDogs__. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. Datasets used:
 
 - `twitter-archived-enhanced.csv`
 - `image_predictions.tsv`
 - `tweet_json.txt`


## Data Wrangling

For this analysis, data was gathered from three different sources as stated earlier. The datasets were assessed both visually and programatically to uncover any `Quality` or `Tidiness` issue that needs to be cleaned. The `Quality` and `Tidiness` issues observed were thoroughly investigated and cleaned. The three (3) datasets were merged to provide a holistic analysis.
Lastly, the merged dataset was further analysed using Microsoft Power BI to build an interactive dashboard to provide other insights to the dataset. The interative dashbaord is embed in the jupyter notebook file.

After the wrangle process, in order to understand the dataset and reveal its hidden insights through visualizations, I asked the following questions:
- Is there a correlation among rating, favorite count and retweet count?
- Which dog image received the highest favorite count and which dog type is it?
- Which dog image received the highest retweet count and which dog type is it?
- What do tweeps (raters) say in their tweets?

## Key Insights for Presentation

1. Golden Retriever, Labrador Retriever and Pembroke are the top 3 most tweeted dogs
2. About 85% of the image predictions were accurate
3. Among the dog stages, pupper is the most tweeted.
4. There is a very strong positive correlation between retweet count and favorite count with a correlation coefficient of 0.91
5. Most tweets are made in the month of November and December
6. Dog image with the highest retweet count is Labrado Retriever (doggo)
7. Dog image with the highest favorite count is Lakeland Terrier (puppo)
8. Golden Retriever, the most correctly predicted dog image, perhaps the most popular
