# test

In this project we have made an attempt to exactly do that, create a decentralized exchange platform.

### Dependencies / Requirements

- Truffle 
- Solidity 
- Node js
- Web3.js 
- Ganache 
- npm
- sublime text

The detailsed dependencies and there versions can be found in this file ![package.json
](./package.json)


### Initial Setup

1. cd into project directory
2. Run `npm install`


### Set Up Ganache



### Set Up Accounts

![Orders Architecture](./assets/ganache1.png) ![Orders Architecture](./assets/ganache2.png)

1. Open up Metamask and add a new Custom RPC

![Orders Architecture](./assets/ganache3.png)

2. The RPC URL can be found on Ganache

![Orders Architecture](./assets/ganache4.png)

![Orders Architecture](./assets/ganache.png)

3. Import the first account on Ganache to your Metamask. The private key of that account can be found by clicking on the 'key' icon on Ganache
4. You can add all the accounts in Ganache to simulate multiple users.
5. Only the first account is the owner account which deployed all the contracts. This will be the account that will have the initial supply of SCSE, MAE and EEE tokens.
6. If you do not see the ETH being reflected in your Metamask wallet, change to another network and change back to Ganache

### Set Up Website

1. cd into 
2. Run `npm install`
3. Run `npm run start` in console
4. If all token balances are 0 in the website, make sure your Metamask account is connected to the website

