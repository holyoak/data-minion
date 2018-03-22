![](https://github.com/holyoak/cryptominion/blob/master/src/client/assets/logo.svg)
# data-minion

> collecting crypto price data

### Steps to creating a base dataset

- First, check out your api docs
- Is is a ws or REST?  Build a handler to suit
- is the data raw trade or candles?
- ID your target market
- claim your market and note the data type on the project wiki
- Start recording your target market, noting the timestamp
- Start polling the market history in 2 sec intervals from the timestamp backwards
- Make sure to catch errors and let them bubble up!




### Eight API starting points

- Binance: node   - https://www.npmjs.com/package/node-binance-api
-          python - python-binance.readthedocs.io/en/latest/binance.html
- Bitflyer:https://lightning.bitflyer.jp/docs?lang=en
- Bittrex: https://bittrex.com/home/api
- Bitstamp:https://www.bitstamp.net/websocket/
- GDAX: https://docs.gdax.com/
- Gemini:https://docs.gemini.com/
- Kraken:https://www.kraken.com/help/api
- Poloniex: https://poloniex.com/support/api/