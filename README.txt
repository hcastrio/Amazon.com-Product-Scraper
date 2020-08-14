Amazon Price Monitor(WebScraper}
----------------------------------------------

What is used:
----------------------------------------------
This project is made with python and 
selenium.

Why this way?
---------------------------------------------
If you use requests amazon will block 
you but if you do it this way they will
not. Also you wont have to deal with
the html changing which amazon does 
alot. 

What the program does:
----------------------------------------------
1. Opens the browser
2. Goes to amazon.com
3. Goes into the search bar
4. Inputs the item we are looking for
5. Then it will scrape the unique link from each item that pops up from our search
6. Now we will have a huge list of all of the unique links that we scraped
7. Then we will loop through each link and scrape data from each product and save
    it in memory(reports folder)
8 The data that is scraped will be the title, the unique ID located in the URL, price, 
   and seller.
9. The program will return a Json file with mainly all the products between the price
    range we selected and they will be in increasing order. 

To Run it do type on command line:
-----------------------------------------------
1. .\venv\Scripts\activate
2. pip install -r requirements.txt
3. python simple_scraper.py




