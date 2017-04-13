## Google art project scraper
This is a scrapy crawler for [Google art](https://www.google.com/culturalinstitute/beta/u/0/)
Use it at your own risk to be banned by google.  
Scrape politely.

### Description
The crawler does:
1. Parses [arists list page](https://www.google.com/culturalinstitute/beta/u/0/category/artist)
2. Parses pages for every individual artist, extracting info about them.
3. Extracts a list of artworks for every artist, download images at max resolution 512x512.
4. Parses pages for every individual artwork, extracting info about them.

All the collected data is stored in [MongoDb](https://docs.mongodb.com/manual/installation/).  
Images are stored on disk.

### Dependencies
- [MongoDb 3.4](https://docs.mongodb.com/manual/installation/)
- Python 2.7
  - [Scrapy 1.3.3](https://doc.scrapy.org/en/latest/intro/install.html)
  - Pymongo 3.4.0

### Usage
TODO:
