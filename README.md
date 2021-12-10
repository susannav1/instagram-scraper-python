# Instagram scraper

Scrapes Instagram public profile and posts.

See https://github.com/webscraping-ai-bot/instagram-scraper-python/blob/main/webscraping_ai_instagram_scraper/spiders/InstagramAccount.py for the spider code.

Usage:

    $ scrapy crawl InstagramAccount -o output.csv -a usernames=nike,microsoft -a api_key=test-api-key

* `usernames` - comma-separated usernames of Instagram accounts to scrape
* `api_key` - WebScraping.AI API key