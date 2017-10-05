# PoE-WebScraper
This is a simple web-scraper using Python, BeautifulSoup, and Numpy for market analysis of poe.trade (for the PC game Path of Exile). The goal of this scrapper is to be able to check for under-priced items based upon the current prices of similar items being listed for sale. 

Overview
------------
The scraper takes urls from the url list, which are poe.trade searches for specific items, parses the data returned and displays any item(s) that are two standard deviations away from the mean of the top 15 listed items for sale. 

Requires
-----------
Python 3.0, BeautifulSoup 4.4.1 or higher, numpy
