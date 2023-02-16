# Geospatial-Sentiment-Analysis

Geospatial sentiment analysis involves using geolocation data to understand the sentiment of social media posts about a specific topic, in this case, a conference on climate change. This can be useful for understanding how people around the world feel about the conference and the issues it is discussing. To perform geospatial sentiment analysis on a dataset of tweets, you would first need to gather the tweets and extract the geolocation data for each one.

Once you have the location data for each tweet, you can use a natural language processing (NLP) tool to analyze the sentiment of the text in the tweets. There are many different NLP tools available, some of which are specifically designed for sentiment analysis. These tools typically use a combination of machine learning algorithms and dictionaries of words with known sentiment values to determine the overall sentiment of a given piece of text.

Once the sentiment data for each tweet is obtained, results are plotted on a map using a geospatial visualization tool. This allows you to see how sentiment about the conference varies by location. For example, you might find that sentiment is generally more positive in certain parts of the world than in others, or that sentiment changes over time as the conference progresses.

# Code description 

The method used in this case is supervised learning with a lexicon-based approach. A Python library called "TextBlob" is used to analyse the text. Natural language processing tasks like tokenization, noun phrase extraction, sentiment analysis, etc. can be carried out using TextBlob's consistent API. We can determine the polarity and subjectivity of each tweet using Textblob's sentiment module.

We experimented with model, pattern analyzer. The Pattern analyzer is based on the pattern library . After pre-processing the tweets, each tweet was read into a dataframe using pandas library in python. Every tweet is iterated through the process of Pattern Analyzer.

# Pattern Analyzer

Pattern analyzer is the default analyzer of TextBlob. Itr returns a named tuple of the form: Sentiment(polarity=0.0, subjectivity=0.0). The polarity score ranges from -1.0 to 1.0 and the subjectivity ranges from 0.0 to 1.0 where 0.0 is very objective and 1.0 is very subjective. Based on the polarity, whether it was 0, less than 0, or more than 0, the tweets are classified as neutral, negative and positive tweets respectively.

# Sentiment Analysis on Geo-spatial Twitter Data

Analysing the public's perception of the energy transition during the UN COP 26 event,it is found that energy transition is being viewed differently across different regions, according to the analysis of the tweet dataset, with some expressing positive views and others expressing negative ones. One of the major conclusions from the analysis is that the UK and other European nations account for the majority of tweets expressing support for the energy transition. These tweets emphasise how crucial it is to switch to green energy in order to lower carbon emissions and lessen the effects of climate change.

On the other hand, tweets that are critical of the energy transition are primarily from the United States and other countries. These tweets frequently contest the validity and affordability of switching to green energy. Despite the contradictory ideas, I wouldn't take these tweets seriously when it comes to influencing governmental policy. Many of the tweets criticising the energy transition are sent from outside the UK and might not accurately represent the opinions of the population there.

Overall, there are strong messages about energy transition, with the majority of tweets stressing how crucial it is to switch to green energy in order to fight climate change. I would advise the UK government, as a policy adviser, to take into account public opinion and move toward switching to green energy in order to achieve net carbon zero.

