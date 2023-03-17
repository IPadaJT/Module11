# Module 11 Challenge: HTML Scraping 
- The focus of this assignment was to use chromedriver and inspecting Chrome elements to scrape/extract information from the web.
- This assignment is done using:
    1. Beautiful Soup for HTML parsing
    2. Splinter for browsing

## Part 1: Mars News
- This portion asks us to create the first deliverable which is to scrape a list of article titles and summaries from a website
    1. 'https://static.bc-edx.com/data/web/mars_news/index.html'
- These titles and summaries are then stored into a dictionary

## Part 2: Mars Weather
- This portion asks us to create the second deliverable which is to produce and analyze data scraped from tables on the following website:
    1. https://static.bc-edx.com/data/web/mars_facts/temperature.html
- The extracted data is then imported into a pd.DataFrame
    1. The dtypes are changed appropriately to allow for data analysis.
    2. Certain groupings are created from the data
- Then the following questions were answered using the analysis:
    1. How many months are there on Mars?
    2. How many Martian days' worth of data are there?
    3. What is the average low temperature by month?
    4. How many terrestrial (earth) days are there in a Martian year?
- As well as plots for the following:
    1. Average Temperature by month
    2. Lowest Temperature sorted by month
    3. Average Pressure by month
    4. Low Temp vs Terrestrial Day plot
- Finally the data is exported into a csv.