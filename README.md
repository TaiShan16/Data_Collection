# Data_Collection
The purpose of this project is to perform a full web-scraping and data analysis on a webpage that contain multiple news articles. We identify HTML elements such as the id and class attributes, and extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.

This project consists of 2 parts:

##### Part 1: Scrape titles and preview text from Mars news articles.

In this part, We will use automated browsing to visit the Mars News website: https://static.bc-edx.com/data/web/mars_news/index.html.
We will create a Beautiful Soup object and use it to extract text elements from the website. Then, extract the titles and preview text of the news articles that we scraped, and store the scraping results in Python data structures.

##### Part 2: Scrape and analyze Mars weather data, which exists in a table.
In this part, We will use automated browsing to visit the Mars Temperature Data site: https://static.bc-edx.com/data/web/mars_facts/temperature.html.
We will create a Beautiful Soup object and use it to scrape the data in the HTML table. We will assemble the scraped data into a Pandas DataFrame and analyze the dataset by using Pandas functions and plot the results as a bar chart.
