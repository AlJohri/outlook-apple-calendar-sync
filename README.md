# outlook-apple-calendar-sync

This script will synchronize Outlook Calendar with Apple Calendar.

## Quickstart

```
brew install AlJohri/-/outlook-apple-calendar-sync
brew services start outlook-apple-calendar-sync
```

This will automatically start running the script every minute. Check the logs to see if its working:

```
tail -f /usr/local/var/log/outlook-apple-calendar-sync.log
```

<!--
If you are running into any errors, you can change the default options using the following environment variables:

- 'OUTLOOK_CALENDAR_NAME'
- 'OUTLOOK_CALENDAR_INDEX'
- 'APPLE_CALENDAR_NAME'
- 'DAYS_AGO'
- 'DAYS_AHEAD'

NOTE: The Outlook Calendar `name` and `index` may be different on your computer.
-->
