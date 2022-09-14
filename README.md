# Ethereum-Health-Monitor

A monitoring application on NodeJS to track core Ethereum infrastructure

![Ethereum Health Monitor](https://user-images.githubusercontent.com/62826108/190055601-71660de8-c0b8-4ce6-8e75-a4f56718c824.jpg "EthMonitor.js")

Built to keep an eye on the network during the merge update.

Tracks:
- infura
- alchemy
- etherscan (web & API)
- flashbots relay
- block transactions
- gas price
- Binance ETH/USDT bid price
- FTX ETH/USD bid price

Console based but all data is stored in a single object so could be extracted to JSON fairly easily.

```
npm install
npm start
```
