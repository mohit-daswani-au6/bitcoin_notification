## BITCOIN NOTIFICATION ALERT APP
-----------------------------------------------------------------------------------------------------------------------------------------------

This is a python script project, bitcoin price notification to get notified for the regular updates of bitcoin price on google sheets,Email and telegram. 
The aim is to push notifications when the price of bitcoin changes at certain time interval, user can specify the time interval. By default time interval and threshold are set to 0.1 in minutes and $10000 respectively.
When the conditions in the program are satisfied the trigger is fired and user will recieve notifications on slack, gmail and telegram.


-----------------------------------------------------------------------------------------------------------------------------------------------
## DESCRIPTION 
-----------------------------------------------------------------------------------------------------------------------------------------------

Bitcoin price is a fickle thing. You never really know where it’s going to be at the end of the day. So, instead of constantly checking various sites for the latest updates, let’s make a Python app to do the work for you.

We’re going to use the popular automation website IFTTT.

We’re going to create there IFTTT applets:

One for emergency notification when Bitcoin price falls under a certain threshold and
one for regular Telegram and one for Email updates on the Bitcoin price and last for saving it in google sheets.

These will be triggered by our Python app which will consume the data from the Coindesk API.

An IFTTT applet is composed of two parts: a trigger and an action.

Trigger will be a webhook service provided by IFTTT.

Our Python app will make an HTTP request to the webhook URL which will trigger an action. Now, this is the fun part—the action could be almost anything you want. IFTTT offers a multitude of actions like sending an email, updating a Google Spreadsheet and even calling your phone.


-----------------------------------------------------------------------------------------------------------------------------------------------
Following query on terminal will provide you with all the help options 

### INPUT
bitcoin-notification.py -h

### OUTPUT 
usage: bitcoin-notification.py [-h] [--d decision] [--i interval]
                               [--u upper threshold]

Bitcoin Notification Alert

optional arguments:
  -h, --help           show this help message and exit
  --d decision         Enter (Yes/No) - Yes will run the program
  --i interval         Enter time interval
  --u upper threshold  Set upper threshold limit in USD for notification


bitcoin-notification-f --d=Yes --i=0.1 --u=10000

This will provide 5 prices of Bitcoin, at the specified time interval according to the code.


-----------------------------------------------------------------------------------------------------------------------------------------------
## TELEGRAM CHANNEL INVITE LINK - 
-----------------------------------------------------------------------------------------------------------------------------------------------

YOU ARE MOST WELCOME! SEE YOU THERE!
https://t.me/Bitcoin9870


-----------------------------------------------------------------------------------------------------------------------------------------------
## CONTRIBUTIONS
-----------------------------------------------------------------------------------------------------------------------------------------------

Updates are always welcome, feel free to drop your suggestions! 
Looking forward for your contribution. ❤️

-----------------------------------------------------------------------------------------------------------------------------------------------

