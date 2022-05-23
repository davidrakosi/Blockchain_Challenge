# Blockchain Challenge

## About

This project includes 5 small tasks:

1. Wallet Connection 

2. Uploading JPEG File and Minting it as NFT

3. List the minted NFT in OpenSea Marketplace

4. Create a Token Gated Access

5. Build a simple DEX 

## Installation

Run these commands to clone the repository and install dependencies.

```bash
cd blockchain_assignment
git clone git@github.com:sheilashehu/blockchain_challenge.git
yarn install
cd my-app
yarn dev
```

## Usage

Prerequisite: 
1. Install the Metamask Wallet extension in your browser. 
2. Make sure you have enough test tokens (Rinkeby Test Network)

#### Minting

1. Connect with Metamask Wallet (If connected, you will be redirected to the NFT Minter)
2. Choose a file and fill out the name and description.
3. Upload the file to IPFS Decentralized Database and wait for alert confirmation.
4. Click MINT button to mint NFT and wait for alert confirmation. 
5. After the confirmation is received, you should be able to see the transaction in Rinkeby Etherscan. You will also be able to find the NFT in OpenSea Test Marketplace.


#### Token Gate

6. After the transaction is performed, you may click on the 'Load Dex' button to access DEX and perform transactions.

#### DEX

 __CP Token Address: 0x29533859D43e92b3A46A1d42d5E35D8e731A38F2__

7. Initially, you have to deposit eth test tokens to DEX and add import CP token to your Metamask Wallet assets, using the above contract address.
8. Next, you can exchange eth by placing a market order.
9. The exchange rate will be based on existing limit orders in the SELL/BUY Order Book.
10. You should also be able to place your own limit orders in the DEX marketplace.
11. Finally, you can withdraw either Eth or CP Tokens to your Metamask Wallet.



## Technology Stack and Tools
[Metamask](https://metamask.io/) Wallet

[Hardhat](https://hardhat.org/) - development framework 

[React Js](https://reactjs.org/) / [NextJs](https://nextjs.org/) - front end framework

[Solidity](https://docs.soliditylang.org/en/v0.8.14/) - ethereum smart contract language

[JavaScript](https://www.javascript.com/) - logic front end and testing smart contracts

[ethers.js](https://docs.ethers.io/v5/) - library interact with ethereum nodes

[Alchemy](https://www.alchemy.com/) - connection to ethereum network

[Open Zeppelin](https://www.openzeppelin.com/) - smart contract libraries


## License
[MIT](https://choosealicense.com/licenses/mit/)