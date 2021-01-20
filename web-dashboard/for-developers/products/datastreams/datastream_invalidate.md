# Datastream: Invalidate Value

Use this setting to manage the _freshness_ of the data. When enabled, the server will automatically check the timestamp of the latest value and act accordingly to settings.

**Invalidate in:** Specifies the period in seconds, minutes, or hours when data is considered fresh.

**then set:** Specifies what to do when data is no longer fresh. You have such options:

| Option | How it works |
| :--- | :--- |
| Nothing | Erases the previous value and shows nothing |
| Default | Will show `Default` datastream value is exists |
| No Data | Will show "No Data" placeholder |
| Empty | Will show "Empty" placeholder |
| -- | Will show dashes "--" placeholder |

Example: 1. A temperature Datastream is set to `Invalidate in 1 hour, then set to "--"` 2. It's 4:00 PM now, and the latest value of `3.14ºC` was received at 3:30 PM. Data is considered to be fresh, and any widget will display it. 3. It's 5:00 PM, and there was no new data since 3:30 PM \(maybe the device is no longer working\). A temperature widget in the app will show `--` because data is no longer fresh.

