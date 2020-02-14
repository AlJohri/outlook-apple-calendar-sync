# outlook-apple-calendar-sync

This script will synchronize some date range from your Outlook Calendar with the Apple Calendar.

## Quickstart

```
./sync.jxa
```

If the defaults do not work for you, you can pass in the following options explicitly:

```
./sync.jxa \
    --outlook-calendar-name=Calendar \
    --outlook-calendar-index=1 \
    --apple-calendar-name="Outlook Sync" \
    --days-ago=1 \
    --days-ahead=7
```

The Outlook Calendar `name` and `index` may be different on your computer.
