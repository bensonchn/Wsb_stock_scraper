# Wsb_stock_scraper

## What does it do?
Scrape reddit posts to see which stock is the most mentioned based on term frequency. Pages visited is /wallstreetbets with 1.1million subcribed users (still increasing as we speak) This will be scraping hottest post. Desired number of post can be changed, and type (newest, hottest, top) of post can be changed.

Conclusion: Currently the hottest stock is GME as of Feb 15 2021

## Needed Improvements 
Vader sentiment model can be refined to be more custom to financial terms.

There are a lot of words/slangs that are mistaken for tickers. Some stopper words ('a'), slangs('CEO'), or mispelled words for example, despite already remove many similar words from the list.

## How to run it.
On google colab, run all, you will be prompt to upload a csv file with all the nasdaq symbols (link will be provided)
Reason for doing so, new company can be added from time to time, and keeping a static csv file not count those newer stocks

## Example results:
Post refers to the Reddit posts headline
We can see that GME was mentioned the most, however it has a less positive sentiment versus PLTR with 72% more.

```This is 2 hottest posts on Feb 14, 2021```

![image](https://user-images.githubusercontent.com/25267825/113228887-dea98000-9263-11eb-85d1-f01e465c577f.png)

```This is 3 hottest post on Mar 31, 2021```

![image](https://user-images.githubusercontent.com/25267825/113230403-ee769380-9266-11eb-98e8-47f791361704.png)



