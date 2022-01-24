How to create a bot for scrape top reviews of amazon product
*************************************

In this Blog Post we will make a bot with the help of Datakund Studio to scrape the top reviews of amazon product.

This bot will save the scraped data in Google Sheet.

1. Click DK extension and type "scrape_amazon_reviews" and then click "+ New Api" to create a new bot. Now click "record" to start training the bot. 

.. image:: images/ar1.*
  :width: 400
  :alt: Amazon_review_scraper

2. In the browser, open amazon.com to add the URL event.

.. image:: images/ar2.*
  :width: 400
  :alt: Amazon_review_scraper
  

3. Now, search for a keyword(eg: mouse)

.. image:: images/ar3.*
  :width: 400
  :alt: Amazon_review_scraper
  
  
4. For the page to load, lets add wait event of 3 sec. To add wait event, right click anywhere on the screen and click Datakund=>wait=>static=>3.

.. image:: images/ar4.*
  :width: 400
  :alt: Amazon_review_scraper
  
  
5. Now lets add repeat event for the bot to go to all the products one by one. To add the repeat event, right click anywhere on the screen, click Datakund=>Start repeat..

.. image:: images/ar5.*
  :width: 400
  :alt: Amazon_review_scraper
  

6. Click on the first product.

.. image:: images/ar6.*
  :width: 400
  :alt: Amazon_review_scraper
    
7. Now, click back arrow and Stop the bot.

.. image:: images/ar7.*
  :width: 400
  :alt: Amazon_review_scraper
  

8. Now create a new bot by the name "scrape_reviews" and click record to start training the bot.

.. image:: images/ar8.*
  :width: 400
  :alt: Amazon_review_scraper

9. Now, lets add 'scroll to end' event, for the bot to scroll down to reviews. For that, right click anywhere on the screen and click Datakund=>more=>scroll to end. 

.. image:: images/ar9.*
  :width: 400
  :alt: Amazon_review_scraper

10. Go the reviews section, and lets add repeat event to scrape reviews one by one. For that, right click anywhere on the screen and click Datakund=>start repeat, to add repeat event to the new bot.

.. image:: images/ar10.*
  :width: 400
  :alt: Amazon_review_scraper
  

11. Click the edit  icon on the top left corner of the extension to add output variables and click save. Like as shown in the image below. 

.. image:: images/ar11.*
  :width: 400
  :alt: Amazon_review_scraper
  
  
12. Lets scrape name, title and description of the reviews. To scrape right click on the name then click Datakund=>scrape =>text=>name, and vice versa for title and description of the review, as shown in the images below.

.. image:: images/ar12.*
  :width: 400
  :alt: Amazon_review_scraper

.. image:: images/ar12_1.*
  :width: 400
  :alt: Amazon_review_scraper

.. image:: images/ar12_2.*
  :width: 400
  :alt: Amazon_review_scraper
  
  
13. Now lets stop the training the bot(scrape_reviews) and open the first bot(scrape_amazon_reviews) and click the last event to start adding the events from there. 

.. image:: images/ar13.*
  :width: 400
  :alt: Amazon_review_scraper
  

14. Now right click anywhere on the screen, then click Datakund=>bots=>scrape_reviews, to call the bot. 

.. image:: images/ar14.*
  :width: 400
  :alt: Amazon_review_scraper
    
15. Now lets stop training the bot, and click run on the main menu, and type the keyword and then click the down button beside the run button and then click run google sheet and the  click run google sheet again once the bot is loaded.

.. image:: images/ar15.*
  :width: 400
  :alt: Amazon_review_scraper
  

 16. Now click open sheets button to open, after opening google sheets, click output sheet at the bottom of the sheet. As shown below all the data is scraped.

.. image:: images/ar8.*
  :width: 400
  :alt: Amazon_review_scraper