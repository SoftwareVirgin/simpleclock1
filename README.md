# simpleclock1

import datetime #import for datetime function

now = datetime.datetime.now() #this will hold the date and time

print("Current date and time : ") # prints out current date and time

print(now.strftime("%Y-%m-%d %H:%M:%S")) #prints it out in year, month, date, and Hour,Minute,Second
