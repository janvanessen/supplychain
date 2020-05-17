# AvocadoChain
*Blockchain Solution for Avocado Supply Chains*

## Introduction

AvocadoChain is a decentralized application for avocado supply chains, backed by the Ethereum platform.
It allows market participants to track avocados along the supply chain. In particular, it enables consumers to prove authenticity and provenance of "Fair Trade Avocados".

## Smart Contract

Contract on the Rinkeby test network:

* Transaction Hash: [0xc53960225a50a9f21cdd6b40940db334d1be15df4cd823d9b296c851557efa57](https://rinkeby.etherscan.io/tx/0xc53960225a50a9f21cdd6b40940db334d1be15df4cd823d9b296c851557efa57)
* Contract Hash: [0x4767b7Cd3f395DFa1Cb4cc791cd04aD843279399](https://rinkeby.etherscan.io/address/0x4767b7cd3f395dfa1cb4cc791cd04ad843279399)
* Contract Address: [https://rinkeby.etherscan.io/address/0x4767b7cd3f395dfa1cb4cc791cd04ad843279399#code](https://rinkeby.etherscan.io/address/0x4767b7cd3f395dfa1cb4cc791cd04ad843279399#code)

## Tests

Run unit tests:

`truffle develop`

`test`

## Frontend

Start the web app:

`npm run dev`


## UML

### Activity Diagram

![Activity](/uml/1-activity.png)

### Sequence Diagram

![Sequence](/uml/2-sequence.png)

### State Diagram

![State](/uml/3-state.png)

### Data Model

![Data](/uml/4-data.png)

## Libraries and frameworks

* Truffle: Development, deployment and testing of smart contracts
* truffle-hdwallet-provider: HD Wallet-enabled Web3 provider

### Version numbers

* Truffle v5.1.14-nodeLTS.0 (core: 5.1.13)
* Solidity v0.5.16 (solc-js)
* Node v13.12.0
* Web3.js v1.2.1

