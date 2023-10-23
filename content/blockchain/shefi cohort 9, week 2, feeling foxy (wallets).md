---
draft: true
tags:
  - blockchain
---
**web3 wallet definitions and uses** 
- wallets allow users to manage crypto funds and
- be used as a single login to all web3 dapps and applications (web3 authentication) -> a wallet also signals to the blockchain a user is the legitimate owner of the funds and able to move them.
- vs. web2 where there are 20+ logins for 20+ applications 
- instead of companies and banks controlling the money, now you are the custodian and you control the money. you become your own bank but this comes with more responsibility and risks when managing crypto wallets

**why do we need to care about wallets**
- ownership economy starts with web3 wallet when you get control over your assets and data, which is encrypted and shared when YOU want to. 
- not your keys, not your crypto. 

**key features of a wallet**
1. seed phrase (do not share) - a secret and your recovery phrase if you lose your wallet. it is a root code of your wallet and it generates private keys for accounts. if someone has your seed phrase, they can access most of the accounts in the same wallet. 
2. public address - you can share this. this can be a qr code, string of text and is an unique identifier on blockchain for users to send funds to you. 
3. private key (do not share) - a complex form of cryptography. if they have a private key, they can unlock the specific account within the wallet. 

public and private keys work together as a pair where they allow you to send and receive tokens without requiring a third party to verify the transactions. 
- public key address for ppl to send transactions
- private key to unlock the tokens

public key cryptography ensure the authenticity and integrity of every transaction on the blockchain. 

each wallet can contain multiple accounts & wallet addresses. 

**types of wallets**
1. custodial - third party holds and manages your crypto for you. CEX and exchanges. They act like a crypto bank for you and they have control over your assets. 
	1. when you go custodial, you trust the company to handle and manage your assets
2. non-custodial - you control the assets and no one else has access but you. you trust the code and yourself. this builds towards ownership economy because you own the funds. 

**hot wallets** are software wallets, they are online and connected to internet. they can run in your web browser.
cold wallets are hardware wallets. offline and not connected to internet. 


**navigate web3 dapps with wallets**
1. you can connect wallet, approve tokens and grant permissions and sign transactions. 
2. before signing transactions, please check if you are on the right website. 
3. revoke access to your wallet via revoke.cash and etherscan.io/tokenapprovalchecker

use burner wallets for minting NFTs cause the risks of scams is higher

how does wallets enable ownership economy? 

**enabled new wallets**
- account abstration in wallets to help improve user interactions with ETH. 
	- hopes to abstract AKA hide things about wallets from like private keys and seed phrases. 
- smart accounts are controlled by code instead of a private key. 
	- users can set their own rules for login, recovery and transactions
	- social recovery - designate friends and family they trust to approve account recovery in case of lost access.
	- multi-factor authentication (MFA): additional layers of authentication such as biometric verification.
	- multi-signature authorization (multisig): transactions can be set to require signatures from multiple private keys or entities.
	- daily spending limits
	- time-locked transactions: programmed to be delayed for certain period, allowing users to cancel them if they are deducted as fraudulent or unauthorized.
	- gas payment options: allow gas fees to be paid in tokens other than native cryptocurrency. 
	- batch transactions: multiple transactions can be grouped and executed in a single batch, improving efficiency and saving on fees. 
	- conditional transactions: set to execute trxns only if certain conditions are met
	- subscription payments
