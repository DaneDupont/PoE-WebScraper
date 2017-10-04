# PoE-WebScraper

This is a simple web-scraper using Python, BeautifulSoup, and Numpy for poe.trade. The goal of this scrapper is to be able to check for under-priced items based upon the current prices being listed for sale. 

The scraper takes urls from the url list, which are poe.trade searches for specific items, parses the data returned and displays any item(s) that are two standard deviations away from the mean of the top 15 listed items for sale. 
