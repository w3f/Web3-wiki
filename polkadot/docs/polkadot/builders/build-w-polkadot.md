# How Can I Build with Polkadot?

## Where are we now?

Polkadot is under active development. However, it is already to get started planning your project and even start building it as a parachain or smart contract. One of the first questions that builders need to answer is whether they will build their project as a parachain or a smart contract. This guide is intended to provide a one-stop resource for those wishing to embark on their Polkadot journey.

## What is the difference between a parachain and smart contract?

It's important to know the difference between a parachain and a smart contract
before you begin work on your project. Since both options have their trade-offs
and benefits, some projects work well as a parachain while others work better
as smart contracts on an already mature blockchain.

In general, if you want control over the foundational mechanics of your
blockchain such as a custom fee structure for transactions, a
monetary system with a treasury, an optimized state transition function,
or are implementing something novel such as a new virtual machine, you will
likely be creating a parachain.

Instead if you would like to quickly prototype and deploy your application
you might be more interested in creating a smart contract.

Be aware that the benefits of developing a parachain also has its 
downsides, it involves running your own network of collators and 
eventually bidding for inclusion in the Polkadot shared security
by staking DOTs. Unless you're sure you are not able to do 
what you want to do on a smart contract platform because you've
already tried, it is generally advisable you start by trying out
your idea there.

| Parachain | Smart Contract |
|-----------|----------------|
| more complex to develop (-) | easy to develop (+) |
| requires collator node to deploy (-) | easy to deploy (+)  |
| interaction between parachains (+) | interaction between applications (+) |
| requires network maintainance (-) | easier to maintain (+) |
| possible to implement complex network logic and advanced crypto (+) | harder to implement complex logic or crypto (-) |
| is its own network (+) | exists inside network (-) |

## Parachain

Once you've determined that parachain development is the right path for your project, you will need to decide on what framework you will use to create your runtime module. Right now there is only one option which is Substrate.

### Substrate

The most definitive resource for substrate development is the Parity maintained [Substrate Development Hub](https://docs.substrate.dev).

### Set-up your chain

Once you've decided on your development framework and have compiled your runtime module into the necessary WASM blob, the next thing to do is set up your chain.

In order to deploy a parachain you will need to run your own collator node.

## Smart Contracts

Polkadot will likely have a variety of parachains which offer smart contracts
to developers. These are still rapidly progressing and more content will be
posted as the technology is ready.

### Edgeware

[Edgeware](https://edgewa.re) is a planned parachain for Polkadot which will
allow for smart contracts.

### pDSL (Parity's Domain Specific Language)

The [pDSL](https://github.com/Robbepop/pdsl) is still in experimental phase and not yet
accepting external contributors. However, it provides some insight into the future of smart
contracts. It intends to provide an efficient, simple, robust, accesible language for
developers that will work with existing Rust tooling.
