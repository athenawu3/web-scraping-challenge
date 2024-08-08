# Web-Scraping Challenge

## Overview
In this challenge, I web-scrape the articles on this news site (https://static.bc-edx.com/data/web/mars_news/index.html) and the data on this site (https://static.bc-edx.com/data/web/mars_facts/temperature.html). 

### Part 1: Analyzing and Exploring the Climate Data
I used automated browsing and a Beautiful Soup object to inspect the Mars news site and extract the titles and previews of the articles. I then stored these results in a Python dictionary. You can find my code in this file: part_1_mars_news_ipynb.

### Part 2: Design Your Climate App
Here, I used a Beautiful Soup object to scrape the temperature data in the HTML table in the Mars weather site. I put that data into a Pandas DF and used it to analyze the data, which involved plotting average low temperatures and average pressures by month. Here are my findings:
1. There are 12 months on Mars.
2. There are 1,867 Martian days' worth of data.
3. The coldest month in Curiosity's location on Mars is the 3rd month.
4. The warmest month in Curiosity's location on Mars is the 8th month.
5. The month with the lowest atmospheric pressure in Curiosity's location is the 6th month.
6. The month with the highest atmospheric pressure in Curiosity's location is the 9th month.
7. There are roughly 700 terrestrial days exist in a Martian year.
You can find the dataframe I used for the above analysis in this file: Mars_DataFrame.csv.