# twitter-activity-analysis
Analysis of the UN OHCHR twitter account @UNHumanRights activity using NLP for state of human rights assessment around the globe.

## Intro
The state of the human rights around the world is an important indicator for progress, prosperity, and development of the whole world. A plethora of research has suggested that there is a positive correlation between condition of the human rights in a society and economic growth, social, and political stability.

The official Twitter API and a python package tweepy were used for data collection. Twitter API allows retrieving, engaging with, or creating tweets, users, spaces, direct messages, lists, trends, media, and places on Twitter through endpoints. There are three access levels for developers using the Twitter API – essential, elevated, and academic research. The level of access increases from left to right with academic research tier having the most access rights. In order to interface with the API through python, the tweepy python package was used. It serves as a wrapper for the endpoints provided by the API and allows to quickly get started with using the Twitter API.


## Results
The results of the experiment showed that most of the tweets obtained using the search query did not belong to a single region. Additionally, the frequency of tweets over the last decade has an increasing trend during some periods and decreasing during other. This might be due to the different events happening around the world. More thorough exploration in needed though, to extract more meaningful insights using the approach.

<p align="center">
  <img src="https://github.com/fariduca/twitter-activity-analysis/assets/49120128/158716ca-b03f-45b1-9c20-bc2dc465deba" width="512"       alt="Frequency of tweets over 10 years (2012-2022)"/>
  <br/>
  Frequency of tweets over 10 years (2012-2022)
</p>
<p align="center">
  <img src="https://github.com/fariduca/twitter-activity-analysis/assets/49120128/854d7bc9-6f4b-4b5e-8202-66cacb764ced" width="512"       alt="Frequency of a country mentioned in a tweet that also contains words like: “urge”, “call”, “deplore”, “concern”, “condemn”, or       “alarm” (2012-2022)" />
  <br/>
  Frequency of a country mentioned in a tweet that also contains words like: “urge”, “call”, “deplore”, “concern”, “condemn”, or “alarm” (2012-2022)
</p>
