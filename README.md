# USA Today News Scraper

This project is a Python script designed to scrape news articles from USA Today. Given a list of article URLs, the script extracts the article content (news text) and publication date. The script is built and executed on Google Colab for ease of use and accessibility.

## Features
+ Input: A list of URLs to USA Today news articles.
+ Output: Extracted article texts and their corresponding publication dates.
+ Environment: Developed and tested on Google Colab.

## Requirements
I have executed and tested this script on Google Colab. You can either use Google Colab or modify the script to run it in other environments. To use it on Google Colab, you will need a Google account.
+ Python libraries, used in the script, include:
  + requests
  + BeautifulSoup (from bs4)
  + pandas
  + os
  + csv

## Usage Instructions
1) Upload the script to Google Drive or directly open it in Google Colab.
Provide Input:
2) Provide the specific path to the .csv file containing USA Today's news URLs in the script. An example csv file for this script include the first column name "serial_number" and second column name "links."
3) Specify the output folder
4) Run the script titled "UTO_news_scrapper.ipynb". It will fetch the news content from each URL and save each URL's news text in separate .txt file. All such .txt files will be under the output folder.

## Example Input and Ouput 
As examples, a few input links and their ouput texts are provided in the Input and Output folders respectively.

## Notes:
This script is meant for academic research purpose only. Please ensure that your scraping complies with relevant ethical issues.

## Customization
The script can be modified to scrape additional metadata, such as author names, article tags, etc. 

