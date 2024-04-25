# Mars News and Temperature Data Scraping

## Introduction
This project focuses on scraping Mars-related data from two distinct websites. The first part aims to retrieve news titles and preview texts from a Mars news site. The second part involves scraping Mars temperature data and storing it in a structured format for further analysis.

## Technologies Used
* Python
* Splinter
* BeautifulSoup
* Pandas
* Matplotlib

# Scraping Mars News
## Visiting the Website
The browsing process is automated using Splinter to visit the specified Mars news site.

## Scraping the Website
The website's HTML content is scraped using BeautifulSoup to extract relevant text elements, specifically news articles.

## Storing the Results
Extracted news titles and preview texts are stored in Python dictionaries, which are then appended to a list.

# Scraping Mars Temperature Data
## Visiting the Website
Automated browsing with Splinter visits the Mars Temperature Data site.

## Scraping the Table
The website's HTML content is scraped using BeautifulSoup to extract the table containing Mars temperature data.

## Storing the Data
The scraped data is organized into a Pandas DataFrame, using headers for column names.

# Data Analysis
The scraped temperature data is analyzed to answer specific questions about Mars' climate.

# Analysis Highlights for the following queries 
1. How many months exist on Mars? Mars has about 12 months.
2. How many Martian days' worth of data exist in the scraped dataset?There are 1867 Martian days' worth of temperature data.
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? The third month has the coldest temperature, and the eighth month is the warmest.
4. Which months have the lowest and the highest atmospheric pressure on Mars? The sixth month has the lowest atmospheric pressure, and the ninth month has the highest.
5. About how many terrestrial (Earth) days exist in a Martian year? A Mars year is about 675 Earth days long, based on the plotted data.

# Saving the Data
The final Pandas DataFrame containing the scraped temperature data is saved as a CSV file.

# Conclusion
This project demonstrates how to scrape Mars-related data using Python libraries and automate browsing using Splinter. The extracted data, including news articles and temperature records, can be used for various analyses, such as understanding Mars' climate patterns and recent news updates.

# Mars_News-Temp_Analysis Repo Organization
* part_1_mars_news - contains the code used to scrape the mars news website to retrieve various news article and headlines
* part_2_mars_weather - contains the code used to scrape the mars weather website to complete the temperature data analysis 
* Output – contains dataframe in the form of a csv for the scraped temperature data 




