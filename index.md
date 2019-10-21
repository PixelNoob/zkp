Blockchain technology provides the necessary tools to decentralize information in a secure and unbreachable manner. The introduction of Bitcoin made it possible for thousands of nodes around the world to share and maintain the same information. However, in most Blockchains, the central idea is to keep this information public so that everyone can access it and verify it, without the need of any central entity, this is why we define public blockchains as trustless networks. 

Many companies and private entities who want to use blockchain technology find themselves with an important interrogant: how can you keep information private and manage to retain the security and transparency of a public blockchain. 

Here is where the zero knowledge protocols come into play: a zero-knowledge proof or zero-knowledge protocol is the method by which the node operators can prove that a transaction is valid without actually revealing the values of that transaction. 

The fact that this added value of privacy can be obtained through cryptography, comes very handy for individuals and private entities that benefit from using blockchain technology without the fear of sharing sensitive information. 

## EOS Argentina's contribution

EOS Argentina has fully incorporated a mathematician and professional researcher to the team to help us study the implementation of zero knowledge protocols on EOS.io. 

The Protocol that we see as the best fit for EOS.io is ZETHER, because it uses an account data structure that requires less RAM than the usual UTXO system.

The research has brought some interesting hurdles that we would like to share with the whole community. We also want to propose solutions to these problems.

## Proof Generator

The proof generator creates the proof and submits the tx to the smart contract for its validation. 

We proposed this code written in python to generate the proof but the same can be done with other languages. 

[LINK TO PROOF GENERATOR](https://link)

## NODEOS Modification & New VM

While we were developing and testing the Smart Contract we encountered an issue with the verification process. We found that the verification time for one proof exceeds the max time of an eos tx on mainnet. We tried with different libraries, amongst them the Blockstream Library, but we failed to complete a verification on the time established by nodeos to execute a transaction.


## REFERENCES:

Jacques Martin: Getting Snarky - A Brief Look At zk-SNARKs, 2019 (https://blockchain.wtf/2018/12/blog/getting-snarky-a-brief-look-at-zk-snarks/)

Stanford University: Zether: Towards Privacy in a Smart Contract World, 2019

