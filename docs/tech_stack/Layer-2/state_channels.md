# State Channels
## Overview
State channels are a technique for performing transactions and other state transitions in a second layer built on top of a blockchain. State channels make blockchains more efficient by moving many processes off-chain, while still retaining a blockchain’s characteristic trustworthiness. Payment channels are a type of state channel that allows users to make "off-chain payments" to each other. The term "state channels" generalizes this approach beyond payments.

Examples are:
* [Counterfactual](https://counterfactual.com/)
* [Raiden Network](https://raiden.network/)
* [Lightning Network](http://lightning.network/)
* [FunFair](https://funfair.io/)

## Counterfactual
Counterfactual is building a generalized framework for native state channels integration in Ethereum-based decentralized applications.

### Resources
* [Counterfactual: Generalized State Channels](https://l4.ventures/papers/statechannels.pdf) - paper describing generalized state channels. 
* [Generalized State Channels on Ethereum](https://medium.com/l4-media/generalized-state-channels-on-ethereum-de0357f5fb44) - article describing state channels on Ethereum.
* [Video](https://www.youtube.com/watch?v=kZH_ty82jKY) - video presentation of generalized state channels. 

## Raiden Network
The Raiden Network is an off-chain scaling solution, enabling near-instant, low-fee and scalable payments. It’s complementary to the Ethereum blockchain and works with any ERC20 compatible token. It is Ethereum’s version of Bitcoin’s Lightning Network.

### Resources
* [FAQ](https://raiden.network/faq.html) - overview of the Raiden Network. 
* [GitHub Documentation](http://raiden-network.readthedocs.io/en/stable/) - API documentation, developer preview, tuturoials.
* [GitHub Repo](https://github.com/raiden-network/raiden/?fref=ts) - codebase. 
* [Video](https://www.youtube.com/watch?v=R1tIy1XgdPw) - video clip explaining the Raiden Network.

## Lightning Network
Lightning is a decentralized network using smart contract functionality in the blockchain to enable instant payments across a network of participants.

### Resources
* [Whitepaper](https://lightning.network/lightning-network-paper.pdf) - overview the Bitcoin Lightning Network: Scalable Off-Chain Instant Payments. 
* [Summary](https://lightning.network/lightning-network-summary.pdf) - brief overview of the Lightning Network.

## FunFair's Fate Channels
A Fate Channel is a State Channel opened for the duration of a gaming session, supporting custom
gaming messages between the FunFair client and server. The only transactions on the blockchain occur
at the beginning and end of the gaming session.

### Resources
* [Whitepaper](https://funfair.io/wp-content/uploads/FunFair-Commercial-White-Paper.pdf) - overview of FunFair with section on Fate Channels. 
* [State Channels in Disguise](https://funfair.io/state-channels-in-disguise/) - brief overview of Fate Channels. 
