# ₿ Awesome Crypto Currency Tools & Algorithms

[![GitHub stars](https://img.shields.io/github/stars/kennethreitz/awesome-coins.svg?style=social&label=Star)](https://github.com/kennethreitz/awesome-coins)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Say Thanks!](https://img.shields.io/badge/SayThanks-!-1EAEDB.svg)](https://saythanks.io/to/kennethreitz)

From Wikipedia—
> A [cryptocurrency](https://en.m.wikipedia.org/wiki/Cryptocurrency) is a digital asset designed to work as a medium of exchange using cryptography to secure the transactions and to control the creation of additional units of the currency.

Many algorithms are used in different crypto–currencies. This document references which algorithms are used in crypto-currencies, and provide a nice list of helpful services and utilities for managing coins.

## So, Before We Begin…

This "coin" stuff may be confusing if you are not familiar with algorithms and data structures. Let me explain what I know so far — 

There are many, many [coins](http://coinbin.org/coins). People like to [trade](https://www.cryptopia.co.nz/Register?referrer=kennethreitz) them, not unlike stocks or Pokémon cards. People also [mine](https://www.nicehash.com/?refby=386829) them, using their home computers or specialized hardware.

Coins are stored in wallets which can be hosted online, on your local computer, or on a sheet of paper.

It is hard to mine a coin on your own, and is like gambling, so people usually opt to join a pool (which typically use the `stratum` protocol to coordinate) — this rewards you for your work, even if you didn't find anything because you helped contribute with thousands of other people, some of whom did find blocks. The blocks are then split up, based on the pool's rules.

Some people [rent hashing power](https://www.nicehash.com/?refby=386829) from farms and either play the "blockchain lottery", trying to find blocks of coins on their own, or they point the farm at a pool, like a typical home miner — except they have a tremendously high amount of computational power available to them, if they're willing to pay for it.

Hope that helps clear things up.

## ☤ Support Causes You Care About

- [Wikileaks](https://wikileaks.org) **BTC**: `1HB5XMLmzFVj8ALj6mfBsbifRoD4miY36v`
- [Internet Archive](https://archive.org) **BTC**: `1Archive1n2C579dMsAu3iC6tWzuQJz8dN`
- [The Pirate Bay](https://thepiratebay.org) **BTC**: `129TQVAroeehD9fZpzK51NdZGQT4TqifbG`
- [xkcd](https://xkcd.com) **BTC**: `14Tr4HaKkKuC1Lmpr2YMAuYVZRWqAdRTcr`
- [this repo](https://github.com/kennethreitz/awesome-coins) **BTC**: `1Me2iXTJ91FYZhrGvaGaRDCBtnZ4KdxCug`

## ☤ Coin Market Tools & Utilities

- **[Coinbin.org](http://coinbin.org)** — Human–friendly API for quickly getting coin data (exchange rates, predictions, &c.)
    * [List of All Known Coins](http://coinbin.org/coins) `/coins`
    * [BTC Current Value](http://coinbin.org/btc) `/btc`
    * [BTC Daily Historical Value](http://coinbin.org/btc/history) `/btc/history`
    * [BTC / ETH Exchange Rate](http://coinbin.org/btc/to/eth) `/btc/to/eth`
    * [20.01 BTC Value](http://coinbin.org/btc/20.01) `/btc/20.01`
    * [42 ETH Value in BTC](http://coinbin.org/eth/42/to/btc) `/eth/42/to/btc`
    * Supports all crypto–currencies.
- [CoinMarketCap](https://coinmarketcap.com) — Shows all currencies on a real-time dashboard.
- [CoinScanner.co](https://coinscanner.co/) — Gives you multiple trade routes from 1 crypto to another.

## ☤ Reading Material

- [Overview of Cryptocurrencies](https://github.com/kilimchoi/cryptocurrency) — GitHub Repo.
- [Map of Coins](http://mapofcoins.com) – Explore the visualized history of the cryptocurrencies, from their whitepapers up to present days.
- [A massive collection of white papers](http://diyhpl.us/~bryan/papers2/bitcoin/)
- [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook) (ebook)
- [Binance Academy](https://www.binance.vision) — Open access education provided by Binance.
- [Bitcoin Developer Reference](https://bitcoin.org/en/developer-reference)
- [Blockchain for humans](https://github.com/anderson-joyle/blockchain-for-humans) — Ultra-simplified blockchain explanation (in construction).
- [r/CryptoCurrency](https://www.reddit.com/r/CryptoCurrency/) — Official subreddit about crypto-currencies and crypto-assets.
- [Golden Cryptocurrency and Blockchain Cluster](https://golden.com/wiki/Cluster%3A_Blockchain_%26_cryptocurrency) - a cluster of topic pages on cryptocurrency and blockchain.
- Publications
    * [Cryptoeconomics](https://medium.com/@cryptoeconomics) / The team at cryptoeconomics.com.au
    * [Minessence](https://vinnylingham.com/) / Vinny Lingham, Co-founder & CEO of Civic.com
    * [CryptoOracle](https://medium.com/crypto-oracle) / Lou Kerner
    * [CryptoCurrencyHub](https://cryptocurrencyhub.io/)
    * [Build Blockchain](https://www.buildblockchain.tech/newsletter/issues/)
    * Hackernoon's
      * [Blockchain](https://hackernoon.com/blockchain/home)
      * [Bitcoin](https://hackernoon.com/bitcoin/home)
      * [Coin & Crypto](https://medium.com/@coinandcrypto) 
      * [Daniel Jeffries](https://hackernoon.com/@dan.jeffries)

## ☤ Coin Mining Pools

Here's a list of [WhatToMine](https://whattomine.com).

- **#**: [https://www.nicehash.com/](https://www.nicehash.com/?refby=386829) — Mine any algo (optimized for your GPU) & get paid in **BTC**.
- **BTC**: https://pool.bitcoin.com/
- **ETH**: https://eth.nanopool.org/
- **SC**: https://sia.nanopool.org/
- **PASC**: https://pasc.nanopool.org/
- **XMR**: https://xmr.nanopool.org/
- **ZEC**: https://zec.nanopool.org/
- **ETC**: https://etc.nanopool.org/
- **ZCL**: https://2miners.com/zcl-mining-pool
- **ZEN**: https://2miners.com/zen-mining-pool
- **ZEC**: https://2miners.com/zec-mining-pool

## ☤ Hashing Power for Rent

- [NiceHash](https://www.nicehash.com/?refby=386829) — Supports all popular algos, pay in **BTC** for raw throughput.
- [Bitcoin.com Pool](https://pool.bitcoin.com/index_en.html) — I've heard good things.
- [BitMain Hosted](https://bitmainwarranty.com/product-category/hosting/) — Looks complicated and sketchy, but they offer hosted ASIC solutions.

## ☤ Coin Wallets

### Hosted Coin Wallets

**Notice:** the coin community frowns upon use of these services, as you are not in direct control of your coins — in fact, you don't own them at all — the service does — much like the way a standard bank operates.

- [Coinbase **BTC**](https://www.coinbase.com/join/516f7e9a929bda3e06000001)
- [Coinbase **ETH**](https://www.coinbase.com/join/516f7e9a929bda3e06000001)
- [Coinbase **LTC**](https://www.coinbase.com/join/516f7e9a929bda3e06000001)

Actual Hosted Coin Wallets:

- [MyEtherWallet **ETH**](https://www.myetherwallet.com/)
- [Tokenary **ETH&ERC20 Tokens**](https://www.tokenary.io/)
- [Dogechain **DOGE**](https://my.dogechain.info/#/wallet)
- [Gamecredits **GAME**](https://wallet.gamecredits.com/dashboard/myWallet)
- [Glif **FIL**](https://github.com/openworklabs/filecoin-web-wallet)

### Coin Debit Cards

- [Cryptopay **BTC** Debit Card](https://cryptopay.me/join/03db9c17)

### Physical Coin Wallets

- [**Sia** Paper Wallet](https://siapaperwallet.co)
- [WalletGenerator.net](https://walletgenerator.net)
- [Cryptosteel](https://cryptosteel.com) — Made of steel!

## ☤ Coin Exchanges

- [Binance](https://www.binance.com) — Exchange the world. 
- [Cryptopia](https://www.cryptopia.co.nz/Register?referrer=kennethreitz) — Wallets for all currencies, trading to/from all currencies.
- [Shapeshift](https://shapeshift.io/#/coins) — The fastest exchange on Earth.
- [Bittrex](https://bittrex.com) — Wallets for all currencies, trading to/from all currencies.
- [Qvolta](https://qvolta.com) — Sell and buy crypto assets around the world for local payment methods.
- [InstaEx](https://instaex.io) - Instant Cryptocurrency Exchange.
- [ExchangeRates.Pro](https://exchangerates.pro) — Price comparison of exchanges worldwide, including the P2P market.


## ☤ Universal GUI Apps

- [**Sia** UI](http://sia.tech/apps/) — SC wallet, file hosting, storage.
- [**LBRY**](https://lbry.io) — LBRY wallet, media consumption & publishing platform.

## ☤ Windows GUI Apps

- [NiceHash Miner](https://miner.nicehash.com/?refby=386829) — Resells your GPU/CPU to miners for profit! Benchmarks all algos against your hardware, and automatically picks the most profitable configuration (adjustable).

[![](https://miner.nicehash.com/images/landing-pages/nhm/nhm2.svg)](https://miner.nicehash.com/?refby=386829)
- [MinerGate](https://minergate.com) - Mine the most profitable cryptocurrency.

## ☤ MacOS GUI Apps

- [MacMiner](http://macminer.fabulouspanda.com/macminer/) — Wraps bfgminer, cgminer, and sgminer in a GUI.

## ☤ MacOS CLI Apps

- [bfgminer](http://macminer.fabulouspanda.com/commandline/) — Modular ASIC/FPGA miner written in C, featuring overclocking, monitoring, fan speed control and remote interface capabilities.
- [cgminer](http://macminer.fabulouspanda.com/commandline/) — ASIC and FPGA miner in C for Bitcoin.
- [sgminer](http://macminer.fabulouspanda.com/commandline/) — Scrypt GPU miner.
- [nheqminer](https://github.com/kozyilmaz/nheqminer-macos) — Equihash CPU & GPU miner.

## ☤ Recommended Hardware

- [NVidia GTX 1080 TI OC](http://amzn.to/2wl1c9j) — The most powerful consumer graphics card in the world.
- [Asrock H110 Pro BTC+ Mining Motherboard](http://amzn.to/2xadkYk) — Can apparently host 12x PCI-E GPUs.

## ☤ Cool Coin/Blockchain Stuff

- [Bit](https://github.com/ofek/bit) — Python’s fastest Bitcoin library with an API allowing transactions
  to be made in only 3 lines of code.
- [bcoin](http://bcoin.io) — Bitcoin fullnode implementation written entirely in Node.js that you can even run in a browser, includes wallet, mempool, chain, and mining. 
- [**BTC** Mempol and Fee Explorer](https://core.jochen-hoenicke.de/queue/#4d)
- [Tezos](https://www.tezos.com) — Self-healing blockchain.
- [Tendermint](https://tendermint.com) — Byzantine fault-tolerant replicated state machines in any programming language.
- [Cosmos](https://cosmos.network) — Network and a framework for interoperability between blockchains.
- [URI scheme for Blockchain exploration](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-August/010712.html)
- [Blockply](https://blockply.com/) — Collection of the most interesting and outstanding blockchain projects
- [Blockchain demo](https://github.com/anders94/blockchain-demo) — Web-based demonstration of blockchain concepts.

## ☤ Algos supported by [NiceHash Stratum Proxy](https://www.nicehash.com/?refby=386829)

- `Scrypt` (Litecoin / **[LTC](http://coinbin.org/ltc)**)
- `SHA256` (Bitcoin / **[BTC](http://coinbin.org/btc)**)
- `ScryptNF` (Scrypt-Adaptive-Nfactor) (GPU Coin, **GPUC**)
- `X11` (Dash / Darkcoin, Dashcoin, ASIC-Resistant)
- `X13` (MaruCoin / **MARU**) (CPU/GPU)
- `Keccak` (MaxCoin / **MAX**)
- `X15` (HTML5 Coin, **HTML5**)
- `Nist5` (Talkcoin, **TAC**)
- `NeoScrypt` (Phoenixcoin (**PXC**), Imperialcoin (**IPC**), Feathercoin (**FTC**), UFOcoin (**UFO**), Guncoin (**GUN**), Bollywoodcoin (**BDC**), Orbitcoin (**ORB**), Halcyon (**HAL**))
- `Lyra2RE` (VertCoin / **VTC**, CryptoCoin)
- `WhirlpoolX` (Vanillacoin / **VNL**)
- `Qubit` (QuibitCoin / **Q2C**)
- `Quark` (**QRK**)
- `Axiom` (Axiom Coin / **AXIOM**)
- `Lyra2REv2` (VertCoin / **VTC**)
- `ScryptJaneNf16` (Diamond / **DMD**)
- `Blake256r8` (Blake Coin / **BLC**)
- `Blake256r14` (Blake Coin / **BLC**)
- `Blake256r8vnl` (Blake Coin / **BLC**)
- `Hodl` (HodlCoin / **HODL**)
- `DaggerHashimoto` (Ethereum / **ETH**)
- `Decred` (**DCR**)
- `CryptoNight` (**XCN**, CPU-only)
- `Lbry` (**LBC**)
- `Equihash` (Zcash / **XEC**, ZClassic, **HUSH**, Komodo)
- `Pascal` (**PASC**)
- `X11Gost` (SIBCoin / **SIB**)
- `Sia` (**SC**)
- `Blake2`s (NevaCoin, Netko Coin, Verge, TajCoin)
- `Skunk` (Signatum Coin / **SIGT**)

[(others)](https://github.com/kennethreitz/awesome-coins/blob/master/other.md)

## ☤ Every Active Coin, Ranked

As of 2017-08-23:

[btc](https://coinbin.org/btc)
[eth](https://coinbin.org/eth)
[xrp](https://coinbin.org/xrp)
[ltc](https://coinbin.org/ltc)
[etc](https://coinbin.org/etc)
[xem](https://coinbin.org/xem)
[miota](https://coinbin.org/miota)
[dash](https://coinbin.org/dash)
[bts](https://coinbin.org/bts)
[strat](https://coinbin.org/strat)
[xmr](https://coinbin.org/xmr)
[zec](https://coinbin.org/zec)
[gnt](https://coinbin.org/gnt)
[bcn](https://coinbin.org/bcn)
[waves](https://coinbin.org/waves)
[steem](https://coinbin.org/steem)
[sc](https://coinbin.org/sc)
[icn](https://coinbin.org/icn)
[xlm](https://coinbin.org/xlm)
[bcc](https://coinbin.org/bcc)
[lsk](https://coinbin.org/lsk)
[doge](https://coinbin.org/doge)
[rep](https://coinbin.org/rep)
[ans](https://coinbin.org/ans)
[fct](https://coinbin.org/fct)
[game](https://coinbin.org/game)
[ardr](https://coinbin.org/ardr)
[gno](https://coinbin.org/gno)
[maid](https://coinbin.org/maid)
[dgb](https://coinbin.org/dgb)
[dcr](https://coinbin.org/dcr)
[kmd](https://coinbin.org/kmd)
[gbyte](https://coinbin.org/gbyte)
[bat](https://coinbin.org/bat)
[nxt](https://coinbin.org/nxt)
[dgd](https://coinbin.org/dgd)
[1st](https://coinbin.org/1st)
[veri](https://coinbin.org/veri)
[mgo](https://coinbin.org/mgo)
[usdt](https://coinbin.org/usdt)
[sngls](https://coinbin.org/sngls)
[nmr](https://coinbin.org/nmr)
[sys](https://coinbin.org/sys)
[btcd](https://coinbin.org/btcd)
[pivx](https://coinbin.org/pivx)
[ant](https://coinbin.org/ant)
[ubq](https://coinbin.org/ubq)
[mcap](https://coinbin.org/mcap)
[emc](https://coinbin.org/emc)
[ppc](https://coinbin.org/ppc)
[ppy](https://coinbin.org/ppy)
[ark](https://coinbin.org/ark)
[round](https://coinbin.org/round)
[lkk](https://coinbin.org/lkk)
[rlc](https://coinbin.org/rlc)
[rdd](https://coinbin.org/rdd)
[sjcx](https://coinbin.org/sjcx)
[qrl](https://coinbin.org/qrl)
[mln](https://coinbin.org/mln)
[xas](https://coinbin.org/xas)
[lbc](https://coinbin.org/lbc)
[amp](https://coinbin.org/amp)
[wings](https://coinbin.org/wings)
[nxs](https://coinbin.org/nxs)
[leo](https://coinbin.org/leo)
[nmc](https://coinbin.org/nmc)
[xcp](https://coinbin.org/xcp)
[xvg](https://coinbin.org/xvg)
[bay](https://coinbin.org/bay)
[edg](https://coinbin.org/edg)
[blk](https://coinbin.org/blk)
[omni](https://coinbin.org/omni)
[myst](https://coinbin.org/myst)
[xzc](https://coinbin.org/xzc)
[nlg](https://coinbin.org/nlg)
[via](https://coinbin.org/via)
[burst](https://coinbin.org/burst)
[cfi](https://coinbin.org/cfi)
[vtc](https://coinbin.org/vtc)
[cloak](https://coinbin.org/cloak)
[mona](https://coinbin.org/mona)
[xaur](https://coinbin.org/xaur)
[eac](https://coinbin.org/eac)
[dice](https://coinbin.org/dice)
[grc](https://coinbin.org/grc)
[ybc](https://coinbin.org/ybc)
[block](https://coinbin.org/block)
[obits](https://coinbin.org/obits)
[nav](https://coinbin.org/nav)
[vsl](https://coinbin.org/vsl)
[trst](https://coinbin.org/trst)
[pot](https://coinbin.org/pot)
[hmq](https://coinbin.org/hmq)
[exp](https://coinbin.org/exp)
[gup](https://coinbin.org/gup)
[tkn](https://coinbin.org/tkn)
[bash](https://coinbin.org/bash)
[xdn](https://coinbin.org/xdn)
[edr](https://coinbin.org/edr)
[ioc](https://coinbin.org/ioc)
[enrg](https://coinbin.org/enrg)
[rads](https://coinbin.org/rads)
[note](https://coinbin.org/note)
[nxc](https://coinbin.org/nxc)
[shift](https://coinbin.org/shift)
[moon](https://coinbin.org/moon)
[wdc](https://coinbin.org/wdc)
[unity](https://coinbin.org/unity)
[xel](https://coinbin.org/xel)
[qau](https://coinbin.org/qau)
[taas](https://coinbin.org/taas)
[bnt](https://coinbin.org/bnt)
[xbc](https://coinbin.org/xbc)
[sky](https://coinbin.org/sky)
[ion](https://coinbin.org/ion)
[snt](https://coinbin.org/snt)
[agrs](https://coinbin.org/agrs)
[neos](https://coinbin.org/neos)
[qrk](https://coinbin.org/qrk)
[zrc](https://coinbin.org/zrc)
[vrc](https://coinbin.org/vrc)
[dbix](https://coinbin.org/dbix)
[storj](https://coinbin.org/storj)
[fun](https://coinbin.org/fun)
[eos](https://coinbin.org/eos)
[sls](https://coinbin.org/sls)
[mco](https://coinbin.org/mco)
[soar](https://coinbin.org/soar)
[swt](https://coinbin.org/swt)
[dbic](https://coinbin.org/dbic)
[dct](https://coinbin.org/dct)
[adt](https://coinbin.org/adt)
[sib](https://coinbin.org/sib)
[pay](https://coinbin.org/pay)
[draco](https://coinbin.org/draco)
[chc](https://coinbin.org/chc)
[mtl](https://coinbin.org/mtl)
[fair](https://coinbin.org/fair)
[uny](https://coinbin.org/uny)
[plu](https://coinbin.org/plu)
[daxx](https://coinbin.org/daxx)
[qtum](https://coinbin.org/qtum)
[san](https://coinbin.org/san)
[grs](https://coinbin.org/grs)
[ppt](https://coinbin.org/ppt)
[crw](https://coinbin.org/crw)
[wbb](https://coinbin.org/wbb)
[mue](https://coinbin.org/mue)
[safex](https://coinbin.org/safex)
[ter](https://coinbin.org/ter)
[omg](https://coinbin.org/omg)
[plbt](https://coinbin.org/plbt)
[net](https://coinbin.org/net)
[cvc](https://coinbin.org/cvc)
[xrl](https://coinbin.org/xrl)
[bdl](https://coinbin.org/bdl)
[b@](https://coinbin.org/b@)
[part](https://coinbin.org/part)
[coe](https://coinbin.org/coe)
[skin](https://coinbin.org/skin)
[plr](https://coinbin.org/plr)
[nvc](https://coinbin.org/nvc)
[etp](https://coinbin.org/etp)
[anc](https://coinbin.org/anc)
[bch](https://coinbin.org/bch)
[cmp](https://coinbin.org/cmp)
[mny](https://coinbin.org/mny)
[stx](https://coinbin.org/stx)
[ico](https://coinbin.org/ico)
[neo](https://coinbin.org/neo)
[dtb](https://coinbin.org/dtb)
[nlc2](https://coinbin.org/nlc2)
[gas](https://coinbin.org/gas)
[btm](https://coinbin.org/btm)
[bnb](https://coinbin.org/bnb)
[dnt](https://coinbin.org/dnt)
[bqx](https://coinbin.org/bqx)
[adx](https://coinbin.org/adx)
[lun](https://coinbin.org/lun)
[frst](https://coinbin.org/frst)
[tix](https://coinbin.org/tix)
[dent](https://coinbin.org/dent)
[snm](https://coinbin.org/snm)
[eb3](https://coinbin.org/eb3)
[zrx](https://coinbin.org/zrx)
[oax](https://coinbin.org/oax)
[ixt](https://coinbin.org/ixt)
[tcc](https://coinbin.org/tcc)
[cat](https://coinbin.org/cat)

----------------------------------


## Find this useful?

If you'd like to donate towards my efforts in the open source world, you can use the following wallet addresses, and any contributions (no matter how small) will be deeply appreciated.

- **[BTC](http://coinbin.org/btc)**: `1Me2iXTJ91FYZhrGvaGaRDCBtnZ4KdxCug`
- **[ETH](http://coinbin.org/eth)**: `0x1321Ec9c7550a7c44ef3e583930556c6557411d1`
- **[LTC](http://coinbin.org/ltc)**: `Lbyje2eiSMPfE1Ux6BYJuzN9CS7Nj78Hpu`
- **[LBC](http://coinbin.org/lbc)**: `bYDCRLb2Pcp1V25sRZs1LJkVnaddsNVCAQ`
- **[SC](http://coinbin.org/sc)**: `f23294ad70d2315f68a3265331508a44cd5363b8365f4ece91efd2365548b8f0760d34a8f884`

Or, [Say Thanks!](http://saythanks.io/to/kennethreitz)

✨🍰✨
