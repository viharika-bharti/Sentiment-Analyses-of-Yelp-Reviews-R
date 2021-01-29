# Sentiment-Analyses-of-Yelp-Reviews-R

This assignment involves text mining of user-review data and sentiment analyses. It is based on a
collection of reviews and accompanying star ratings from Yelp. A sample of the original dataset (over 4
million review by over a million users for 144K businesses) will be used here, to keep the assignment
task manageable. We will examine the effectiveness of different sentiment ‘dictionaries’, and develop
and evaluate classification models to help predict sentiment polarity (negative, positive).
The star ratings will be used here to indicate the sentiment label. For binary classification, we will need
to convert the 1-5 scale rating values to {positive(1), negative(0)} values.
(More details on the data are available from https://www.yelp.com/dataset)

The data was given in json files. The reviews data file contains the reviews and includes reviewID,
businessID, businessName, the review text, star rating and other attributes. The business data file
contains the businessName, businessID, address, categories (restaurants, beauty and salon, food,
fitness, local services, etc.), various attributes of the business (free wifi, wheelchair access, parking,
smoking allowed, operating hours, … etc). Note that a business can fall under multiple categories, and
these are specified in different variables names Category1, Category2,…
We will consider reviews for restaurants. The data has been pre-processed to get the business type,
review text, star rating, and how many users found this review to be cool, funny, useful, into a single file
which you will use for the analyses. There are ~ 45K rows in the sample file given.
