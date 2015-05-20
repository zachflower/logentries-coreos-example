## LogEntries Token

To generate a LogEntries token for CoreOS, log into your LogEntries dashboard and add a "Manual" log.

![LogEntries Token](https://photos-1.dropbox.com/t/2/AAB_TqTvR68K7HHEc8RXKYJMakBaYC0bQUZ565Ap_QkZyg/12/593441/png/1024x768/3/1432098000/0/2/Screenshot%202015-05-19%2021.23.47.png/CKGcJCABIAIgAyAEIAUgBigBKAI/cVo-4jW23DAeV3wbNNm8y4T0qp8hQdrgf5NTdWdj5C4)

Setup the "Log Name" and "Set" to your preferences, but make sure that "Token TCP" is selected as the log sending method.

![LogEntries Token](https://photos-6.dropbox.com/t/2/AADlwisD-5pzZoKleCAPcEZ7cWXC22JRXXn5orThcOHrxQ/12/593441/png/1024x768/3/1432098000/0/2/Screenshot%202015-05-19%2020.22.18.png/CKGcJCABIAIgAyAEIAUgBigBKAI/k47zBn0sGCgziZe45Hm_yQO1i2NnFTxsYGwDSRutCJM)

Click "Create Log Token" at the bottom of the page, and your LogEntries Token will be shown.

## Example Setup

If you would like to use this example code directly, you'll have to setup your keys.

### user-data

Edit the `./user-data` and replace the second occurrance of `LOGENTRIES_TOKEN` with your LogEntries token.

## Requirements

[Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/) are both required to run this example.

## Running

Navigate to your `logentries-coreos-example` folder in a terminal and type the following:

`vagrant up`

What that will do is start your CoreOS Vagrant instance. If you've configured LogEntries correctly, you should start seeing something like this in your LogEntries dashboard:

![LogEntries Logs](https://photos-4.dropbox.com/t/2/AAAcn025H8rzu7-eU2rYbaZUm_rJW1d5OcJmwdzTamkBag/12/593441/png/1024x768/2/_/0/4/Screenshot%202015-05-19%2020.35.05.png/CKGcJCABIAIgAyAEIAUgBigBKAI/in97z1kasriw058/AAARTAaFoJnJjjFxMqfjzdhKa/Screenshot%202015-05-19%2020.35.05.png)
