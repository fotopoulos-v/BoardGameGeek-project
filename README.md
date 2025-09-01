
Data scraping from the website: "www.boardgamegeek.com" and creation of four csv files about board games which create a small database.
These four csv files contain information about the board games ratings, types, minimum and maximum number of players, price, their designers, publishers, artists etc. 
Total number of pages/board-games scraped for each csv file: around 25200.

> It is Python code in a Jupyter notebook. It uses the following libraries:
>>Pandas, Beautiful Soup, Selenium.

+It is working in Linux Ubuntu but should also work in any other Operational System.
+It opens the page www.boardgamegeek.com in a Chrome browser, it clicks the sign-in button, it enters the user's credentials and then scrapes the specified number of pages and scrapes the information inside them and stores it in csv files.
 
