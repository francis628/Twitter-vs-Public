# Twitter-vs-Public

Slides: [Twitter vs Public Deck](https://github.com/francis628/Twitter-vs-Public/blob/main/Twitter%20vs%20Public%20Deck.pptx)

[Tableau Dashboard](https://public.tableau.com/views/TwittervsPublic/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

This work seeks to provide evidence on the differences in sentiment (Positive/Negative) between perceptions shared on twitter versus perceptions held by the public at large. Specifically, this analysis will focus on compairing sentiment of famous brands. The public's sentiment is approximated by brand specific survey data collected by YouGov. Whereas for Twitter data, tweets responding to these brands will be scraped and classified as either positive or negative. 

Both the survey and Twitter data were scraped using the Selenium library. Selenium provides scraping cababilities for unstructured web data, unlike other scraping programs that require data to be in a tabular format.

Flair, a pretrained NLP model, was used to classify tweet data as positive or negative. To evaluate preformance of Flair, the model classified 20,000 Amazon product reviews with ratings of one or five stars.

The results of the analysis are available in [Twitter vs Public Deck](https://github.com/francis628/Twitter-vs-Public/blob/main/Twitter%20vs%20Public%20Deck.pptx)
Jupyter notebook with additional documentation and code used to execute this project is located in [Twitter_vs_Public.ipynb](https://github.com/francis628/Twitter-vs-Public/blob/main/Twitter_vs_Public.ipynb)

Additional files for this project include:
hand collected corporate twitter accounts: famous_brands_with_twitter.csv
list of Amazon product reviews: kcore_5.json, file is too large to post but is available at http://jmcauley.ucsd.edu/data/amazon/index.html

