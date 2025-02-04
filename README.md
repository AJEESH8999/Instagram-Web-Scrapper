# Instagram-Web-Scrapper
Creating an Instagram scraper involves extracting profile and post data (usernames, bios, follower counts, posts), searching posts via hashtags. Python tools like BeautifulSoup, Scrapy scrape; Selenium automates. Ethical: follow Instagram's terms, respect privacy, manage API limits to avoid blocks, adhere to platform guidelines.


This repository contains a Python script for scraping Instagram data, focusing on extracting profile information, post details, and hashtag searches.

## Features

- **Profile Data Extraction:** Retrieve usernames, bios, follower counts, and more.
- **Post Data Extraction:** Capture post captions, image URLs, likes, comments, and timestamps.
- **Hashtag Search:** Collect posts associated with specific hashtags.
- **Automation:** Use Selenium for automating interactions like scrolling, clicking, or posting.

## Requirements

- Python 3.x
- Dependencies listed in `requirements.txt`

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AJEESH8999/Instagram-Web-Scrapper/tree/main
   cd Instagram-Web-Scrapper
2. Install Required Libraries
   ```bash
   pip install -r requirements.txt
## Download WebDriver
 - Download the appropriate WebDriver for the browser you intend to use. For example:

 - ChromeDriver
 - GeckoDriver (Firefox)
 - Make sure the WebDriver executable is in your system's PATH, or specify its location in your code.
## Key Components Explained
 - WebDriver Initialization: Create an instance of the WebDriver for your browser.
 - Navigating to a URL: Use the get() method to open a web page.
 - Finding Elements: Use methods like find_element_by_name, find_element_by_xpath, etc., to locate elements on the page.
 - Interacting with Elements: Methods like send_keys() and click() allow you to interact with elements.
 - Waiting: Use time.sleep() for simple waits, but for more robust waiting, use WebDriver's explicit waits.
 - Closing the Browser: Use quit() to close the browser once your tasks are complete.
