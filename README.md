We can also schedule Email Messages. For scheduling the mail, we will make use of the schedule package in python.

**pip install schedule**

Functions:
The below function will call the function mail every 2 seconds.
schedule.every(2).seconds.do(mail) 

This will call the function mail every 10 minutes.
schedule.every(10).minutes.do(mail)

This will call the function in every hour.
schedule.every().hour.do(mail)

Calling every day at 10:30 AM.
schedule.every().day.at("10:30").do(mail)

Calling a particular day.
schedule.every().monday.do(mail)
