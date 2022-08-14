# surfs_up
Weather Analysis using SQLite
## Overview of the statistical analysis
### Purpose
The purpose of this analysis is to review a dataset pertaining to weather conditions that has been stored in a SQLite database to provide information that will convince an investor that opening up a Surf n' Shake shop in Oahu, Hawaii is a good business idea. The idea is that the shop will sell surf boards and ice cream throughout the year, but the investor is hesitant because he invested in a similar business that failed due to the weather conditions. In order to get this investor on board, we need to provide statistical analysis specifically on the weather conditions in Oahu that will convince him that this will be a successful business venture.
### Resources
* Jupyter Notebook Files: Climate_analysis.ipynb, SurfsUp_Challenge.ipynb
* Python: app.py
* Sqlite file: hawaii.sqlite
* Data tool: Python SQL (SQLAlchemy), Object Relational Mapper, pandas, numpy.
* Software: Flask, SQLite.
### Overview
This project explores the power of Advanced Data Storage and Retrieval to efficently produce an analyis of temperature trends in Oahu, Hawaii. Specifically, summary statistics of temperature data were requested for the months of June and December, in order to determine if a prospective surf and ice cream shop business can sustainably operate year-round as opposed to a seasonal business.
## Results
<img width="173" alt="Screen Shot 2022-08-13 at 9 35 45 AM" src="https://user-images.githubusercontent.com/107584361/184502980-cf5990b2-be87-4d5a-a100-dae3220fd345.png"> <img width="161" alt="Screen Shot 2022-08-13 at 9 36 45 AM" src="https://user-images.githubusercontent.com/107584361/184502986-4aaa5fcd-d9e0-4073-9515-2c5422219fb9.png">

### Observations
* The Number of counts are more in june compared to december. June recordings were 1700 whereas December has 1517 counts.
* The Average temperature in the month of June were 74.94 whereas for December was 71.04.
* The maximun and minimum temperatures for the month of June were 85.0 and 64 whereas for the month of December it was 83.0 and 56.0.
* The Standard Deviation were 3.25 and 3.74 for the month of Jne and December respectively.
* As per the observations, **The weather conditons in the months of June and December has temperature around 70 and 80 which are suitable for surfing and having ice cream.**
* this shows the Surf n' Shake shop in oahu, Hawaii will be a profitable bussiness idea.
## Summary
Oevrall the weather in December and June are very similar, although December has a wider range of results, with its high being close to June month but its low well below June month.

Additional queries may include: 
* Precipation difference between June and December to determine which one has more rainy weather.
* The weather station closest to our bussiness location, which would narrow the results and provide the best data for us to consider.
