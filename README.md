# javlibrary-scraper
JAVLibrary scraper is a Node script that automatically crawls JAVLibrary and scrapes all the data to an SQLite database with a many-to-many relationship.<br>



## Usage:
**scraper** - shows scraper the command list.<br>
**scraper category** - scrapes JAVLibrary for all the categories and saves them to the database. Required for scraping videos.<br>
**scraper video** - scrapes all the videos from JAVLibrary.<br>
**scraper video *(category name)*** - scrapes all the videos from JAVLibrary with a category offset*.<br>
**scraper video *(category name) (page #)*** - scrapes all the videos from JAVLibrary with a category and page offset*.<br>

*Offset will allow you to not start all over scraping JAVLibrary if the scraping failed for some reason or you decide to pause it. 

## Dependencies:
[x-ray](https://www.npmjs.com/package/x-ray)<br>
[chalk](https://www.npmjs.com/package/chalk)<br>
[request-promise](https://www.npmjs.com/package/request-promise)<br>
[cloudscraper](https://www.npmjs.com/package/cloudscraper)<br>
[cheerio](https://www.npmjs.com/package/cheerio)
[better-sqlite3](https://www.npmjs.com/package/better-sqlite3)


## Notes:
This script was made mostly for my own usage, so don't expect it to get frequent updates as long as it performs it's main use case.
