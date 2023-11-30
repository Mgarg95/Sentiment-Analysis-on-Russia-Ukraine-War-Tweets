
# Russia-Ukraine War Sentiment Analysis on Tweets
In February 2022, Russia announced special military operation on Ukraine.  As people gather on social media to express their opinion on the incident, it will be insightful to analyse their sentiment as different people throughout the world have different opinions. This analysis finds out the positive,negative and neutral sentiments about the war for all tweets in English till 12/2022.
### Microsoft Azure
We adopt Text Analytics in Azure Cognitive Services to obtain the sentiment score of tweets. The API can ouput confidence scores of the text being postive, neutral and negative respectively. For consistency and easier understanding, we will map the scores into a composite score in range [-1. 1].
### TextBlob
Textblob is an open-source python library for processing textual data. It can evaluate both polarity and subjectivity in text. The polarity score is a float within the range [-1.0, 1.0]. The subjectivity is a float within the range [0.0, 1.0] where 0.0 is very objective and 1.0 is very subjective.

### Results
It can be seen that most users are objective, which is unusual on social media. This can be attributed to the fact that people tend to express objective opinion while sharing news.
