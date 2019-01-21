# ccxt-usage python version

ccxt - 一个支持超过百种数字货币交易开源库 | 支持 JavaScript, Python 和 PHP 语言
A JavaScript / Python / PHP cryptocurrency trading library with support for more than 130 bitcoin/altcoin exchanges
https://github.com/ccxt/ccxt



#### 获取支持的交易所 
```

print (ccxt.exchanges)
```

#### 获取交易所支持的币种交易

```

for symbol in btcbox.markets:
        print(symbol)
```


#### 获取所有币种交易 

```

if btcbox.has['fetchTrades']:
        for symbol in btcbox.markets:  # ensure you have called loadMarkets() or load_markets() method.
            time.sleep (btcbox.rateLimit / 1000)  # time.sleep wants seconds
            print (symbol, btcbox.fetch_trades(symbol))
```
* fetch_orders 什么意思？
