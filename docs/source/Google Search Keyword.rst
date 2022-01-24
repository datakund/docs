How to Scrape result count for all the keywords given?
*************************************

To make a bot which searches keyword on google.com and scrapes its result count, follow these steps:-

1. To create a new bot, click DK extension and type "google_count" and then click " + New Api".

.. image:: images/g1.*
  :width: 400
  :alt: Alternative text

2. Now open google.com in the browser before training the bot, and click "Record" to train the bot.

.. image:: images/g2.*
  :width: 400
  :alt: Alternative text
  

3. Now click  button to add output variable and click "save".

.. image:: images/g3.*
  :width: 400
  :alt: Alternative text
  
  
4. Reload the page to add the URL to the event.

.. image:: images/g4.*
  :width: 400
  :alt: Alternative text
  
  
5. To train the bot to search a keyword, first type a keyword(eg: dog) in google search and press enter.

.. image:: images/g5.*
  :width: 400
  :alt: Alternative text
  

6.  Now right click on the results count, then click Datakund=>Scrape=>Text=>results_count, to scrape the results count.

.. image:: images/g6.*
  :width: 400
  :alt: Alternative text
    
7. Now stop the training(by clicking ), and click "run".

.. image:: images/g7.*
  :width: 400
  :alt: Alternative text
  

8. Click the down arrow beside the run button, click "Run Google Sheet" and click "Open Sheets". 

.. image:: images/g8.*
  :width: 400
  :alt: Alternative text

9. Google Sheets will open and then type all the input keywords from the 3rd row, and close the sheets.

.. image:: images/g9.*
  :width: 400
  :alt: Alternative text
    
10.Now go back to the browser and click "Run Google Sheet", and wait for the bot to run and click open sheets.

.. image:: images/g10.*
  :width: 400
  :alt: Alternative text
  

11. Now click on “Google Sheet” button and you can see the below image, that our bot scraped all the search count.

.. image:: images/g11.*
  :width: 400
  :alt: Alternative text