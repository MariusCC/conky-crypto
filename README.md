Conky Crypto
=============

Material Design conky with horizontal layout to monitor your favourite crypto currencies using CoinMarketcap API.

Light background
![alt text](conky2.png "Conky on light desktop background")

Dark background
![alt text](conky.png "Conky on dark desktop background")

## Currency conversion

Update the crypto.conf file with whatever coins you want to monitor. Use the https://coinmarketcap.com/coins/ name for each.
If you don't like the text colors you can easily mess up with them in the template file.

## Installation

The install script will create (if not already existing) ~$HOME/.conky/crypto and it will add one .rc per currency. Will also add the conky start script to Gnome auto-start.

```
./install
```

Inspired by [this](http://www.omgubuntu.co.uk/2013/05/google-now-themed-conky-for-ubuntu-desktop) and [this](https://www.omgubuntu.co.uk/2016/02/run-multiple-conky-scripts-same-session).
