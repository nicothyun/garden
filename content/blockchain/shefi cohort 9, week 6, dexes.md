---
draft: true
---
Crypto enables permission-lessness by replacing humans with codes.

A new class of exchanges emerged where:
1. Token listings can be done without lengthy negotiations with exchanges
2. Trades no longer require the participation of human counterparties
3. Market makers can be less sophisticated. 

**Key components of an exchange**
1. **Parties:** Sellers and buyers
2. **Medium:** Money, cryptocurrency and goods
3. **Platform:** Physical venue or digital platform
4. **Pricing:** Supply and demand
5. **Liquidity:** Ease of buying and selling
6. **Settlement:** Delivery and payment mechanisms
7. **Fees:** Cost for using the exchange

**What's the purpose of financial exchanges?** 
- **Companies** to (1) raise capital by selling shares for the purpose of expansion, research and other business activities 
- **Individuals** want to (2) invest in stock market to have more money and for (2) income generation to buy stocks low and sell high, (3) liquidity (platform where traders can easily swap out of stocks to cash) and (4) diversification where investing in multiple stocks can diversify portfolio and reduce risks 

**Why do traders buy and sell on exchanges?** 
1. Fluctuating prices 
2. Constant price movements create economic opportunities for traders

**CEX & DEX** 
- CEX: Binance, Coinbase
	- *Pros:* Users not managing keys, easy to exchange fiat to crypto, insurance and accountablity
	- *Cons:* Single point of attack, KYC, "not your keys and not your crypto", fees 
- DEX: Uniswap - there's no listing process and anyone can list a token. 

**Types of DEX:** 

# Orderbook vs AMM
Orderbook: facilitating trades between two humans.
AMM: Uses algo and liquidity pools 

1. Order book-based
	1. **Central Limit Order Book Exchanges (CLOB)**: a system where buy and sell requests are listed and matched based on their price and this system requires **market makers** (place limit orders, trades at specific prices) and **market takers** (place market orders, trades that execute immediately)
	2. Order book matches trades based on their price
	3. No order flow if there are no trades without makers and takers
	4. There must be two counterparties (buyers and sellers) for a trade to execute.
	5. CLOB matches makers and takers and this needs human counterparties or else the system does not work. 

**Market makers**
- Market makers place limit orders for tokens and they prioritize price. They place orders ahead of time to be fulfilled at anytime. 
	- Set orders in advance, waiting for someone to match their price at a later time. 

**Market takers**
- Takers place market orders to buy or sell tokens at any price, prioritizing immediacy
- Speed over price and get matched with best available limit orders
- Takers are looking for quick trades and are willing to accept current market prices. 

**Order Book DEX**
1. IDEX
2. dYDX
3. Ocean Protocol 

**Automated Market Makers** are a new class of exchange where token listings can be done without lengthly negotiations with exchanges. 
- Trades no longer require participation of human counterparties.
- Market makers can be less sophisticated as the MM algorithim is provided by smart contract codes. 

Key components of an automated market makers:
1. Liquidity pools
2. Traders
3. Liquidity providers

**Key features:**
- Trades are priced based on the ratio of tokens in a pool.
- There are no limit orders and therefore no order book. 
- Deploy smart contracts to act as a market maker in an exchange transaction. 
- Smart contracts aka liquidity pool will always 24/7 execute buy and sell orders
	- Aka smart contracts are the guaranteed counterparty
	- No need to wait for 2 human counterparties. 
- Rely on mathematical formulas to set the price of a token and to quote prices between two assets for trades
	- E.g Uniswap V2 implements a constant product formulae: #X * #Y = K to price assets

**Why is this important?**
- Anyone, anywhere in the world can list a token and create a market for it
- It eliminates trusted intermediaries and unnecessary forms of rent extraction, allowing for safe, accessible, and efficient exchange activity
- E.g Uniswap is seen as a standard for AMM

**What can you do on an AMM Exchange?**
- Swap ERC20 to ERC20 tokens
- Swap ETH to an ERC20 tokens, and vice versa
- Contribute tokens to liquidity pools (as a maker) and be rewarded with exchange fees
- List a token on token and create your own liquidity pool for it 

**Liquidity pools:** 
- smart contract = liquidity pool
- each AMM smart contract manages the two ERC-20 tokens in the price
- Price of a token in a pool is based on the % of each token in it
- anyone can supply tokens to a pool aka be makers
- when you supply tokens to a pool, you are financially rewarded with trading fees
- *Why use liquidity pools?* Order books are not the native architecture for implementing a permissionless liquidity protocol on a decentralized open blockchain
- Capital/money/tokens are critical to an exchange's success. 

***Where does Uniswap's liquidity come from?***
1. anyone anywhere in the world can supply a pair of tokens to a liquidity pool
2. Uniswap incentivizes people to provide liquidity by rewarding them with fees
3. all of the capital is supplied by people and it needs to be supplied in ratio

***Liquidity providers***
- Supply tokens to Uniswap makes a person a liquidity provider
- Anyone can supply liquidity and be rewarded for it
- Liquidity (deposits) can be added and removed(withdrawn) at any time

**Takeaways:** 
- Crypto enables permissionless-ness by replacing humans with code.
- Token listings can be done without lengthy negotiations with exchanges
- Trades no longer require the participation of human counterparties
- MM can be less sophisticated
