Awesome Moneysocket [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

------------------------------------------------------------------------

A curated list of awesome things related to the Moneysocket protocol. A socket-based protocol for coordinating [Lightning Network](https://github.com/lightningnetwork/lightning-rfc) payments as part of UX and backend services.

DISCLAIMER - Moneysocket is still new, under development and is Reckless with your money. Use this stuff at your own risk.


Documentation
------------------------------------------------------------------------

* (Actual official documentation is forthcoming)
* [Stablewallet Leatherpaper](https://socket.money/leatherpaper.html) - A brief standalone explanation of the Stablewallet concept
* A [development playlist](https://www.youtube.com/playlist?list=PLqE3dWTuqRc8p8C3O_zlbrkYuGENCaVqp) of demos and discussion journaling the thought process to-date.
* A loose collection of [brainstorm diagrams](https://github.com/moneysocket/prototype/tree/master/doc/diagrams) is in the prototype repo in [.dia](https://en.wikipedia.org/wiki/Dia_%28software%29) format.


Protocol Implementations
------------------------------------------------------------------------

* [js-moneysocket](https://github.com/moneysocket/js-moneysocket) - Reference JavaScript Library
* [py-moneysocket](https://github.com/moneysocket/py-moneysocket) - Reference Python Library

* [moneysocket-go](https://github.com/xplorfin/moneysocket-go) - In-progress Go implementation.

Infrastructure
------------------------------------------------------------------------

* [terminus](https://github.com/moneysocket/terminus) - The terminus application for providing Moneysocket connections that interface Lightning Network node software. Runs as either a C-Lightning Plugin or LND wrapper.
* [relay](https://github.com/moneysocket/relay) - Websocket relay application for providing a rendezvous service for two Moneysocket connections and forwards end-to-end-encrypted messages between them. (this app runs at wss://relay.socket.money).
* [stabled](https://github.com/moneysocket/stabled) - Stablewallet daemon that consumes a Bitcoin-based Moneysocket connection on the backend and provides a stable Fiat-currency-based balance on the frontend. The provided connections can transact via satoshis on the LN while maintaining the stable balance.


Wallets
------------------------------------------------------------------------
* [Costanza Wallet](https://github.com/moneysocket/costanza) - A browser-based wallet for Moneysocket. It's key feature is that provides an upstream Moneysocket connection to an app and allows you to control the permissions for spending via that connection. It is not meant to compete with leading wallets for daily driver use. It's purpose is to assist bootstrapping the Moneysocket protocol by pioneering presenting something approximating what a real-world user will experience from a Moneysocket-enabled wallet. A build is hosted [here](https://socket.money/wallet).

* (Deprecated - use Costanza 👍) [web-wallet](https://github.com/moneysocket/web-wallet) - A browser-based JavaScript wallet that consumes a Moneysocket connection and also provides an outgoing connection. This was very basic to get started, but not intended for real use and will make your eyes bleed.


Applications
------------------------------------------------------------------------
* [Moon Money Mover 3000](https://github.com/moneysocket/mover) - A simple application for moving money between two Moneysocket provider connections. A build is hosted [here](https://socket.money/mover)
* [Satopong](https://github.com/drschwabe/satopong) - A (WIP) application for a Moneysocket-driven arcade game of Pong.
* [Opinion Buyer and Seller](https://github.com/moneysocket/bs-demo) - a demo of the definition a custom extension to the Moneysocket protocol for buying/selling particular digital goods over a connection. A build is hosted for the [buyer](https://socket.money/bs-demo/buyer.html) and the [seller](https://socket.money/bs-demo/seller.html)

Utilities
------------------------------------------------------------------------
* [Beacon Codec](https://github.com/moneysocket/beacon-codec) - A browser-based beacon coder and decoder utility. A build is hosted [here](https://socket.money/codec).

Project Links
------------------------------------------------------------------------

- [Homepage](https://socket.money).
- [Twitter](https://twitter.com/moneysocket)
- [Telegram](https://t.me/moneysocket)
- [Donate](https://socket.money/#donate)
