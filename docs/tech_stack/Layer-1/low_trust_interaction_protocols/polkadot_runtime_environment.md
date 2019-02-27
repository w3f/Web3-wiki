# Polkadot Runtime Environment
## Overview
The Polkadot Runtime Environment (PRE) is an important component within the [Polkadot](../low_trust_interaction_platforms/polkadot.md) platform. The PRE can be seen as the bottom three layers of a four layer stack, and will be common to each of the native chains within Polkadot (see also [parachains](parachains.md).

The three layers of the PRE are:

* Wasm Interpreter
* Consensus
* Networking

The code of the PRE can be compiled to run natively. The top part of the Polkadot stack is called the runtime (otherwise known as the state machine) will be unique to each chain and must be written in a language that compiles to Wasm.

The following image is taken from the [slide deck of Gavin Wood's presentation on Substrate](https://slides.com/paritytech/paritysubstrate#/8). It shows how the four layers a PRE will look.

![](https://i.imgur.com/Z9dxeR4.png)

## Substrate
The Web3 Foundation contracted Parity Technologies to write the first implementation of Polkadot. Their implementation of the PRE is called ‘[Substrate](substrate.md)’.

## Useful Links
See the useful links under the Substrate page for useful references.

* [Polkadot Runtime Environment: Alternative Implementation Grant](https://github.com/w3f/Web3-collaboration/issues/12) - In H2 2018, W3F offered a grant for an alternative implementation of the Polkadot Runtime Environment. This grant has come to a soft close.
