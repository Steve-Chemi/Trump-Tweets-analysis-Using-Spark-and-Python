# Trump-Tweets-analysis-Using-Spark-and-Python
From an history of all Donald trump tweets since 01/01/2015 in the form of a text file, i'll make a Text analysis using Apache Spark on Python

**Context:** I have an history of all Donald trump tweets since 01/01/2015 in the form of a text file.
* Each line of this text file is in the form: text_of_the_tweet,date_of_the_tweet
* Each tweet can be an original tweet or a retweet, each retweet starts with the keyword ‘RT’


<img src="https://github.com/Steve-Chemi/Trump-Tweets-analysis-Using-Spark-and-Python/blob/master/Trump_Tweets.png">

My task is to explore this data by using Spark, because i should also be able to apply this on very large data sets, for instance to analyze the communication of other public figures.
I will present my keys findings in form of lists, tables or visualizations.

I will for instance search for:
* **Top positives and top negatives words used**
* **Overall sentiment scores (from positives and negatives words)**
* **Top contextual words or hot topics (e.g. covid-19) and associated opinions…**
* **Top hashtags (#) cited**
* **Top references (@) cited- …**
I will explore these points over the time (per month or per year for instance), and make a differentiation between original tweets and retweets (RT).
My final jupyter notebook will contain keys findings (lists, tables, visualizations, …) from these points. I will also try to comment all these key findings
