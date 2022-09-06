# WebScraping-BeautifulSoup


Hamoye Stage C (Python Libraries for StoryTelling)
PROJECT : Web Scraping with BeautifulSoup
 
Introduction
 What is web scraping? 
Web scraping is the process of using bots to crawl websites to extract content and specific information as structured data. It extracts underlying HTML code and data stored in a database.
Aims and Objectives
The aim of this project is to learn the art of web scraping using some Python libraries. My initial idea was to scrape a real estate website called Abujaproperties.com where I intended to find out the cost of renting different apartments and see how their prices vary based on location, type of building,  facilities etc. After several attempts to scrape that website, I discovered that the website has restrictions placed on scraping their webpage , same with other websites I tried.
I finally settled for an online bookstore called bookstoscrape.com. My focus was to scrape the first  page and grab the book titles,  the prices, and the stock availability.
 
 
 
Tools and Processes of Web Scraping
Firstly, we import the following libraries:
Requests: To make web requests
Beautiful Soup: To extract data from the HTML response
Pandas: To display the data in a dataframe
The process of web scraping includes the following steps:
Make a request with requests module via a URL.
Retrieve the HTML content as text.
Examine the HTML structure closely to identify the particular HTML element from which to extract data. To do this, right click on the web page in the browser and select inspect options to view the structure. I used the google chrome browser
Use BeautifulSoup to crawl the website and find the particular element from the response and then extract the text.
Analysis
I used the info function to see what data types each column has and to see if there is any analysis to be carried out. I also checked for the book that has the highest price and the book that has the lowest price.
 
