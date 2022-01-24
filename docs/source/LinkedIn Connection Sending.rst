How to send connection requests to all profiles in search results in all pages
*************************************
To make a bot which searches keyword on Linkedin and send connection requests to all profiles in search results follow these steps:-


1. First you have to enter the name of the bot “LinkedIn Connect Bot”. After that click on “+ New Api” button then click on record to train the api.

.. image:: images/link1.*
  :width: 400
  :alt: Alternative text

2. Now open LinkedIn.com, it will record LinkedIn URL event in training.

.. image:: images/link2.*
  :width: 400
  :alt: Alternative text
  

3. Apply static wait for 3 sec so that site can load. To add wait
Right Click >DataKund > More > Wait > Static sleep > 3 (for 3 seconds)

.. image:: images/link3.*
  :width: 400
  :alt: Alternative text
  
  
4. Now click on LinkedIn search field, type any profile name let’s suppose “Divya”, press “Enter” to get the search results then apply 3 sec wait and filter by people.

.. image:: images/link4.*
  :width: 400
  :alt: Alternative text
  
  
5.  Click on dk extension, check events and exit training.

.. image:: images/link5.*
  :width: 400
  :alt: Alternative text
  
To send the connection request we have to make a new bot first whose work only to send connection request.
Follow These Steps:-

1.Enter the name of the bot like 'send connection bot'. After that click on “+ New Api” button then click on record to train the api.

.. image:: images/link6.*
  :width: 400
  :alt: Alternative text
    
2. Select 2-3 profile and add repeat. Right click > Datakund > Start Repeat

.. image:: images/link7.*
  :width: 400
  :alt: Alternative text
  

3. Now click on Connect > Send connection to the first profile in list then Right click > End Repeat and Click on Next at the bottom of page.

.. image:: images/link8.*
  :width: 400
  :alt: Alternative text

4. Now trigger this bot itself as part of training. Right Click > Bots > click on Send connection Bot (2nd Created Bot) and exit the record.

Resume the training of the first bot whose training was paused.
5. Go Back LinkedIn Connect Bot, Click on record and trigger send connection bot (2nd created bot). Exit Record and Run the Bot.

.. image:: images/link9.*
  :width: 400
  :alt: Alternative text