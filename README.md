# Udacity_Project_1


## Motivation

The following project has been created as part of the [Udacity Data Science Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025)

Using the Munich Airbnb dataset, this project aims to answer the following three questions of interest:

##### 1. In which months are most Airbnb listings still available (total and by room type)?
##### 2. In which Munich areas (zip codes) are the best Airbnb listings (according to total rating)?
##### 3. Do less expensive listings have a lower rating compared to expensive listings? 


## Files

This project uses data from the [Munich Airbnb dataset](http://insideairbnb.com/get-the-data.html) (date compiled: 24th of December 2020)

The analysis includes detailed listings data (download: listings.csv.gz) as well as detailed calendar data for listings (download: calendar.csv.gz). The unzipped data are stored in the Data folder of this project.

The udacity_project_1.ipynb  - Jupyter notebook includes the full project analysis for all three questions.


## Installation

For this project, I've have used Python 3.7.3 and the following Python libraries:

- altair==4.1.0
- geopandas==0.8.2
- matplotlib==3.3.2
- numpy==1.19.4
- pandas==1.1.3
- seaborn=0.11.0
- shapely == 1.6.4


## Results

##### 1. In which months are most Airbnb listings still available (total and by room type)?

February 2021 is the month with the highest availablity rate, followed by January 2021 and March 2021. This makes sense, if you think of the current Corona situation.      People hesitate to book a room soon. October 2021 is the busiest month regarding the availablity rate. People look forward to go to the Octoberfest again.

If we have a look at the availability rate by room type, we can see that entire home/apartments, private rooms and shared rooms also have the hightest availability rate in January, February, and March 2021. Only hotel rooms are slightly more booked in January 2021 compared to the other months - availability rate is only 0.9%.

##### 2. In which Munich areas (zip codes) are the best Airbnb listings (according to total rating)?

It seems to be that most of the popular areas (zip codes with a rating above 97%: 81373, 80639, 81243, 80636, 80686) are placed in the West of Munich. This area has very good traffic connections to the inner city and also to the Oktoberfest. The only exception is zip code 81545, which is placed in the South of Munich. One reason might be the good location near to the Perlacher Forst. 

Please note, that all areas have an average total rating above 90. Zip codes with ratings less than 10 were excleded from the analysis.


##### 3. Do less expensive listings have a lower rating compared to expensive listings? 



If you are interested to learn more, please visit my blog article.

