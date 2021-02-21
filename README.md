This is a collection of libraries and utilities for [Vapory](https://vapory.org).

## Use cases

### Creating an online wallet?

Check out [keyvapory](https://github.com/vaporyjs/keyvapory) or [vaporyjs-wallet](https://github.com/vaporyjs/vaporyjs-wallet) (with HD wallet support) for managing keys and [vaporyjs-tx](https://github.com/vaporyjs/vaporyjs-tx) for creating transactions with them.
[vaporyjs-icap](https://github.com/vaporyjs/vaporyjs-icap) might also come handy for dealing with the ICAP (Vapory in IBAN) format.

### Creating a Dapp?

You will need to interface with the Vapory network. [web3.js](https://github.com/vaporyco/web3.js) provides a complete Javascript API to interact with the RPC interface. If looking for a more lightweight option, [vaporyjs-abi](https://github.com/vaporyjs/vaporyjs-abi) or [solidity.js](https://github.com/vaporyco/solidity.js) can handle the ABI encoding.

### Interested in running a node?

See [node-blockchain-server](https://github.com/vaporyjs/node-blockchain-server). It is in a pretty rough state at the moment, but at least can download the blockchain.

## Full list of repos

* [browser-builds](https://github.com/vaporyjs/browser-builds): browser builds of vaporyjs libraries
* [common](https://github.com/vaporyjs/common): the genesis data for the blockchain
* [vapashjs](https://github.com/vaporyjs/vapashjs): [Ethash](https://github.com/vaporyco/wiki/wiki/Ethash) in Javascript
* [vaporyjs-abi](https://github.com/vaporyjs/vaporyjs-abi): ABI encoding and decoding
* [vaporyjs-account](https://github.com/vaporyjs/vaporyjs-account): account schema encoding, decoding and validation
* [vaporyjs-block](https://github.com/vaporyjs/vaporyjs-block): block schema encoding, decoding and validation
* [vaporyjs-blockchain](https://github.com/vaporyjs/vaporyjs-blockchain): manage a blockchain
* [vaporyjs-codesim](https://github.com/axic/vaporyjs-codesim): run EVM or Solidity code and examine the output
* [vaporyjs-icap](https://github.com/vaporyjs/vaporyjs-icap): utilities for handling ICAP (Vapory in IBAN) encoding
* [vaporyjs-lib](https://github.com/vaporyjs/vaporyjs-lib): meta package for loading the other vaporyjs- modules
* [vaporyjs-testing](https://github.com/vaporyjs/vaporyjs-testing): transforms the [official test vectors](https://github.com/vaporyco/tests) to a format suitable for vaporyjs
* [vaporyjs-tx](https://github.com/vaporyjs/vaporyjs-tx): transaction creation, manipulation, signing and verification
* [vaporyjs-units](https://github.com/vaporyjs/vaporyjs-units): Vapory unit conversion
* [vaporyjs-util](https://github.com/vaporyjs/vaporyjs-util): a collection of frequently used methods by the other libraries
* [vaporyjs-wallet](https://github.com/vaporyjs/vaporyjs-wallet): lightweight toolkit for managing Vapory keys, including HD wallet support
* [vaporyjs-vm](https://github.com/vaporyjs/vaporyjs-vm): a complete EVM (Vapory Virtual Machine) and state processing implementation
* [gvap.js](https://github.com/vaporyjs/gvap.js): start and stop gvap from Node.js
* [helpvap](https://github.com/vaporyjs/helpvap): purists' commandline tool for key and transaction management
* [keythereum](https://github.com/vaporyjs/keythereum): create, import and export Vapory keys
* [merkle-patricia-tree](https://github.com/vaporyjs/merkle-patricia-tree): This is an implementation of the modified merkle patricia tree as specified in the [Vapory yellow paper](http://gavwood.com/Paper.pdf)
* [node-blockchain-server](https://github.com/vaporyjs/node-blockchain-server): aims to provide a full Vapory node implementation
* [node-devp2p](https://github.com/vaporycojs/node-devp2p): implementation of the [RLPx](https://github.com/vaporyco/devp2p/blob/master/rlpx.md) transport protocol for Vapory (used between nodes)
* [node-devp2p-dpt](https://github.com/vaporyjs/node-devp2p-dpt): implementation of the [RLPx](https://github.com/vaporyco/devp2p/blob/master/rlpx.md) DPT (peer table) protocol for Vapory
* [node-devp2p-vap](https://github.com/vaporyjs/node-devp2p-vap): implementation of the Vapory sub-protocol over RLPx
* [node-devp2p-manager](https://github.com/vaporyjs/node-devp2p-manager): peer manager for DPT & RLPx
* [organization](https://github.com/vaporyjs/organization) and [ideas](https://github.com/vaporyjs/ideas): plans and discussions
* [rlp](https://github.com/vaporyjs/rlp): [RLP (Recursive Length Prefix)](https://github.com/vaporyco/wiki/wiki/RLP) encoding and decoding
* [testrpc](https://github.com/vaporyjs/testrpc): fast Vapory RPC node for testing and development


## Vapory JS projects not tracked here
* [web3.js](https://github.com/vaporyco/web3.js): the complete API as seen in the [wiki](https://github.com/vaporyco/wiki/wiki/JavaScript-API)
* [solidity.js](https://github.com/vaporyco/solidity.js): ABI encoding and decoding (the relevant code split out from web3.js)

## Contributing and contact

Please check out [organization](https://github.com/vaporyjs/organization) and [ideas](https://github.com/vaporyjs/ideas) repos first.  Contributing to each of the projects is preferably done via pull requests.

You can also reach out on:
* [Gitter](https://gitter.im/vapory/vaporyjs-lib)
* [#vaporyjs](https://webchat.freenode.net/?channels=vaporyjs) on freenode
