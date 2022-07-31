# RSI-Divergence-BTC

RSI divergence detector finds regular and hidden bullish and bearish divergences for BTC data from Binance API.

The trades are stored in a json file in the following format:

'''json
  'start_dtm': Start Time of the divergence,
  'end_dtm': End Time of the divergence,
  'rsi_start': RSI at the beginning of the divergence,
  'rsi_end': RSI at the end of the divergence,
  'price_start': Price at the beginning of the divergence,
  'price_end': Price at the end of the divergence,
  'type': 'bullish/bearish (hidden or not)'
'''

Detected signals of RSI divergences for BTCUSDT pair during 22.11.2020 - 22.07.2022 period in daily timeframe are visualized:

![alt text](https://github.com/mertcan79/RSI-Divergence-BTC/blob/main/img/rsi.JPG)

# Result 

Based on the different kinds of signals, the profit for each of them are found as :

Hidden Bearish: 91075$
Bearish: -30391$
Hidden Bullish: 0 (No such type were detected in the timeframe)
Bullish: 9679$
