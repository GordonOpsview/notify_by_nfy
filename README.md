# notify_by_ntfy

A notification script for Ntfy (https://ntfy.sh/) as a notification method. 

Use the command: `notify_by_nfy -u URL -t TOPIC -k TOKEN [-d]`


### Example using an Opsview Variable:
Variable: __NTFY__
- Arg1 : URL
- Arg2 : Topic
- Arg3 : Token
- Command: `notify_by_nfy -u "%NTFY:1%" -t "%NTFY:2%" -k "%NTFY:3%"`


### To get an auth token:
- Log in to your ntfy server
- Go to Account settings
- Click on __Create Access Token__


### Relevant documentation:

- Set up an Opsview variable: https://knowledge.opsview.com/docs/variables
- Opsview notification methods: https://knowledge.opsview.com/docs/customized-notification-methods
- Official ntfy docs: https://docs.ntfy.sh/
