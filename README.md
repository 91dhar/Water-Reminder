# Water Reminder application

A simple reminder application built on Python to remind you to drink water. Yes, drink water.

## Installs
 
`py -m pip install plyer`

## Imports

`import time`

`from plyer import notification`

## Functionality

`timeout` denotes the seconds for which the notification popup will stay on. You can edit the same in the code.

`time.sleep(60*60)` denotes the intervals. Here it is 60 seconds * 60 mins. Notificaton window will popup every 1 hour.

`pythonw .\app.py` in the integrated terminal will make this application run in the background. Can kill the process from Task Manager.



### Note

Had run into the following error.

SyntaxError: (unicode error) 'unicodeescape' codec can't decode bytes in position 2-3: truncated \UXXXXXXXX escape.

`Solution`: Just put r before your normal string. It converts a normal string to a raw string.
