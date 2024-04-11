#     Exploratory Data Analysis - Project Team 2
#     Video Game Ratings and Sales Analysis 
#     Project 1 


## Overview

The video gaming industry, is the selected industry for our project.  Specifically, the games that are played on or via the internet.  Rating statistics are captured and maintained 
within a database managed by Twitch, an Amazon Company.  Per Wikipedia, "Twitch is an American video live-streaming service that focuses on video game live streaming, including broadcasts of esports competitions, in addition to offering music broadcasts, creative content, and "in real life" streams. Twitch is operated by Twitch Interactive, a subsidiary of Amazon[4] It was introduced in June 2011 as a spin-off of the general-interest streaming platform Justin.tv.[5] Content on the site can be viewed either live or via video on demand. The games shown on Twitch's current homepage are listed according to audience preference and include genres such as real-time strategy games (RTS), fighting games, racing games, and first-person shooters." (https://en.wikipedia.org/wiki/Twitch_(service)).

The database (one of two for this project), that we are using is the Internet Games Database, IGDB. Per Wikipedia, "Twitch acquired the Internet Games Database (IGDb), a user-driven website similar in functionality to Internet Movie Database (IMDb) to catalog details of video games in September 2019. Twitch plans to use the database service to improve its own internal search features and help users find games they are interested in.[73] On September 26, 2019, Twitch unveiled a new logo and updated site design. The design is accompanied by a new advertising campaign, "You're already one of us", which will seek to promote the platform's community members.[74] Twitch began signing exclusivity deals with high-profile streamers in December 2019."  The url of the IGDB is https://www.igdb.com/ .  

The second, or other database we plan to use is Kaggle based, and is "Video Games Sales", url https://www.kaggle.com/datasets/gregorut/videogamesales. This came to us somewhat of an after thought, as we wanted to include sales information in addition to the ratings data we get from the IMDb. 

## Questions

The goal or questions we aim to answer, gleened from our intial review of the columns within both databases are...

     o  What games (aggregate) are used/rated the best (IGDB)
     o  What games by genre are rated the best? (IGDB)
     o  What platform (X360, PSx, etc.) is used more for gaming? (IGDB)

       Using a cross correlation through the matching by name of game to the sales db (IGDB --> Sales DB) 

     o  What games have the highest sales?
     o  Does the sales data follow the rating information?
     o  Game sales by country (North America, Europe, Japan, other)

The IGDB contains a hoard of information, and through Twitch, we will use their API which is robust.  
On the other hand, the Kaggle dataset for sales will have to be downloaded, and is much smaller.  It contains information on 
those games with sales over 100,000.  


## Summary
This information is of course subject to change, and we may adjust it, based on more exploration of the data, so this is a working document at this time. 
It is felt that information gleened from the information presented, that an individual (or company) could use it to plan the development of a new game. 



