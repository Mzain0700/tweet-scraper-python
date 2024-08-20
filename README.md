# Nitter Tweet Scraper
This project allows you to scrape tweets from Nitter, an alternative Twitter front-end, using Python. The main functionality is encapsulated in a function that lets you easily scrape tweets from a specific user's timeline and save the data to a CSV file.

# Features
- **Scrape tweets by hashtag:** Retrieve tweets containing a specific hashtag.
- **Scrape tweets by username:** Retrieve tweets from a specific user's timeline.
- **Save data to CSV:** Export the scraped tweet data to a CSV file for further analysis.

## Getting Started

### Prerequisites

Before running the project, make sure you have the following installed:

- Python 3.x
- pip (Python package manager)

## Install Required Python Packages
pip install ntscraper pandas

## Usage
The following steps demonstrate how the scraping process works, using a specific hashtag as an example:

- **Initialize the Nitter Scraper :**
The scraper is initialized with specific configurations, such as log level.

- **Scrape Tweets by Hashtag or User :**
Scrape tweets containing the hashtag or Username.

- **Process and Save the Data :**
Extract relevant data from the scraped tweets and save it to a CSV file.

The demo is provided in the script to help you understand how the scraping works.

## Main Function: Creating a Tweets Dataset for a Specified User
- The primary functionality is encapsulated in a function that allows you to scrape tweets from a specified user's timeline and save them to a CSV file.
- The function create_tweets_dataset takes two parameters: the username of the Twitter user and the number of tweets you wish to scrape.
- Simply Change the username and limit in function call with your required profile user name using this command.
create_tweets_dataset("username", 100)
