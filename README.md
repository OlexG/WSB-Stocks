# WSB-Stocks
A python program which scrapes the r/wallstreetbets subreddit for stock tickers and lists them from most popular to least popular.
## Instructions for use
Visit https://www.reddit.com/prefs/apps and create an app. Make sure the app is of type script and the redirect link is http://localhost:8080/. Replace "your_id" on line 8 with the letters under "personal use script". Replace "your_secret" with the secret. Replace "your_bot_name" with the name of the bot app you made. Type in "pip install praw" in console and any other packages you don't have. After this just run the python script (if import praw doesnt work you can replace the file path being added to sys.path with the installation path. You can find the installation path with pip show praw).
