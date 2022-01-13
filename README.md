# logger.py

## Usage
### Install Requests
`pip3 install requests`

### Using in Your Code
```py
from Logger import logError, logWarning, logInfo, logDiscord

logInfo("Hello World")
logWarning("Hello World")
logError("Hello World")
logDiscord("Hello discord")
```

## Conifguration
Go to logger.py then change the constants. 
### Webhooks
To yurn on webooks (i.e: discord) turn `USE_WEBHOOK`to True and set `WEBHOOK` to the webhook URL. By default only errors are sent to the webhook. But you can use 
`logDiscord(str)` at any time.
