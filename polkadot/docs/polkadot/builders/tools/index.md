# Tools

Here we provide a list of tools available for your development needs. They
are sorted by programming language. Right now, the Rust ecosystem is the most
mature and it's possible to get started by building on Substrate today. As the
ecosystems surrounding other programming languages expand, the sections below
will be filled out.

## Block Explorers

 - [Polkascan](https://polkascan.io/) - Blockchain explorer for Polkadot. **Currently down.**
 - [PolkadotJS Explorer](https://polkadot.js.org/apps/#/explorer) - Currently connects to the Alexander testnet by default, but can be configured to connect to other remote or local endpoints.

## Wallets

 - [Polkawallet](https://polkawallet.io/) - A mobile wallet for Polkadot on both iOs and Android. Currently in development but a Beta version is available for download.
 - [ImageWallet](https://www.reddit.com/r/dot/comments/ah3py1/introducing_alpha_version_of_httpsimagewalletio/) - Cross-chain wallet with visuals. **In development with planned support for Polkadot and all Substrate chains.**

## Rust

The first [Polkadot client](https://github.com/paritytech/polkadot) is written in Rust.

Currently the Rust ecosystem is the most mature for Polkadot parachain development. The framework for creating Polkadot parachains is called [Substrate](https://github.com/paritytech/substrate).

There is comprehnsive documentation for building on Substrate available in the [Substrate Development Hub](https://github.com/paritytech/substrate).

Additional tools you may be interested in:

## C++

[Soramitsu](https://github.com/soramitsu) is developing a [client](https://github.com/soramitsu/polkadot) in C++.

## Go

[ChainSafe Systems](https://chainsafe.io) is writing a [client](https://github.com/ChainSafeSystems/go-pre) in Go.

## JS

There is an extensive ecosystem of Polkadot tools including a [client](https://github.com/polkadot-js/client) available in [polkadot-js](https://github.com/polkadot-js) organization.

Documentation on the [polkadot-js](https://polkadot.js.org) is a good starting point for diving deeper.

Once you've configured and started to run a local node, you can interact with it through the generic polkadot [explorer](https://polkadot.js.org/apps/#/explorer).

### Libraries

 - [@polkadot/keyring](https://polkadot.js.org/common/keyring/) To create / load accounts in JavaScript, helpful for creating wallets or any application which will require the user to write to chain. [Examples](https://polkadot.js.org/common/examples/keyring/)
 - [@polkadot/util](https://polkadot.js.org/common/util/) Useful utility functions like checking if a string is hex encoded. **!Needs documention**
 - [@polkadot/util-crypto](https://polkadot.js.org/common/util-crypto/) Crypto utilities that will come into handy while developing with Polkadot. **!Needs documention**
 - [oo7-polkadot](https://github.com/polkadot-js/oo7-polkadot) A bonds library for Polkadot. **!Needs documentation**

### CLI Tools

 - [@polkadot/api-cli](https://github.com/polkadot-js/tools/tree/master/packages/api-cli) Simple commandline interface for the polkadot API. **!Needs documentation**
 - [@polkadot/monitor-rpc](https://github.com/polkadot-js/tools/tree/master/packages/monitor-rpc) Simple RPC monitor for Polkadot. **!Needs documentation**
