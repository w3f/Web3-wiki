# Peer to Peer Internet overlay protocols

## Overview

Peer-to-peer Internet overlay protocols are a Layer 0 component.

Examples are:
* Devp2p
* Libp2p

## Devp2p 
### Overview
devp2p is the secure networking suite that powers Ethereum, Whisper, and Swarm. It defines a set of networking and peer-to-peer protocols including [RLPx](https://github.com/ethereum/devp2p/blob/master/rlpx.md), which it uses for authentication, stream multiplexing, network forming, and protocol multiplexing. 

### Resources
* [Wiki](https://ethereum.gitbooks.io/frontier-guide/content/devp2p.html) - protocol specification.
* [JS Implementation](https://github.com/ethereumjs/ethereumjs-devp2p) - library bundling different components.
* [RLPx](https://github.com/ethereum/devp2p/blob/master/rlpx.md) - peer-to-peer network and protocol suite.
* [Gitt Chat](https://gitter.im/ethereum/devp2p?at=5ab4d61ce3d0b1ff2c5bc3d4) - discuss the project.

## Libp2p
### Overview
libp2p is the modular secure networking suite that powers IPFS and Polkadot. It defines a set of interfaces for common networking and peer-to-peer protocols. libp2p is fast, robust, and powerful. It uses multiformats for self-description, avoiding algorithm lock-in, and cryptographic agility. libp2p handles Authentication, Transports, Stream Multiplexing, Peer Discovery, Peer Routing, Content Routing, NAT Traversal, and Relay. The coolest thing? It also runs entirely on the browser!

### Resources
* [GitHub Repo](https://github.com/libp2p/) - full set of resources.
* [Specifications](https://github.com/libp2p/specs) - spec in libp2p, currently a work in progress.
* [Rust Implementation](https://github.com/libp2p/rust-libp2p) - implementation in Rust from [Parity Technologies](https://github.com/paritytech/).
* [Website](https://libp2p.io/) - homepage.
* [Whitepaper](https://github.com/ethereum/wiki/wiki/libp2p-Whitepaper) - high-level overview, now outdated. 

### Teams using libp2p
* [Polkadot](https://github.com/w3f/Web3-wiki/wiki/Polkadot)
* [Substrate](https://github.com/w3f/Web3-wiki/wiki/Substrate)
* [IPFS](https://github.com/ipfs/ipfs)
* [Livepeer](https://github.com/ericxtang/livepeer-libp2p-spike)
* [OpenBazaar](https://github.com/OpenBazaar/go-libp2p-kad-dht)
* [Curio](https://github.com/dabeaz/curio)

