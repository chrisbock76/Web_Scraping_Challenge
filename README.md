# Web_Scraping_Challenge
CWRU Bootcamp Homework12


The mission_to_mars_clean.ipynb (Jupyter Notebook) contains all of the intial scraping activities done utilizaing pandas. Twitter scrape was initially successful, but ulimately failed because of the JavaScript code that is being used for the webpage.  Twitter scrape methods have been made to circumvent this issues (such as Tweepy's Twitter API or twitterscraper) 

A MongoDB was created titled mars_scraperDB with a collection titled Mission_To_Mars, where the data were initially collected and stored when app.py was first run.  Note, when app.py is first run, in order to populate the columns and effectively create the database, one must use /Scrape after the webpage is started

Contained within the 'mars' folder in the repo:

* mars_scraper.py (contains the functions used for the scraping.  The twitter section was commented out because of the error mentioned above.  This caused the code to hangup and not continue with additional scraping)
* app.py (the final app containing Flask to visualize the results)
* chromedriver.exe (utilized for splinter applications during browser initialization in web scraping)
* 'templates' folder (contains the index.html file for rendering the scrape results)

Contained within the 'Images' folder:

* 4 screen shot PNG files of the final product
