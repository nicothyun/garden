- Account abstraction is a proposal seeking to improve user interactions with Ethereum.
	- **abstraction**: in cs, it roughly means hiding info about a system or application so it can be used with less knowledge of the processes running in the background
	- **account**: user's representation on the blockchain that can send or receive transactions and interact with other on-chain accounts.


- helps to pave the way for wider adoption of trustless, censorship-resistant smart accounts where programmable, self custodial accounts ("smart accounts") can reduce the friction of onboarding new users to the web3 ecosystem. 

**mechanics:**
1. *Externally Owned Account (EOA)*: managed by cryptographic pair of public and private key. it can initiate transactions and pay gas fee
2. *Contract accounts*: Controlled by logic written in code. It is programmable and can execute arbitrary logic depending on code stored at the address but it cannot pay gas fees and originate transactions. 

**objectives:**
- simplify experience of using web3 where wallets become invisible - will feel like using a bank account without having to trust the bank because it is still self custodial 
- brings web3 wallet experience closer to web2 

**different kind of abstractions?**
1. implementing *signature abstraction* allows for more advanced authorization schemes to solve problems and drawbacks of EOAs. 
	1. E.g. Wallet linked to smart account can reject a transaction (or request for additional authorization) if the value exceeds a preset limit. 
	2. E.g. multi party approvals before funds can be withdrawn from the smart account. 
	3. E.g. using Dapp with session keys 

2. implementing *fee abstraction* abstracts away details of how and when users choose to pay for gas. e.g it can be sponsored by another account to cover the cost of gas
	1. non eth gas payments where a relayer with ETH can front the cost for your transaction and you pay them back in another token such as USDC/DAI
	2. gasless transactions where dapp developers can sponsor transactions and minimize onboarding friction for new ETH users
	3. social logins for authentication infrastructure

3. implementing nonce abstraction for trxn batching 
	1. reduce cost and complexity of interacting with dapps
	2. difficult to implement in practice