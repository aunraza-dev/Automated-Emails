We can also schedule Email Messages. For scheduling the mail, we will make use of the schedule package in python.

**pip install schedule**

The below function will call the function mail every 2 seconds.
**<br>schedule.every(2).seconds.do(mail)</br>** 

This will call the function mail every 10 minutes.
**<br>schedule.every(10).minutes.do(mail)</br>**

This will call the function in every hour.
**<br>schedule.every().hour.do(mail)</br>**

Calling every day at 10:30 AM.
**<br>schedule.every().day.at("10:30").do(mail)</br>**

Calling a particular day.
**<br>schedule.every().monday.do(mail)</br>**
