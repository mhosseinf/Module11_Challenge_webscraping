# Module11_Challenge_webscraping

## Mars Temperature Data Analysis

This repository hosts two Python scripts, and one folder contains output data:

1. Mars News Scraper: This script scrapes Mars news data from this webpage.
https://static.bc-edx.com/data/web/mars_news/index.html,

2. Mars Temperature Data Scrapping and Analysis: The second script scrapes and analyses weather data from Mars, sourced from the below page. The analysis offers valuable insights into Martian temperature/Pressure patterns.
https://static.bc-edx.com/data/web/mars_facts/temperature.html

3- The data is stored in a JSON file named news_data.json, located in the output folder for the Mars News Scraper.

4-Similarly, the scraped data is converted into a DataFrame for the Mars Temperature Data Analysis script and exported as a CSV file named Mars_Temperature_Data.csv. This CSV file is also saved in the output folder.

# Mars news Web Scraping

## How it works
1-The script uses Splinter to open a Chrome browser and visit the specified URL.

2-It then creates a Beautiful Soup object to parse the HTML content of the web page.

3-The script extracts text elements with the class image_and_description_container.

4-It loops through these text elements extracts the text within each element, and prints it.
5-The script also extracts news titles and preview text from the page.

6-It stores this data in a list of dictionaries, each representing a news article.

7-Finally, it exports this data to a JSON file named news_data.json in the output folder.



# Mars Temperature Data Scraper

## How it works

1-Similar to the first script, it uses Splinter and Beautiful Soup to visit the URL and parse the web page.

2-The script extracts rows of data from the page.

3-It creates a Pandas DataFrame to organise the data.

4-The data types of DataFrame columns are adjusted for analysis.

5-It answers several questions about the Mars data, such as the number of months, days, average temperatures, etc.

6-The script generates visualisations to better understand the temperature patterns on Mars.

7-Finally, it exports the DataFrame to a CSV file named Mars_Temperature_Data.csv in the output folder.
