## LogEntries Token

To generate a LogEntries token for CoreOS, log into your LogEntries dashbaord and add a "Manual" log.

![LogEntries Token](https://www.dropbox.com/s/z5kvhezpi746w4e/Screenshot%202015-05-19%2021.23.47.png?dl=0)

Setup the "Log Name" and "Set" to your preferences, but make sure that "Token TCP" is selected as the log sending method.

![LogEntries Token](https://www.dropbox.com/s/nllv5gnhxtziwgs/Screenshot%202015-05-19%2020.22.18.png?dl=0)

Click "Create Log Token" at the bottom of the page, and your LogEntries Token will be shown.

## Example Setup

If you would like to use this example code directly, you'll have to setup your keys.

#### user-data

Edit the `./user-data` and replace the second occurrance of `LOGENTRIES_TOKEN` with your LogEntries token.
