# outlook-apple-calendar-sync

This script will synchronize your Outlook Calendar with Apple Calendar.

## Quickstart

```
brew install AlJohri/-/outlook-apple-calendar-sync
brew services start outlook-apple-calendar-sync
```

This will automatically start running the script every minute. Check the logs to see if its working:

```
tail -f /usr/local/var/log/outlook-apple-calendar-sync.log
```

## Configuration

The Outlook Calendar `name` and `index` may be different on your computer.

If you are running into any errors, you can change the default options using the a configuration file at `'~/.config/outlook-apple-calendar-sync.json'`.

You can set any of the following options:

```
{
    "outlookCalendarName": "Calendar",
    "outlookCalendarIndex": "1",
    "appleCalendarName": "Outlook Sync",
    "daysAgo": 1,
    "daysAhead": 7
}
```

## Start/Stop/Uninstall/Update

- Start Service: `brew services start outlook-apple-calendar-sync`
- Stop Service: `brew services stop outlook-apple-calendar-sync`
- Uninstall: `brew uninstall outlook-apple-calendar-sync`
- Update: `brew update && brew reinstall outlook-apple-calendar-sync`
