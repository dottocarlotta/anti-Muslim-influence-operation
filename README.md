# Data analysis of an anti-muslim hashtag campaign on Twitter in May 2021

How First Draft used Twitter data and Python's Pandas to analyse the anatomy of an anti-Muslim hashtag operation

[Carlotta Dotto](https://twitter.com/CarlottaDotto), First Draft

This repository contains data and code supporting a [First Draft article](https://firstdraftnews.org/articles/israel-palestine-tweets-and-indian-anti-muslim-network/) examining how an anti-Muslim influence operation in India hijacked conversations about Israel and Palestine. Published on May 21, 2021.

## Methodology

We gathered 46,170 tweets and retweets containing the #UnitedAgainstJehad hashtag between May 13 and May 17. 

We used Python's Pandas to analyse the main actors, to extract their creation dates and select the most common hashtags in the tweets and accounts' bio. 

Network analysis was performed on Gephi, resizing the nodes based on the in-degree (pict 1) and out-degree values (pict 2). We used the «ForceAtlas 2» layout to bring accounts that frequently mentioned each other closer together. 

---

## Data

[Data](https://github.com/dottocarlotta/antimasks-hashtags-data-analysis/tree/master/data) was scraped from the Twitter API.

## Analysis

• [This document](https://github.com/dottocarlotta/antimasks-hashtags-data-analysis/blob/master/NoMasks-analysis.ipynb) walks through the data analysis of #UnitedAgainstJehad hashtag. It provides reproducible code for parsing out the hashtags in the tweets and for creating key visualizations.
