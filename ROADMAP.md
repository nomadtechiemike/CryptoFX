# ROADMAP

## 2.0.0 - Expected : Before end 2017 ? 
* CryptoFX-Mobile : Using Onsen, Cordova and Angular ? 
* Use the lending system in order to gain benefit can expect a 0.02% rate for 2Days (If i made this [Spreadsheets](https://docs.google.com/spreadsheets/d/1k1xu97SYNyJL7alMIsPpcDy87L3-fM_KLuZmwXlvrMY/edit?usp=sharing) right, it can be profitable)

## 1.0.0 - Expected : 01/01/2017
* Ability to a trade in a specific market in a totally automated manner using MarketSignals combination
* Ability to access to the CryptoFX Dashboard/Front (Meteor App on a separate CryptoFX-App ?).
* Ability to run specific configuration for each user.
* Abiility to backtest.
 
## 0.2.0 - Expected : 15/10/2016
* [DATABASES] One for MIB, one for MAB, One for users purpose.
* Ability to get past data from poloniex, 
* Dissociate SmartAnalyst from MAB (which should only add candle from scratch or refreshing with new data).

## 0.1.0 (Since 04/10/2016: [0.1.0](https://github.com/Alex-Werner/CryptoFX/tree/0.1.0) )
* [Indicators] EMA, TSI, SMA
* [MarketSignals] GoldenCross, DeathCross

## 0.0.1
* [FETCHER] Ability to get tick from Bittrex and Poloniex
* [MAB] Ability to get data from MIB and transform tick into candle
* [MIB] Ability to store tick and responds all data or lastPrice of specific market


# Todos 

## 0.2.0
- [ ] Make MIB a candle store and not a tick store anymore
- [ ] Being able to handle tick or candle as an import way
- [ ] MarketExchange : BTC China as it has it's allow import data
- [ ] External API for CryptoFX Front
- [ ] Make Candle creator Generic
- [ ] Dissociate SmartAnalyst from MAB
- [ ] Make SmartAnalyst more generic
- [ ] Candle + SmartAnalyst should not re-calculate from begining, instead they should process only unprocessed tick
- [ ] Being able to fetch old data from a market (let's say poloniex) and add missing data into database 
- [ } Make above generic
- [ ] Setup database driver (for MongoDB - we will have 2.3 Billions entries possible but 10/20ms latency). 


## 1.0.0 

Indicators : 
- [X] Simple Moving Average
- [ ] Exponential Moving Average
- [ ] Weighted Moving Average
- [ ] Moving Average Convergence Divergence
- [ ] Moving Average Convergence Divergence Histogram
- [ ] Bollinger Bands
- [ ] Average True Range
- [ ] Relative Strength Index
- [ ] Wilder's Smoothing (Smoother Moving Average)
- [ ] Rate of Change 
- [ ] Know sure Thing
- [ ] Stochastic 
- [ ] WilliamsR
- [ ] Accumulation Distribution Line
- [ ] On Balance Volume
- [ ] TRIX

Market Signals : 

- [X] Death Cross
- [X] Golden Cross
- [ ] Crossover
- [ ] Moving Average Ribbon
- [ ]

Supra Signals : 

```This should used a bunch of Indicators and Market Signals, and learn from them, changing it's own variable to find the best weight to put to all different factor```
```Supra Signals should be able to write their own, we will called that : Writing Strategy```

- [ ] CryptoSignals (Should be our most advanced one, will document that late)
- [ ] Optimistic 
- [ ] Pessimistic