# Stock_sentiment_Analysis

Top 10 stocks with gains and loss are tracked and analysed based on the the social media buzz on Twitter

We are scrapping the names of the top ten and bottom 10 stocks from BSE website, and later the names of each stock are then fed to the Twitter scraper.
Twitter scraper uses the query to scrape tweets related to the stock names, the time frame taken is the past 7 months.

We are saving the scraped tweets along with the information on username, time and a flag to identify the stock status
stock status 0 is a bottom 10 stock and 1 denotes it is a gainer stock


The tweets are cleaned of punctuations, emojis, hyperlinks, retweets and hashtags

We are using the text blob library for determining the subjectivity and polarity of the tweets and thereby determining the sentiments as positive, Negative and neutral

We are analysing the number of positive and negative sentiments associated with both gainer and loser stocks
