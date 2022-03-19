# Network-Analytics-Project---Winter-Olympics
Comparing the reactions of Twitterati of two US-Born Winter Olympians of Chinese origin

Eileen Gu and Nathan Chen are two American-born Winter Olympians of Chinese descent. While the athletes had similar backgrounds, the thing that set them apart was that Eileen chose to compete for China during the 2022 Winter Olympics. Several news channels referred to Eileen as a traitor.

This project aimed to capture and compare the discussion surrounding the two Olympians on Twitter, and to determine if the sentiments were driven by influencers. Furthermore, we assessed if Eileen Gu is still marketable in the United States.

The project included the following phases - 
- Data Extraction by Scraping Twitter: Please refer '01 - Data Extraction.ipynb'
- Data Cleaning and Sentiment Analysis: Please refer '02a - Sentiment Analysis - Eileen Gu.ipynb' and '02b - Sentiment Analysis - Nathan Chen.ipynb'
- Topic Modeling to identify Dominant Themes: Please refer '03a - Topic Modeling - Eileen Gu .ipynb' and '03b - Topic Modeling - Nathan Chen.ipynb'
- Network Analysis using Gephi: Please refer 'Network Analysis - Eileen Gu.gephi' and 'Network Analysis- Nathan Chen.gephi'
- Final Presentation: Please refer 'Fame Fury.pptx'

![image](https://user-images.githubusercontent.com/61624917/159137055-34b33878-9a3f-467e-a6de-a5222f119a12.png)

Data extraction was done using Tweepy. We scraped a total of 60,000 tweets (30,000 each for Chen and Gu)

Data Cleaning included filtering out the tweets that were not in English (done using Google Sheets), followed by removal of emoticons, links, stopwords, and words shorter than 3 characters. After this, we converted everything into lower case and performed stemming and lemmatization. The lemmatized data was used for Sentiment Analysis using VADER

We then analyzed the network using Gephi and shared the key takeaways. We conclude the following - 
- Both athletes have a grassroots-driven network
- The negative tweets about Eileen Gu were mostly criticising the negative media coverage she received, and about the actions of the Chinese government
- Contrary to the opinion of the popular news channels, Eileen Gu is not unmarketable in the United States
