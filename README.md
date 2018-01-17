# Twitter Sentiment Study
*A simple sentiment study.<br><br>

The goal of this study is to extract tweets using the Twitter API Tweepy on a certain topic, and then analyze the overall sentiment for the topic by analyzing the positive and negative words ratio. The topic chosen is "Trump", and approximately 540 tweets were pulled spanning over the first two weeks of January 2018. Below are the results:<br>

## Ratio of Positive and Negative Words:<br>
3.6<br><br>

## Interpretation:<br>
Overall positive; there are more than 3 times more positive words than negative words<br><br>

## Discussion:<br>
This study is very valuable to political parties when trying to estimate the effectiveness of their campaigns and political efforts. Despite the overall negative voices for Trump's presidency, from this sentiment study on Twitter that he is actually more popular than the Media led us to believe. This method could also be used to predict stock prices by analyzing market sentiment. Please see Jupyter Notebook file for details of steps used for study.<br>

## Future Improvements:<br>
Initially, I planned on using Nltk library to analyze the tweets extracted. This is a sophisticated library that could not only interpret the postive/negative words, but also could measure the sentiment of tweets by giving a "sentiment value". However, due to the simplicity of the assignment, using pre-existing word lists and loops is a more direct approach. the Nltk approach is detailed in the source list below. The final word count for positive and negative word counts seems low for more than 500 tweets. This is perhaps due to extra punctuation that still exists in the final word list that was used for analysis. Additional methods could be used in the future to further clean the data. Due to the limit placed by Twitter, I couldnt extract more than 140 tweets at once. In the future, I could try using 'Twitter Stream' to capture large amount of tweets at once (method detailed in sources). Another library I found extremely helpful in this study was the "tweet-processor" library; this allowed me to quickly clean up the tweets collected without writting large blocks of code<br>

## Sources:<br>
General Directions Help: MSIS 2802 Class TA<br><br>

Nltk Approach to sentiment study:<br>
https://stackoverflow.com/questions/43646877/python-extract-positive-words-from-a-string-using-sentiment-vader<br><br>

Setting up Tweepy:<br>
https://www.youtube.com/watch?v=o_OZdbCzHUA&t=335s<br><br>

Tweepy Documentation:<br>
https://media.readthedocs.org/pdf/tweepy/latest/tweepy.pdf<br><br>

Tweet-Preprocessor:<br>
https://pypi.python.org/pypi/tweet-preprocessor/0.4.0<br><br>

General Python Help:<br>
https://pythonprogramming.net/<br><br>

Syntax Help:
https://dev.to/rodolfoferro/sentiment-analysis-on-trumpss-tweets-using-python- 

Tweets write to text file:<br>
https://stackoverflow.com/questions/21976599/tweepy-search-api-writing-to-file-error<br><br>

Combine multiple text files:<br>
https://stackoverflow.com/questions/13613336/python-concatenate-text-files<br><br>

Start Tweet Stream:<br>
http://docs.tweepy.org/en/v3.5.0/streaming_how_to.html<br><br>






