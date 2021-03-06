# tex_analysis_climate_change
The repository contains a code to run an unsupervised topic modeling and quantitative text analysis using R package STM on US Congressional speeches and newspaper articles addressing the issue of climate change. 

There were two selection criteria for our corpus; that the texts/speeches contained specific mentions to "climate change" or "global warming", and that these  were produced between January 2008 and September 2016. The timeframe of analysis is delineated by the two presidential terms of Barack Obama.

The corpus contains the following: 
* Congress Floor Speeches: We use House of Representatives and Senate from the Gentzkow, Shapiro and Taddy Dataset of Congressional Record for the 43rd-114th Congresses (2017). The last speech sample is from the 6 of September 2016.The unit of analysis is unique speech by speaker per day and Chamber. Our initial sample contained 3736 unique speeches.
* Congress Committee Hearings: We party make use of the dataset of Ju Yeon Park (2021) from the Committee Hearing speeches in Congresses from 105th through 114th. Our initial sample contained 1400 unique speeches.
* Newspaper Articles: We downloaded news articles from ProQuest from the Washington Post, The New York Times and Wall Street Journal as thr most influential print news sources. The unit of analysis is article per journal and day. Our initial sample contained unique 4385 articles.

References: 
- Gentzkow, M., Shapiro, J. M., & Taddy, M. (2019). Measuring group differences in high‐dimensional choices: method and application to congressional speech. Econometrica, 87(4), 1307-1340.
- Park, J. Y. (2021). When do politicians grandstand? Measuring message politics in committee hearings. The Journal of Politics, 83(1), 000-000.
