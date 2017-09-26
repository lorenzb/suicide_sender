# SuicideSender
**Learn this one simple trick to forcibly increase any smart contract's balance!**

## About 

This repo contains a small utility contract written in Solidity and EVM assembly that sends ether to other addresses by means of 
SUICIDE/SELFDESTRUCT. Unlike for a normal send/call, if the receiving address
belongs to a contract, the contract's code is never called; one can
forcibly increase any contract's balance!

If you're interested in the implications of this trick, I recommend
looking at [João Carvalho's and Richard Moore's entries to the first
Underhanded Solidity Contest](https://medium.com/@weka/announcing-the-winners-of-the-first-underhanded-solidity-coding-contest-282563a87079). Anybody writing smart contracts should be 
aware of forced balance increases lest their contracts be vulnerable.

## Deployed contracts

The contract is deployed on the Ethereum mainnet at address [0xE7850f1A4d21bBd2f819374457C83A6fF84E70d3](https://etherscan.io/address/0xe7850f1a4d21bbd2f819374457c83a6ff84e70d3#code).
