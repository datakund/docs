How to create Amazon Product Result Page Scraper Bot
*************************************

In this Blog Post we will make a bot with the help of Datakund Studio to scrape the product information from Amazon Search Result Product Page.
This bot will save the scraped data in Google Sheet.

1. First we'll enter name of the bot “amazon-scraper”. After that click on “+ New Api”  button to create a new bot. 

.. image:: images/apr1.*
  :width: 400
  :alt: Amazon_product_scraper

2. Now click "record" to train the bot and then click keyboard button  to add variables. 

.. image:: images/apr2.*
  :width: 400
  :alt: Amazon_product_scraper
  

3. Now add the input and output variables and click "save" button. Now click  button to go back to the training.

.. image:: images/apr3.*
  :width: 400
  :alt: Amazon_product_scraper
  
  
4. Now right click anywhere on the browser windows, click Datakund =>more=>input=>variables=>amazon_url=>open Link. This will open the given input link in the browser. 

.. image:: images/apr4.*
  :width: 400
  :alt: Amazon_product_scraper
  
  
5. Page should redirects to a page which is shown below, now stop the training for aprnce(click  button to stop training), and open amazon search results page to train the bot.   

.. image:: images/apr5.*
  :width: 400
  :alt: Amazon_product_scraper
  

6.  After opening the Amazon search result page, we will strat training the bot again. Click DK extension, and click record and then click the last recorded event to continue training the bot from that event.

.. image:: images/apr6.*
  :width: 400
  :alt: Amazon_product_scraper
    
7.Now lets train the bot to scrape the date repeatedly, for that we need to add repeat action, for that press alt+p to add repeat event.

.. image:: images/apr7.*
  :width: 400
  :alt: Amazon_product_scraper
  

8. After adding the repeat event, right click on the title of a product click Datakund=>scrape=>text=>title, to scrape the title.   

.. image:: images/apr8.*
  :width: 400
  :alt: Amazon_product_scraper

9.  Lets Scrape similarly for Price and Link.

.. image:: images/apr9.*
  :width: 400
  :alt: Amazon_product_scraper
    
10.Now stop the training and click "Run" in the menu as shown below.

.. image:: images/apr10.*
  :width: 400
  :alt: Amazon_product_scraper
  

11.  Now enter the amazon link in the box below and  click the arrow beside run, and click "Run Google Sheet", wait for the bot to load and click "Run Google Sheet" again.

.. image:: images/apr11.*
  :width: 400
  :alt: Amazon_product_scraper
  
12.  Now enter the amazon link in the box below and  click the arrow beside run, and click "Run Google Sheet", wait for the bot to load and click "Run Google Sheet" again.

.. image:: images/apr12.*
  :width: 400
  :alt: Amazon_product_scraper