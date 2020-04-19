## Contract Address
```
0x23f7b72a601eEAC3916B7848DC22a68A6b5fDF3C
```

## transaction hash
```
0x890de04fa997260d904a5507635c5145196eb199f0c2cc7edc8815e75f965f83
```

## No libary used

## IPFS was not used

## Truffle version
v5.1.20 (core: 5.1.20)

## Node version
v10.16.0

## UML Diagrams

UML diagrams are in UML folder

# USAGE
This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

## Prerequisites

-Ganache
-Truffle
-Metamask

### Clone the repository
```
https://github.com/Tomesyy/Supply-Chain.git
```

- run 
```
npm install
```
- launch Ganache

- run
```
truffle compile
truffle migrate
truffle test
```
All 10 tests should pass

- launch the DApp
```
npm run dev
```

- open DApp on browser
- Connect metamask to Ganache
