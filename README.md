# Web Crawler for JLL India's Twitter Account

This is a Python-based web crawler that has been created using the Google Colab platform. The main purpose of this web crawler is to scrape data from the Twitter account of JLL India. The libraries that have been used to create this web crawler are Selenium, BeautifulSoup, pandas and time.

## Libraries Used

*Selenium*: This is a Python library that is used to automate web browsers. It is mainly used for testing purposes, but it can also be used for web scraping. In this web crawler, Selenium has been used to open the Twitter website, navigate to the JLL India Twitter account, and scroll through the tweets.

*BeautifulSoup*: This is a Python library that is used for web scraping purposes. It is used to extract data from HTML and XML files. In this web crawler, BeautifulSoup has been used to extract the data from the HTML code of the tweets.

*pandas*: This is a Python library that is used for data manipulation and analysis. In this web crawler, pandas has been used to create a data frame and store the scraped data in a CSV file.

*time*: This is a Python library that is used to add time delays in the code. In this web crawler, time has been used to add a delay of a few seconds after each scroll, to ensure that all the tweets are loaded before scraping.

## Steps to Use

To use this web crawler, follow these steps:

Open Google Colab and create a new notebook.

Copy the code from the GitHub repository and paste it in the notebook.

Make sure that all the libraries used in the code are installed in the notebook.

Run the code in the notebook.

After the code finishes executing, a CSV file named "JllIndia.csv" will be created in the notebook's file directory. This file will contain the scraped data.

## Limitations

This web crawler has a few limitations:

The code may not work if Twitter changes its HTML code.

The code may not work if Twitter changes its policies regarding web scraping.

The code may take a long time to execute if there are a large number of tweets to be scraped.

## Conclusion
This web crawler is a useful tool for scraping data from the Twitter account of JLL India. It can be used to extract data such as the tweet text, number of retweets, number of likes, and the date and time of the tweet. The scraped data can be used for various purposes such as data analysis, sentiment analysis, and market research.
