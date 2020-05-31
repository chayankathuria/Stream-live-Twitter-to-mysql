# Stream-live-Twitter-to-mysql

#### I have used the Twitter API to search for tweets containing specific keywords and stream this directly into MySQL database. Once done, the data will be available for further analysis at any time.

------------
#### I have used the Tweepy library which will makes it very easy to connect to the API and start streaming the data.

#### I connected to the twitter API via tweepy using the credentials generated on the twitter developer app. Later I used mysql.connecter to connect it to the API and stream live data.

#### The tweets were filtered for certain keywords and fetched in realtime.

#### Almost 14000 tweets were gathered in 5 hours and loaded into python using mysql connector.

#### Then the data was fetched into a dataframe and fed to the NLP pre processing pipeline

#### Sentiment analysis was done using textblob
-------
