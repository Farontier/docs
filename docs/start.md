---
id: start
title: SparkPool API Document
sidebar_label: start
---

The document is introduce how to integrated with [SparkPool](https://www.sparkpool.com) API.

## Begin

### Host

```
www.sparkpool.com
```

### API Prefix

```
/v1/miner
/v1/bill
/v1/worker
```

### DEMO

```
// request
curl -H 'content-type: application/json' https://www.sparkpool.com/v1/pool/stats

// response
{
   "code":200,
   "data":[
      {
         "pool":"SPARK_POOL_CN",
         "currency":"ETH",
         "income":0.01157,
         "meanIncome24h":0.01191,
         "incomeHashrate":"100000000",
         "blocks":1821,
         "hashrate":"56642502013889",
         "miners":8210,
         "workers":256578,
         "usd":377.785287,
         "usdDiff":0.028825,
         "cny":2558.399742,
         "cnyDiff":0.021584,
         "networkHashrate":"244230169415375",
         "diff":0.0006
      },
    ...
   ]
}
```

## Contrat us

1. wechat: 星火矿池 / SparkPool
2. email: dev@sparkpool.com
3. [Twitter](https://twitter.com/sparkpool_eth)
4. [telegram](https://t.me/Ethersparkpool)
