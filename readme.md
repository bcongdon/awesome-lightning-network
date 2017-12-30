# ⚡ awesome-lightning-network [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome Lightning Network resources, apps, and libraries

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Lightning Network Protocol](#lightning-network-protocol)
  - [Implementations](#implementations)
  - [Specifications / White Papers](#specifications--white-papers)
- [Applications](#applications)
  - [Desktop Interfaces](#desktop-interfaces)
  - [Web Interfaces](#web-interfaces)
  - [Misc](#misc)
- [Developer Resources](#developer-resources)
  - [Libraries](#libraries)
  - [Tutorials](#tutorials)
  - [Example Projects](#example-projects)
- [Learning Resources](#learning-resources)
  - [Talks](#talks)
  - [Books](#books)
- [Community](#community)
  - [IRC](#irc)
- [Related Lists](#related-lists)
- [Contribute](#contribute)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## Lightning Network Protocol

### Implementations

Implementations of the Lightning Network Protocol

- [LND](https://github.com/lightningnetwork/lnd) - Lightning Network Daemon (Golang)
- [eclair](https://github.com/ACINQ/eclair) - A Scala implementation of the Lightning Network (Scala)
- [lit](https://github.com/mit-dci/lit) - Lightning Network node software (Golang)
- [c-lightning](https://github.com/ElementsProject/lightning) - A Lightning Network implementation in C
- [lightning-onion](https://github.com/lightningnetwork/lightning-onion) - Onion Routed Micropayments for the Lightning Network (Golang)
- [ptarmigan](https://github.com/nayutaco/ptarmigan) - C++ BOLT-Compliant Lightning Network Implementation [Incomplete]

### Specifications / White Papers

- [Lightning Network Specification](https://github.com/lightningnetwork/lightning-rfc)
- [LND API Reference](http://api.lightning.community/)
- [Lightning Network White Paper](https://lightning.network/lightning-network-paper.pdf)
- [Deployable Lightning White Paper](https://github.com/ElementsProject/lightning/blob/master/doc/deployable-lightning.pdf)
- [Scalable Funding of Bitcoin Micropayment
Channel Networks](https://www.tik.ee.ethz.ch/file/a20a865ce40d40c8f942cf206a7cba96/Scalable_Funding_Of_Blockchain_Micropayment_Networks%20(1).pdf)

## Applications

### Desktop Interfaces

- [lightning-app](https://github.com/lightninglabs/lightning-app) - Cross-platform Lightning Desktop Application
- [lnd-gui](https://github.com/alexbosworth/lnd-gui) - Lightning MacOS GUI Wallet
- [eclair-node-gui](https://github.com/ACINQ/eclair) - Cross-platform desktop GUI for Lightning
- [zap-desktop](https://github.com/LN-Zap/zap-desktop) - Lightning Network desktop application


### Web Interfaces

- [lncli-web](https://github.com/mably/lncli-web) - Light-weight web client for the lnd daemon written in NodeJS / Angular
- [lnd-chrome-extension](https://chrome.google.com/webstore/detail/lnd-chrome-extension/fckoopaejbdhcjgpjllghoadkeicdjnf?hl=en)
- [kugelblitz](https://github.com/cdecker/kugelblitz) - A simple UI for the c-lightning daemon lightningd and bitcoind

### Misc

- [lightning-faucet](https://github.com/lightninglabs/lightning-faucet) - A faucet for the Lightning Network
- [ln-dice](https://github.com/mably/ln-dice) - Dice gambling service using the Lightning Network for deposits and withdrawals
- [ln-tip-slack](https://github.com/CryptoFR/ln-tip-slack) - Lightning [Slack](https://slack.com/) Tipbot
- [lightning-cat](https://github.com/rustyrussell/lightning-cat/blob/master/catsearch.sh) - Cat pictures via Lightning
- [Lightning network explorer](https://explorer.acinq.co/) - Lightning network explorer (testnet)

## Developer Resources

- [Lightning Overview](http://dev.lightning.community/overview/)
- [LND Developers Site](http://dev.lightning.community/)
- [LND Developer Guide](http://dev.lightning.community/guides/)
- [Rusty Russell's BOLT Blog Series](https://medium.com/@rusty_lightning/the-bitcoin-lightning-spec-part-1-8-a7720fb1b4da)

### Libraries

- [lightning-integration](https://github.com/cdecker/lightning-integration) - Lightning Integration Testing Framework
- [lightning-strike](https://github.com/ElementsProject/lightning-strike) - A simple drop-in solution for accepting lightning payments (Javascript)
- [lightning-strike-client-js](https://github.com/ElementsProject/lightning-strike-client-js) - JavaScript client for lightning-strike
- [lightning-strike-client-php](https://github.com/ElementsProject/lightning-strike-client-php) - PHP client for lightning-strike
- [lightning-payencode](https://github.com/rustyrussell/lightning-payencode) - Minimal QR-code-ready encoding for requesting lightning payments
- [lseed](https://github.com/cdecker/lseed) - A DNS seed for the Lightning Network
- [woocommerce-gateway-lightning](https://github.com/ElementsProject/woocommerce-gateway-lightning) - A WooCommerce gateway for lightning payments
- [lnrpc-client](https://github.com/michielbdejong/lnrpc-client) - Javascript RPC Client for LND
- [ln-service](https://github.com/alexbosworth/ln-service) - Lightning REST Service


### Tutorials

- [Setting up and Testing LND with the Testnet Lightning Faucet](http://lightning.community/lnd/faucet/2017/01/19/lightning-network-faucet/)
- [Setting up a local Lightning cluster](http://dev.lightning.community/tutorial/01-lncli/index.html)
- [Using the LND Web Client](http://dev.lightning.community/tutorial/02-web-client/index.html)
- [Using the LND gRPC Client](http://dev.lightning.community/tutorial/03-rpc-client/index.html)
- [Integrating Lightning into a server-side web application](http://dev.lightning.community/tutorial/04-webapp-integration/index.html)
- [How to use a Python gRPC Client with LND](http://dev.lightning.community/guides/python-grpc/)
- [How to use a Javascript gRPC Client with LND](http://dev.lightning.community/guides/javascript-grpc/)

### Example Projects

- [ilp-lightning-demo](https://github.com/interledgerjs/ilp-lightning-demo) - Demo sending payments between Bitcoin and Litecoin Lightning Networks using Interledger
- [lightning-coindesk](https://github.com/lightninglabs/lightning-coindesk) - An example news app exemplifying Lightning Network micropayments integration


## Learning Resources 

- [Lightning FAQ](https://medium.com/@AudunGulbrands1/lightning-faq-67bd2b957d70)
- [Lightning Network Bitcoin Wiki](https://en.bitcoin.it/wiki/Lightning_Network)
- [Hashed Timelock Contracts](https://en.bitcoin.it/wiki/Hashed_Timelock_Contracts)
- [LN as a Directed Graph; Single-Funded Channel Topology](https://docs.google.com/presentation/d/1G4xchDGcO37DJ2lPC_XYyZIUkJc2khnLrCaZXgvDN0U/edit?pref=2&pli=1#slide=id.g85f425098_0_2) (Slides)
- [How to Do "2-of-3 Multisig Contract" Equivalent on Lightning](https://lists.linuxfoundation.org/pipermail/lightning-dev/2016-January/000403.html) (From LN Mailing List)

### Talks

- [Lightning Network Deep Dive with Laolu "Roasbeef" Osuntokun](https://www.youtube.com/watch?v=b_szGaaPPFk) [48:10]
- [SF Bitcoin Devs Seminar: Scaling Bitcoin to Billions of Transactions Per Day](https://www.youtube.com/watch?v=8zVzw912wPo) [54:40]
- [Bitcoin, Lightning, and Streaming Money](https://www.youtube.com/watch?v=gF_ZQ_eijPs) (Andreas Antonopoulos) [27:38]
- [Lightning Network Tech Talk at Coinbase](https://www.youtube.com/watch?v=wIhAmTqXhZQ) (Thaddeus Dryja and Joseph Poon) [58:11]

### Books

- [Mastering Bitcoin, 2nd Edition](http://shop.oreilly.com/product/0636920049524.do)

## Community

- [Lightning Network Community Blog](http://lightning.community/)
- [Lightning Network Twitter Feed](https://twitter.com/lightning)
- [Lightning Network Mailing List](https://lists.linuxfoundation.org/mailman/listinfo/lightning-dev)
- [LND Community Slack](https://join.slack.com/t/lightningcommunity/shared_invite/MjI4OTg3MzQ4MjI2LTE1MDMxNzM1NTMtNjlmOGYzOTI1Ng)
- [Lightning Labs Blog](https://blog.lightning.engineering/)

### IRC

- [#lightning-dev](https://webchat.freenode.net/?channels=lightning-dev&uio=d4) (on Freenode) - Lightning protocol development
    - [Channel Archive](https://botbot.me/freenode/lightning-dev/)
- [#lnd](https://webchat.freenode.net/?channels=lnd&uio=d4) - Lightning only version of #bitcoin-commits

## Related Lists

- [awesome-bitcoin](https://github.com/igorbarinov/awesome-bitcoin)
- [awesome-blockchain](https://github.com/igorbarinov/awesome-blockchain)


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the author has waived all copyright and
related or neighboring rights to this work.
