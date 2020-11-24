Awesome Moneysocket [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

------------------------------------------------------------------------

A curated list of awesome things related to the Moneysocket protocol. A socket-based protocol for coordinating [Lightning Network](https://github.com/lightningnetwork/lightning-rfc) payments as part of UX and backend services.

DISCLAIMER - Moneysocket is still new, under development and is Reckless with your money. Use this stuff at your own risk.

Documentation
------------------------------------------------------------------------

* (Actual official documentation is forthcoming)
* A [development playlist](https://www.youtube.com/playlist?list=PLqE3dWTuqRc8p8C3O_zlbrkYuGENCaVqp) of demos and discussion journaling the thought process to-date.
* A loose collection of [brainstorm diagrams](https://github.com/moneysocket/prototype/tree/master/doc/diagrams) is in the prototype repo.
*


Protocol Implementations
------------------------------------------------------------------------

* [js-moneysocket](https://github.com/moneysocket/js-moneysocket) - Reference JavaScript Library
* [py-moneysocket](https://github.com/moneysocket/py-moneysocket) - Reference Python Library
*

Infrastructure
------------------------------------------------------------------------

* [terminus](https://github.com/moneysocket/terminus) - The terminus application for providing Moneysocket connections that interface Lightning Network node software. Runs as either a C-Lightning Plugin or LND wrapper.
* [relay](https://github.com/moneysocket/relay) - Websocket relay application for providing a rendezvous service for two Moneysocket connections and forwards end-to-end-encrypted messages between them. (this app runs at wss://relay.socket.money).
* [stabled](https://github.com/moneysocket/stabled) - Stablewallet daemon that consumes a Bitcoin-based Moneysocket connection on the backend and provides a stable Fiat-currency-based balance on the frontend. The provided connections can transact via satoshis on the LN while maintaining the stable balance.
*


Wallets
------------------------------------------------------------------------
* [web-wallet](https://github.com/moneysocket/web-wallet) - A browser-based JavaScript wallet that consumes a Moneysocket connection and also provides an outgoing connection.
*

Applications
------------------------------------------------------------------------
* [Satopong](https://github.com/drschwabe/satopong) - A (WIP) application to stake satoshis on the outcome of a Pong game.
* [Opinion Buyer and Seller](https://github.com/moneysocket/prototype/tree/master/browser) - A prototype application of how a [buyer](https://github.com/moneysocket/prototype/blob/master/browser/src/js/buyer.js) and [seller](https://github.com/moneysocket/prototype/blob/master/browser/src/js/seller.js) app can define a custom extension to the Moneysocket protocol for buying/selling digital goods over a connection.

Utilities
------------------------------------------------------------------------
* [Beacon Codec](https://github.com/moneysocket/prototype/blob/master/browser/src/js/encode-decode.js) - A browser-based beacon coder and decoder utility. (TODO - host this somewhere)
