# javlibrary-scraper
**JAVLibrary-Scraper** is a Node script that automatically crawls JAVLibrary and scrapes all the data to an SQLite database with a many-to-many relationship.<br>



## Usage:
**scrape** - shows the scraper command list.<br>
**scrape category** - scrapes JAVLibrary for all the categories and saves them to the database. Required for scraping videos.<br>
**scrape video** - scrapes all the videos from JAVLibrary.<br>
**scrape video *(category name)*** - scrapes all the videos from JAVLibrary with a category offset*.<br>
**scrape video *(category name) (page #)*** - scrapes all the videos from JAVLibrary with a category and page offset*.<br>

*the offset will allow you to not start all over scraping JAVLibrary if the scraping failed for some reason or you decide to pause it. 

## Dependencies:
[x-ray](https://www.npmjs.com/package/x-ray)<br>
[chalk](https://www.npmjs.com/package/chalk)<br>
[request-promise](https://www.npmjs.com/package/request-promise)<br>
[cloudscraper](https://www.npmjs.com/package/cloudscraper)<br>
[cheerio](https://www.npmjs.com/package/cheerio)<br>
[better-sqlite3](https://www.npmjs.com/package/better-sqlite3)


## Notes:
This script was made mostly for my own usage, so don't expect it to get frequent updates as long as it performs it's main use case.
