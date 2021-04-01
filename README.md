# Wsb_stock_scraper

## What does it do?
Scrape reddit posts to see which common stock is the hottest based on term frequency. Pages visited is /wallstreetbets with 1.1million subcribed users (still increasing as we speak) This will be scraping hottest post. Desired number of post can be changed, and type (newest, hottest, top) of post can be changed.

Conclusion: Currently the hottest stock is GME as of Feb 15 2021

## Needed Improvements 
Some stopper words ('a'), slangs('CEO'), or mispelled words may be misinterpreted as tickers. Vader model can be improved with more updated version of words of today's standards.

## Example results:
Post refers to the Reddit posts headline
![image](https://user-images.githubusercontent.com/25267825/113228887-dea98000-9263-11eb-85d1-f01e465c577f.png)

In conclusion: We can see that GME was mentioned the most, however it has a less positive sentiment versus PLTR with 72% more.
