# Awesome Monero List

A curated list of awesome Monero libraries, tools, and resources.

## Contents

- [Resources](#resources)
- [Wallets](#wallets)
- [Libraries](#libraries)
- [Docker](#docker)
- [Tools](#tools)
- [Nodes](#nodes)
- [Blockchain Explorers](#blockchain-explorers)
- [Decentralized Exchanges](#decentralized-exchanges)
- [Built with Monero](#build-with-monero)
- [Mining](#mining)
- [Atomic Swaps](#atomic-swaps)
- [Integrations](#integrations)
- [Merchants](#merchants)
- [Point of Sale](#point-of-sale)
- [Future development](#future-development)
- [Other](#other)

## Resources

- [Official Website](https://getmonero.org/)
- [Official GitHub](https://github.com/monero-project/monero)
- [Official Twitter](https://twitter.com/monero)
- [Official Reddit](https://www.reddit.com/r/Monero/)
- [Unofficial Docs](https://docs.monero.study/)
- [Monero Research Lab](https://github.com/monero-project/research-lab)

- [Implementing Seraphis](https://raw.githubusercontent.com/UkoeHB/Seraphis/master/implementing_seraphis/Impl-Seraphis-0-0-2.pdf)
- [RandomX](https://github.com/tevador/RandomX) - RandomX is a proof-of-work (PoW) algorithm that is optimized for general-purpose CPUs.
- [LMDB](https://github.com/LMDB/lmdb) - Lightning Memory-Mapped Database

### Books

- [Mastering Monero](https://github.com/monerobook/monerobook) - "Mastering Monero: The future of private transactions" is your guide through the world of Monero, a leading cryptocurrency with a focus on private and censorship-resistant transactions. This book contains everything you need to know to start using Monero in your business or day-to-day life, even if you've never understood or interacted with cryptocurrencies before.
- [monero-book](https://github.com/Cuprate/monero-book) - This book aims to document the Monero protocol. Currently, work is being done to document Monero's consensus rules. This being completed as a part of [Cuprate](https://github.com/Cuprate/cuprate), the Rust Monero node. ([Website](https://monero-book.cuprate.org/))

## Wallets

### Desktop Wallets

- [Monero GUI Wallet](https://getmonero.org/downloads/) - Official desktop wallet
- [Feather Wallet](https://github.com/feather-wallet/feather) ([Website](https://featherwallet.org/)) - Lightweight desktop wallet
- [monero-wallet-generator](https://github.com/moneromooo-monero/monero-wallet-generator) - Self contained offline javacsript Monero wallet generator

### Mobile Wallets

- [Cake Wallet](https://github.com/cake-tech/cake_wallet) - Popular iOS wallet
- [Monerujo](https://github.com/m2049r/xmrwallet) - Popular Android wallet
- [Stack Wallet](https://github.com/cypherstack/stack_wallet) - A multicoin, cryptocurrency wallet 
- [ANONERO](http://anonero.io/) - Hardened wallet with enforced privacy & security (Onion link)

### Hardware Wallets

- [Kastelo](https://github.com/monero-project/kastelo) - This is the project to create an official Monero Hardware Wallet (Dead project)
- [passport2-monero](https://github.com/mjg-foundation/passport2-monero) - v2.x.x series of firmware for Passport, rebuilt for monero 
- [MoneroSigner](https://github.com/Monero-HackerIndustrial/MoneroSigner) - Seedsigner Monero fork. Use an air-gapped Raspberry Pi Zero to sign monero transactions!
- [Monero Ledger App](https://github.com/LedgerHQ/app-monero) - Monero wallet application for Ledger Nano S and Nano X. (avoid buying Ledger products)

### Other Wallets
[Monero Subscriptions Wallet](https://github.com/lukeprofits/Monero_Subscriptions_Wallet) - A Monero wallet that automatically pays subscriptions.

## Libraries

- [monero-ts](https://github.com/woodser/monero-ts) - Monero TypeScript library for Node.js and browsers
- [monerophp](https://github.com/monero-integrations/monerophp) - A Monero library written in PHP by the Monero Integrations team.
- [monero-python](https://github.com/monero-integrations/monero-python) -  A comprehensive Python module for handling Monero cryptocurrency
- [monero-rpc-php](https://github.com/refring/monero-rpc-php) - Monero daemon and wallet RPC client library written in modern PHP.
- [monero-java](https://github.com/woodser/monero-java) - Java library for using Monero 
- [monero-rs](https://github.com/monero-rs/monero-rs) - Library with support for de/serialization on block data structures and key/address generation and scanning related to Monero cryptocurrency.
- [libmonero](https://github.com/monumexyz/libmonero) - libmonero is a library for the Monero cryptocurrency written in Rust. It is designed to be fast, safe and easy to use.
- [monero-cpp](https://github.com/woodser/monero-cpp) - C++ library for using Monero
- [go-monero-rpc-client](https://github.com/omani/go-monero-rpc-client) - A go client for the Monero wallet and daemon RPC
- [go-monero](https://github.com/duggavo/go-monero) - A multi-platform Go library for interacting with Monero servers either on clearnet or not, supporting daemon and wallet RPC, p2p commands and ZeroMQ.

## Docker

- [Simple Monerod Docker](https://github.com/sethforprivacy/simple-monerod-docker) - A simple docker image for running a Monero node.
- [Monero Suite](https://github.com/hundehausen/monero-suite) - Build your personal docker-compose.yml file for Monero services. 
- [Docker-XMRig](https://github.com/metal3d/docker-xmrig) - Xmrig containeried to mine monero cryptocurrency
- [Moneroblock Docker](https://github.com/sethforprivacy/moneroblock-docker) - A simple and straightforward Dockerized MoneroBlock built from source and exposing standard ports.

## Tools

- [Monero Inflation Checker](https://github.com/DangerousFreedom1984/monero_inflation_checker) - Minimal Python tools and educational material for checking inflation in Monero. You can get more information at moneroinflation.com.
- [Monero Vanity Address Generator](https://github.com/hinto-janai/monero-vanity) - Monero vanity address generator for CPUs
- [monero-lws](https://github.com/vtnerd/monero-lws) - Monero Light Wallet Server (scans monero viewkeys and implements mymonero API)

## Nodes

- [Monero Node List](https://moneroworld.com/) - A list of public Monero nodes.
- [Monero Node Scanner](https://monerohash.com/nodes-distribution.html) - A tool to scan the Monero network for nodes.
- [monero.fail](https://monero.fail/) -  Monero public node aggregator.
- [Monerod-in-Termux](https://github.com/CryptoGrampy/android-termux-monero-node) - Run a Monero Node on Android using Termux
- [check-monero-seed-nodes](https://github.com/plowsof/check-monero-seed-nodes) - A script to check the status of Monero seed nodes
- [Monero Node for Umbrel](https://github.com/deverickapollo/umbrel-monero) - Run a Monero node on your Umbrel personal server.
- [xmr.sh](https://github.com/vdo/xmr.sh) - xmr.sh script wizard sets up a new server running a monero node daemon with Docker compose, with your choice of SSL certificates for your domain, network selection, a Tor hidden service, Grafana dashboard and more.

## Blockchain Explorers

- [Onion Monero Blockchain Explorer](https://github.com/moneroexamples/onion-monero-blockchain-explorer) - A Monero blockchain explorer.
- [Moneroblock](https://github.com/duggavo/MoneroBlock) -  Decentralized and trustless Monero block explorer

## Decentralized Exchanges

- [Bisq](https://bisq.network/) - A decentralized exchange network for trading Monero and other cryptocurrencies.
- [Haveno](https://github.com/woodser/haveno) - A decentralized, peer-to-peer, non-custodial Monero exchange for trading fiat currencies for Monero.
- [Serai](https://github.com/serai-dex/serai) - Serai is a new DEX, built from the ground up, initially planning on listing Bitcoin, Ethereum, DAI, and Monero, offering a liquidity-pool-based trading experience. Funds are stored in an economically secured threshold-multisig wallet.

## Built with Monero

- [Nerostr](https://github.com/pluja/nerostr) -  nostr paid relay, but with monero
- [NEVEKO](https://github.com/creating2morrow/neveko) - full-stack privacy application with gpg messaging, monero multisig and built-in i2p marketplace

## Mining

- [XMRig](https://github.com/xmrig/xmrig) - High performance, open source, cross platform RandomX, CryptoNight and Argon2 CPU/GPU miner
- [Gupax](https://github.com/hinto-janai/gupax) - A simple GUI for mining Monero on P2Pool, using XMRig.
- [P2Pool](https://github.com/SChernykh/p2pool) - P2Pool is a decentralized Monero mining pool that works by creating a peer-to-peer network of miner nodes.
- [XMRig Proxy](https://github.com/xmrig/xmrig-proxy) - Stratum proxy with Web interface, support for several backup pools, and more.
- [Docker-XMRig](https://github.com/metal3d/docker-xmrig) - Xmrig containeried to mine monero cryptocurrency
- [MoneroOS](https://github.com/4rkal/MoneroOS) - Plug and play monero mining archuseriso config
- [XMRig for Android](https://github.com/XMRig-for-Android/xmrig-for-android) - ⛏ Mine Monero from your android device 

## Atomic Swaps

- [XMR to BTC Atomic Swap](https://github.com/comit-network/xmr-btc-swap) - Bitcoin–Monero Cross-chain Atomic Swap
- [ETH-XMR Atomic Swaps](https://github.com/AthanorLabs/atomic-swap) - 💫 ETH-XMR atomic swap implementation
- [UnstoppableSwap GUI](https://github.com/UnstoppableSwap/unstoppableswap-gui) - Graphical User Interface (GUI) For Trustless Cross-Chain XMR<>BTC Atomic Swaps
- [BCH-XMR-SWAP PoC](https://github.com/PHCitizen/bch-xmr-swap) - A proof of concept for a Bitcoin Cash to Monero atomic swap
- [Farcaster Project](https://github.com/farcaster-project) - Farcaster is a cross-chain atomic swap protocol and implementation who allows to exchange Bitcoin and Monero in a peer-to-peer manner with anyone running a Farcaster node.


## Merchants

- [Monero Merchants](https://www.monerooutreach.org/stories/monero_merchants.html) - A list of merchants that accept Monero as payment.
- [Monerica](https://github.com/monerica-project/monerica) ([Website](https://monerica.com/)) - A directory for a Monero circular economy
- [Monero for Merchants](https://github.com/ASchmidt1024/monero-for-merchants-booklet) - A printable booklet to attract merchants to accept Monero (multiple languages!)

## Point of Sale

- [Kasisto](https://github.com/amiuhle/kasisto) - A Monero Point of Sale payment system 
- [Monero Gateway for WooCommerce](https://github.com/monero-integrations/monerowp) - A Monero WooCommerce Plugin for Wordpress 
- [MoneroPay](https://github.com/moneropay/moneropay) - A Monero payment gateway for WooCommerce
- [Monero Merchant](https://github.com/RuiSiang/monero-merchant) - Monero Merchant is a RESTful API wrapper for the official Monero wallet RPC. This project is mainly for merchants who hope to accept Monero as payment.
- [AcceptXMR](https://github.com/busyboredom/acceptxmr) - This library aims to provide a simple, reliable, and efficient means to track monero payments.
- [HotShop](https://github.com/CryptoGrampy/HotShop) - An Ephemeral, browser-based, no-private-key, no-server Point of Sale for receiving and validating Monero payments. Repository is archived :(
- [monerochan-merchant-rpc](https://github.com/spirobel/monerochan-merchant-rpc) - A tool to accept digital cash at your online business.

## Future development

- [Seraphis](https://github.com/UkoeHB/Seraphis) - Seraphis is a privacy-focused transaction protocol for p2p electronic cash systems (e.g. cryptocurrencies).
- [Full chain membership proofs](https://github.com/kayabaNerve/full-chain-membership-proofs)
- [Cuprate](https://github.com/Cuprate/cuprate) - an upcoming experimental, modern & secure monero node. Written in Rust.
- [wallet3](https://github.com/seraphis-migration/wallet3) - Info and discussions about a hypothetical full 'wallet2' rewrite from scratch 