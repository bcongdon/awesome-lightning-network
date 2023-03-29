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
  - [Command Line Interfaces](#command-line-interfaces)
  - [Mobile applications](#mobile-applications)
  - [Explorers](#explorers)
  - [Misc](#misc)
- [Developer Resources](#developer-resources)
  - [Tools](#tools)
  - [Libraries](#libraries)
  - [Tutorials](#tutorials)
  - [Example Projects](#example-projects)
  - [Simulators](#simulators)
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
- [rust-lightning](https://github.com/rust-bitcoin/rust-lightning) - A Lightning Network implementation in Rust [Incomplete]
- [lightning-onion](https://github.com/lightningnetwork/lightning-onion) - Onion Routed Micropayments for the Lightning Network (Golang)
- [ptarmigan](https://github.com/nayutaco/ptarmigan) - C++ BOLT-Compliant Lightning Network Implementation

### Specifications / White Papers

- [Lightning Network Specification](https://github.com/lightningnetwork/lightning-rfc)
- [LND API Reference](http://api.lightning.community/)
- [Lightning Network White Paper](https://lightning.network/lightning-network-paper.pdf)
- [Deployable Lightning White Paper](https://github.com/ElementsProject/lightning/blob/master/doc/deployable-lightning.pdf)
- [Scalable Funding of Bitcoin Micropayment Channel Networks](https://www.tik.ee.ethz.ch/file/a20a865ce40d40c8f942cf206a7cba96/Scalable_Funding_Of_Blockchain_Micropayment_Networks%20(1).pdf)

## Applications

### Desktop Interfaces

- [lightning-app](https://github.com/lightninglabs/lightning-app) - Cross-platform Lightning Desktop Application
- [lnd-gui](https://github.com/alexbosworth/lnd-gui) - Lightning MacOS GUI Wallet
- [eclair-node-gui](https://github.com/ACINQ/eclair) - Cross-platform desktop GUI for Lightning
- [zap-desktop](https://github.com/LN-Zap/zap-desktop) - Lightning Network desktop application
- [Presto](https://github.com/icota/presto) - c-lightning based desktop wallet
- [Lightning Peach Wallet](https://github.com/LightningPeach/lightning-peach-wallet) - Bitfury Lightning Wallet
- [spark-wallet](https://github.com/shesek/spark-wallet) - Minimal GUI for c-lightning; available as web, mobile and desktop application
- [Voltage](https://github.com/benharold/voltage) - Voltage is a macOS GUI for c-lightning
- [Node-launcher](https://github.com/lightning-power-users/node-launcher) - Quickly install BTC and launch the LN desktop app
- [Sparkswap Desktop](https://github.com/sparkswap/sparkswap-desktop) - Buy BTC using USD and LND
- [ShockWizard](https://github.com/shocknet/Wizard) - Install a Shockwallet LND node on any Desktop/Laptop in just a few clicks.

### Web Interfaces

- [fulmo](https://github.com/marzig76/fulmo) - A minimalist c-lightning UI
- [Joule](http://lightningjoule.com) - A browser extension for lnd that enables payments and other interactions with lightning apps (similar to MetaMask)
- [kWh](https://github.com/fiatjaf/kwh) - A browser extension that connects to c-lightning or Eclair nodes and enables interactions with Lightning apps (similar to Joule)
- [kugelblitz](https://github.com/cdecker/kugelblitz) - A simple UI for the c-lightning daemon lightningd and bitcoind
- [lncli-web](https://github.com/mably/lncli-web) - Light-weight web client for the lnd daemon written in NodeJS / Angular
- [Ride The Lightning](https://github.com/ShahanaFarooqui/RTL) - Web Client for LND Daemon written in NodeJS /  Angular 7
- [LND-For-WP](https://github.com/rstmsn/lnd-for-wp) - WordPress plugin for managing & using your LND Node; [WordPress Plugin Directory](https://wordpress.org/plugins/lnd-for-wp/)
- [ThunderHub](https://github.com/apotdevin/thunderhub) - Web UI for managing (multiple) LND Nodes written in TypeScript / React
- [NodeGuard](https://github.com/Elenpay/NodeGuard) - Web-based treasury management solution for lightning nodes

### Command Line Interfaces

- [bos – Balance of satoshis](https://github.com/alexbosworth/balanceofsatoshis) - Advanced tool for LND with powerful rebalancing options and telegram bot support written in NodeJS
- [charge-lnd](https://github.com/accumulator/charge-lnd) - policy based fee manager for LND
- [lntop](https://github.com/edouardparis/lntop) - TUI-based interactive channels dashboard for Unix systems
- [rebalance-lnd](https://github.com/C-Otto/rebalance-lnd) - A script that can be used to balance lightning channels of a lnd node
- [suez](https://github.com/prusnak/suez) - Tool for pretty printing and optimizing Lightning Network channels

### Mobile applications

- [rawtx](https://github.com/rawtxapp/rawtxapp) - A lightning network wallet (Android, iOS); [Homepage](https://rawtx.com)
- [Swift Lightning](https://github.com/biscottigelato/SwiftLightning) - LN wallet build on top of LND for iOS
- [Bitcoin Lightning Wallet](https://play.google.com/store/apps/details?id=com.lightning.walletapp)  - An Android based Lightning Network compatible wallet based on Eclair ([testnet version](https://play.google.com/store/apps/details?id=com.lightning.wallet))
- [Eclair Mobile](https://play.google.com/store/apps/details?id=fr.acinq.eclair.wallet.mainnet2)
- [Globular](https://gitlab.com/inbitcoin/globular) - cross-implementation LN Android remote wallet, connects to a Lighter instance (see [Libraries](#libraries) section)
- [Muun](https://muun.com/) - A Lightning Network wallet for Android. ([Github](https://github.com/muun/apollo))
- [Shockwallet](https://shockwallet.app) - A Lightning SuperApp and Decentralized Social Network. ([Github](https://github.com/shocknet/wallet))
- [Zebedee](https://zbd.gg) - Bitcoin gaming wallet


### Explorers

- [1ML](https://1ml.com/) - 1ML explorer (mainnet + testnet)
- [Amboss.space](https://amboss.space/) - Amboss.space explorer
- [Bitcoin Exchange Rate](https://bitcoinexchangerate.org/lightning) - Lightning network explorer (testnet and mainnet)
- [Lightblock](https://lightblock.me) - lightning network explorer mainnet.
- [Lightning network explorer](https://explorer.acinq.co/) - Lightning network explorer (testnet)
- [List of explorers](https://gist.github.com/bretton/798ec38165ffabc719d91e0f4f67552d) - meta list of visualisers and metrics sites
- [lngraph](https://github.com/xsb/lngraph) - Personal private Lightning Network explorer using Neo4j Browser.
- [Robtex Bitcoin Lightning Explorer](https://www.robtex.com/lightning/node/) - Robtex Bitcoin Lightning Explorer (mainnet)

### Misc

- [lightning-address-nodejs](https://github.com/mefatbear/lightning-address-nodejs) - Simple server for your personal Lightning Address
- [bitcoin-kit-makefile](https://github.com/Perlover/bitcoin-kit-makefile) - Easy installation of full bitcoin and lightning nodes from sources
- [ifpaytt](https://github.com/ElementsProject/ifpaytt) - IFTTT (If Pay Then This) based on Lightning payments; [Blog Post](https://blockstream.com/2018/03/27/ifpaytt-brings-lightning-micropayments-to-ifttt.html)
- [lightning-faucet](https://github.com/lightninglabs/lightning-faucet) - A faucet for the Lightning Network
- [lightning-jukebox](https://github.com/ElementsProject/lightning-jukebox) - A Lightning powered Jukebox; [Blog Post](https://blockstream.com/2018/03/28/lightning-jukebox-offers-a-fun-end-to-our-week-of-lapps.html)
- [LightningBuddy](https://github.com/elaineo/LightningBuddy) - Twitter relay for Lightning JSON-RPC interface.
- [LightningTip](https://github.com/michael1011/lightningtip) LND focused Lightning Tip too, embed in webpage.
- [ln-tip-slack](https://github.com/CryptoFR/ln-tip-slack) - Lightning [Slack](https://slack.com/) Tipbot
- [lnplace](https://github.com/sangaman/lnplace) - Purchase pixels with lightning payments - Submission of [L2 Summit Hackathon](https://innovation.mit.edu/event/l2-summit/)
- [nanotip](https://github.com/ElementsProject/nanotip) - Lightning Tip Box (based on c-lightning); [Blog Post](https://blockstream.com/2018/03/24/tipping-on-lightning-with-nanotip-lapp.html)
- [Carrot](https://earncarrot.com) - Rewards site that lets you earn Bitcoin via Lightning
- [Satoshis.Stream](https://satoshis.stream) - Earn Lightning sats as a podcaster, easily

## Developer Resources

- [Lightning Overview](http://dev.lightning.community/overview/)
- [LND Developers Site](http://dev.lightning.community/)
- [LND Developer Guide](http://dev.lightning.community/guides/)
- [Rusty Russell's BOLT Blog Series](https://medium.com/@rusty_lightning/the-bitcoin-lightning-spec-part-1-8-a7720fb1b4da)
- [LN in a box](https://github.com/bajohns/lightning-in-a-box) - Project that aims to quickly have lnd + btc setup for playing
- [Lightning Dissector](https://github.com/nayutaco/lightning-dissector) - A wireshark plugin to analyze the communication between lightning network nodes. _Currently compatible with ptarmigan and Eclair implementations_
- [C-lightning-plugins](https://github.com/conscott/c-lightning-plugins) - Collection of plugin scripts to control c-lightning

### Tools

- [Polar](https://github.com/jamaljsr/polar) - One-click Bitcoin Lightning networks for local app development & testing
- [Lightning Cash](https://ln.cash) - An app for gifting satoshis
- [Lightning Gifts](https://lightning.gifts) - Another app for gifting satoshis

### Libraries

- [FileBazzar](https://github.com/ElementsProject/filebazaar) - Sell digital files with Lightning
- [Lighter](https://gitlab.com/inbitcoin/lighter) - LN node wrapper for c-lightning, eclair and LND (Python)
- [lightning-charge-client-js](https://github.com/ElementsProject/lightning-charge-client-js) - JavaScript client for lightning-charge
- [lightning-charge-client-php](https://github.com/ElementsProject/lightning-charge-client-php) - PHP client for lightning-charge
- [lightning-charge](https://github.com/ElementsProject/lightning-charge) - A simple drop-in solution for accepting lightning payments (Javascript)
- [lightning-integration](https://github.com/cdecker/lightning-integration) - Lightning Integration Testing Framework
- [lightning-payencode](https://github.com/rustyrussell/lightning-payencode) - Minimal QR-code-ready encoding for requesting lightning payments
- [lightning-php](https://github.com/thorie7912/lightning-php) - PHP client for direct RPC-based access to the c-lightning daemon
- [LightningJ](http://www.lightningj.org/) - LND Integration API for Java
- [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with Lightning
- [ln-service](https://github.com/alexbosworth/ln-service) - Lightning REST Service
- [lncall](https://github.com/michael1011/lncall) - LND implementation of paypercall
- [lnrpc](https://github.com/RadarTech/lnrpc) - Auto-generated LND RPC interface with Typescript type definition support
- [lseed](https://github.com/cdecker/lseed) - A DNS seed for the Lightning Network
- [paypercall](https://github.com/ElementsProject/paypercall) - Charge for HTTP APIs on a per-per-call basis with Lightning
- [webln](https://github.com/wbobeirne/webln) - An app library & set of standards for communication between apps and Lightning clients in the browser (similar to Web3)
- [woocommerce-gateway-lightning](https://github.com/ElementsProject/woocommerce-gateway-lightning) - A WooCommerce gateway for lightning payments
- [wordpress-lightning-publisher](https://github.com/ElementsProject/wordpress-lightning-publisher) - Lightning Publisher for WordPress
- [glightning](https://github.com/niftynei/glightning) - Golang based plugin for c-lightning
- [lightningd-gjson-rpc](https://github.com/fiatjaf/lightningd-gjson-rpc) - [gjson](https://github.com/tidwall/gjson)-based RPC client for c-lightning.
- [Sitzprobe](https://github.com/niftynei/sitzprobe) - A c-lightning plugin that actively sends test payments through the lightning network allowing finding and/or deprecating channels for the payments
- [get-lightning-paid](https://github.com/conscott/get-lightning-paid) - A Flask REST API to generate lightning invoices and payment confirmations
- [lnd-sql](https://github.com/lightning-power-users/lnd-sql) - Output the lnd node data in a relational SQL database
- [Dazaar](http://dazaar.com/) - A library for selling data over a P2P network.

### Tutorials

- [Setting up a local Lightning cluster](http://dev.lightning.community/tutorial/01-lncli/index.html)
- [Using the LND gRPC Client](http://dev.lightning.community/tutorial/03-rpc-client/index.html)
- [Integrating Lightning into a server-side web application](http://dev.lightning.community/tutorial/04-webapp-integration/index.html)
- [How to use a Python gRPC Client with LND](http://dev.lightning.community/guides/python-grpc/)
- [How to use a Javascript gRPC Client with LND](http://dev.lightning.community/guides/javascript-grpc/)
- [Chaincode Labs Lightning Application Residency Videos](https://lightningresidency.com/#videos)
- [Setting up and Testing LND with the Testnet Lightning Faucet](http://lightning.community/lnd/faucet/2017/01/19/lightning-network-faucet/)
- [How to Send Payments via CLI on the Lightning Network](https://andrewgriffithsonline.com/blog/guide-to-make-lightning-network-payments)
- [Using the LND Web Client](http://dev.lightning.community/tutorial/02-web-client/index.html)
- [Setup LND and Bitcoind on Ubuntu 16.04 LTS](https://gist.github.com/bretton/0b22a0503a9eba09df86a23f3d625c13) - Install guide for LND, bitcoind, on Ubuntu, with startup scripts with email alerts.

### Example Projects

- [ilp-lightning-demo](https://github.com/interledgerjs/ilp-lightning-demo) - Demo sending payments between Bitcoin and Litecoin Lightning Networks using Interledger
- [lightning-coindesk](https://github.com/lightninglabs/lightning-coindesk) - An example news app exemplifying Lightning Network micropayments integration

### Simulators

- [lnsim](https://github.com/dianerey/lnsim) - A simulator in OCaml (2017). See also: [Simulating a Decentralized Lightning Network with 10 Million Users](https://hackernoon.com/simulating-a-decentralized-lightning-network-with-10-million-users-9a8b5930fa7a) by Reynolds and [Simulating a Decentralized Lightning Network with 500,000 payments, 0.01% fee per hub and 10 Million Users: 100% success (99.9986%)](https://www.reddit.com/r/Bitcoin/comments/7mwag6/simulating_a_decentralized_lightning_network_with/)
- [LNSim](https://github.com/gdistasi/LNSim/) - A simulator in C++ (2018). See paper (PDF): [Routing payments on the Lightning Network](http://wpage.unina.it/giovanni.distasi/pub/blockchain2018-main.pdf) by Di Stasi et al.
- CLoTH - A simulator in C. See paper [CLoTH: a Simulator for HTLC Payment Networks](https://arxiv.org/abs/1812.09940) by Conoscenti et al. Code not released.
- Blyskavka - A simulator in Java. See paper [Split Payments in Payment Networks](https://www.researchgate.net/publication/327470777_Split_Payments_in_Payment_Networks_ESORICS_2018_International_Workshops_DPM_2018_and_CBT_2018_Barcelona_Spain_September_6-7_2018_Proceedings) by Piatkivskyi and Nowostawski. Code not released.
- [Lightning-Network-Simulator](https://github.com/whiteyhat/Lightning-Network-Simulator) (2019) - A simulator in Java. See [website](https://devpost.com/software/lightning-network-simulator).
- [LNTrafficSimulator](https://github.com/ferencberes/LNTrafficSimulator)

## Learning Resources

- [Lightning FAQ](https://medium.com/@AudunGulbrands1/lightning-faq-67bd2b957d70)
- [Lightning Network Bitcoin Wiki](https://en.bitcoin.it/wiki/Lightning_Network)
- [Radar ION - Guide to joining the Lightning Network](https://ion.radar.tech)
- [Hashed Timelock Contracts](https://en.bitcoin.it/wiki/Hashed_Timelock_Contracts)
- [LN as a Directed Graph; Single-Funded Channel Topology](https://docs.google.com/presentation/d/1G4xchDGcO37DJ2lPC_XYyZIUkJc2khnLrCaZXgvDN0U/edit?pref=2&pli=1#slide=id.g85f425098_0_2) (Slides)
- [How to Do "2-of-3 Multisig Contract" Equivalent on Lightning](https://lists.linuxfoundation.org/pipermail/lightning-dev/2016-January/000403.html) (From LN Mailing List)
- [uselightning.network](https://uselightning.network/)

### Talks

- [Lightning Network Deep Dive with Laolu "Roasbeef" Osuntokun](https://www.youtube.com/watch?v=b_szGaaPPFk) [48:10]
- [SF Bitcoin Devs Seminar: Scaling Bitcoin to Billions of Transactions Per Day](https://www.youtube.com/watch?v=8zVzw912wPo) (Thaddeus Dryja and Joseph Poon)[54:40]
- [Bitcoin, Lightning, and Streaming Money](https://www.youtube.com/watch?v=gF_ZQ_eijPs) (Andreas Antonopoulos) [27:38]
- [Lightning and the Importance of Layer Two](https://www.youtube.com/watch?v=3PcR4HWJnkY) (Elizabeth Stark) [14:15]
- [Bitcoin Q&A: The Lightning Network](https://www.youtube.com/watch?v=vPnO9ExJ50A)  (Andreas Antonopoulos) [7:55]

### Books

- [Mastering the Lightning Network (LN)](https://github.com/lnbook/lnbook)
- [Mastering Bitcoin, 2nd Edition](http://shop.oreilly.com/product/0636920049524.do)
- [Bitcoin and Lightning Network on Raspberry Pi](https://www.apress.com/gp/book/9781484255216)

## Community

- [Lightning Network Community Blog](http://lightning.community/)
- [Lightning Network Twitter Feed](https://twitter.com/lightning)
- [Lightning Network Mailing List](https://lists.linuxfoundation.org/mailman/listinfo/lightning-dev)
- [Lightning Labs Blog](https://blog.lightning.engineering/)
- [Lightning Discord](https://discord.gg/sm2rfS7)
- [Lightning Wiki](https://lightningwiki.net)

### IRC

- [#lightning-dev](https://webchat.freenode.net/?channels=lightning-dev&uio=d4) (on Freenode) - Lightning protocol development
    - [Channel Archive](https://botbot.me/freenode/lightning-dev/)
- [#lnd](https://webchat.freenode.net/?channels=lnd&uio=d4) - Lightning only version of #bitcoin-commits

## Related Lists

- [awesome-bitcoin](https://github.com/igorbarinov/awesome-bitcoin)
- [awesome-blockchain](https://github.com/igorbarinov/awesome-blockchain)
- [Lightning Network Stores](http://lightningnetworkstores.com/)
- [Accept Lightning](https://acceptlightning.com/) - Directory of merchants accepting Lightning payments
- [Robtex LN Directory](https://www.robtex.com/directory/lightning/) - List of lapps and stores.
- [lnroute lists](https://lnroute.com/) - List of resources, lapps and stores.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the author has waived all copyright and
related or neighboring rights to this work.
