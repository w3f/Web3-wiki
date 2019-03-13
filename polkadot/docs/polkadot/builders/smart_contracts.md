# Comparison to Smart Contract Engineering

Developers may be familiar with other blockchains and their environments
for developing smart contracts. For higher-level comparisons between
Polkadot and other solutons you can read the overview [here](../information/comparison.md).

The rest of this document will elaborate on some key differences between
developing Parachains or runtime modules and smart contracts.

## Layer of Abstraction

When you write a smart contract on Ethereum you are creating the instructions
which will be compiled down to a blob of code and deployed to a
specific address on chain.

In comparison, Substrate runtime modules are WASM blobs which will dictate
the entire logic of your parachain. 

**Code can be significantly changed by performing runtime upgrades**

Unlike in Ethereum when you deploy a smart contract and that contract
code won't change in unexpected ways (sans the inclusion of bugs or exploits),
with runtime modules, the entire logic can be swapped out by the developer
or the governance system.

This allows for a greater degree of control on behalf of developers since 
they are now dealing with entire chain logic instead of just the
specific contracts which they've deployed.

## Gas Fees

In smart contracts on Ethereum you must be aware of the gas fees of your
contracts and things like `while` loops that perform gas-heavy calls
can prove fatal to the execution of your contract logic.

When coding for a Polkadot parachain, you no longer have to directly 
worry about the gas costs of the logic that you will deploy. Since
the parachain will be a network that you run with the shared security
of the relay chain.

This makes certain operations such as dividend pay-outs or token inflation
easier to develop into your system.

Things that are hard to do in smart contracts suddenly become available
to the developer when coding for Polkadot parachains.