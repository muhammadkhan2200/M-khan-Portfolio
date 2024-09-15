# M-khan-Portfolio
Python Portfolio
# [Project 1: Web Scraper with Python](https://github.com/muhammadkhan2200/Web-Scraper-with-Python/blob/main/README.md#web-scraper-with-python)
[^1]: This project utilizes Python's urllib module to create a web scraper that extracts data from a specified website. Here's a brief overview: Initialization: The Scraper class is initialized with a website URL, such as "https://news.google.com/". Scraping Method:

import urllib. request from bs4 import BeautifulSoup

class Scraper: def init(self, site): self.site = site def scrape(self): r = urllib.request.urlopen(self. site) HTML = r.read() def scrape(self): r = urllib.request.urlopen(self. site) HTML = r.read() parser = "HTML. parser" sp = BeautifulSoup(HTML, parser) def scrape(self): r = urllib.request.urlopen(self. site) HTML = r.read() parser = "HTML. parser" sp = BeautifulSoup(HTML, parser) for tag in sp.find_all("a"): url = tag. get("href") if URL is None: continue if "articles" in URL: print("\n" + URL) import urllib. request from bs4 import BeautifulSoup
