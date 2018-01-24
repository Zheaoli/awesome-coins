# ₿ 加密货币工具和算法大合集

维基百科—
> [加密货币](https://en.m.wikipedia.org/wiki/Cryptocurrency)加密货币是一种利用密码学原理来保证账户之间交易的安全性并且控制货币发行量的数字资产。

现在市面上已经存在各种各样根据不同加密原理的加密货币。这篇文章中列举了那些主流加密货币的相关信息以及非常有用的工具。希望可以帮助到大家。

## 说在最开始

如果你是加密货币领域的新新人类，”货币”这个词可能会让你感到很困惑。所以我先给你们讲一下我目前理解的 -

现在已经存在很不同种类的[货币](http://coinbin.org/coins)。很多人都喜欢像交易股票和宝可梦卡片那样人们喜欢在这个平台上进行[货币交易](https://www.cryptopia.co.nz/Register?referrer=kennethreitz)。
也有人喜欢去用自己的个人电脑或着专业的矿机来[挖矿](https://www.nicehash.com/?refby=386829)。

加密货币存放在钱包里，可以是在线钱包、本地钱包甚至是记录在一张纸上。
独自挖矿是很困难的，这个过程跟赌博有点像，所以大家通常倾向于加入一个矿池。
(矿池通常运行 `stratum` 协议) —- 即使你没有挖到任何货币，也会收到奖励，因为你为那些挖到矿的人贡献了自己微博的算力。

之后这些挖到的块会按照协议的规则分成许多份。

除非你有非常多的算力可以用而且愿意为此花钱，你还可以[租借算力](https://www.nicehash.com/?refby=386829)，然后或者是用这些算力来玩一个"区块链彩票"的游戏, 尝试自己去挖矿, 或者就和家庭作坊式矿工一样将这些算力提供给矿池来换取奖励。

希望已经把事情都讲明白了。

## ☤ 货币市场高效工具

- **[Coinbin.org](http://coinbin.org)** — 用于快速获取货币数据（汇率，预测，，，）用户友好的API

    * [已知加密货币列表](http://coinbin.org/coins) `/coins`
    * [BTC 实时币值](http://coinbin.org/btc) `/btc`
    * [BTC 每日币值](http://coinbin.org/btc/history) `/btc/history`
    * [BTC / ETH 汇率](http://coinbin.org/btc/to/eth) `/btc/to/eth`
    * [20.01 BTC 价格](http://coinbin.org/btc/20.01) `/btc/20.01`
    * [42 ETH 价格（BTC）](http://coinbin.org/eth/42/to/btc) `/eth/42/to/btc`
    * 支持所有加密货币.
- [CoinMarketCap](https://coinmarketcap.com) — 所有加密货币实时Dashboard.
- [MoneyHash](https://moneyhash.today) — 根据可用的算力在货币市场计算出利润率。

## ☤ 阅读资源

- [加密货币概览](https://github.com/kilimchoi/cryptocurrency) — GitHub 仓库.
- [加密货币家谱图](http://mapofcoins.com) – 可视化查看从货币发布白皮书至今的发展历史
- [白皮书大合集](http://diyhpl.us/~bryan/papers2/bitcoin/)
- [精通比特币](https://github.com/bitcoinbook/bitcoinbook) (电子书)
- [比特币开发手册](https://bitcoin.org/en/developer-reference)
- [深入浅出区块链](https://github.com/anderson-joyle/blockchain-for-humans) — 最简单的区块链讲解文章
- [加密货币](https://www.reddit.com/r/CryptoCurrency/) — 加密货币和加密资产。

## ☤ 矿池

[挖什么](https://whattomine.com)的列表.

- **#**: [https://www.nicehash.com/](https://www.nicehash.com/?refby=386829) — 根据你的GPU自动进行最优配置 & 挖 **比特币（BTC）**.
- **BTC**: https://pool.bitcoin.com/
- **ETH**: https://eth.nanopool.org/
- **SC**: https://sia.nanopool.org/
- **PASC**: https://pasc.nanopool.org/
- **XMR**: https://xmr.nanopool.org/
- **ZEC**: https://zec.nanopool.org/
- **ETC**: https://etc.nanopool.org/


## ☤ 算力租借

- [NiceHash](https://www.nicehash.com/?refby=386829) — 支持所有的哈希算法, 根据使用量支付 **BTC** .
- [Bitcoin.com 矿池](https://pool.bitcoin.com/index_en.html) — 听说这里有一些有意思的事.
- [BitMain Hosted](https://bitmainwarranty.com/product-category/hosting/) — 网站看起来乱七八糟的，但是他们提供ASIC解决方案。

## ☤ 钱包

### 托管钱包

**注意:** 社区并不喜欢这样的服务, 因为你其实并不真正的拥有你的货币 — 事实上, 这些钱也根本不是你的 — 这种服务的方式有点像银行。

- [Coinbase **BTC**](https://www.coinbase.com/join/516f7e9a929bda3e06000001)
- [Coinbase **ETH**](https://www.coinbase.com/join/516f7e9a929bda3e06000001)
- [Coinbase **LTC**](https://www.coinbase.com/join/516f7e9a929bda3e06000001)

真正的本地钱包:

- [MyEtherWallet **ETH**](https://www.myetherwallet.com/)
- [Dogechain **DOGE**](https://my.dogechain.info/#/wallet)
- [Gamecredits **GAME**](https://wallet.gamecredits.com/dashboard/myWallet)

### 加密货币借记卡

- [Cryptopay **BTC** Debit Card](https://cryptopay.me/join/03db9c17)

### 硬件钱包

- [**Sia** 纸质钱包](https://siapaperwallet.co)
- [Cryptosteel](https://cryptosteel.com) — 金属材质！

## ☤ 交易所

- [Cryptopia](https://www.cryptopia.co.nz/Register?referrer=kennethreitz) — 提供所有币种的钱包，支持所有类型的交易。
- [Shapeshift](https://shapeshift.io/#/coins) — 地表最快交易所
- [Bittrex](https://bittrex.com) — 提供所有币种的钱包，支持所有类型的交易。
- [Qvolta](https://qvolta.com) — 使用本地的交易渠道买/卖加密货币。
- [Coinwale](https://coinwale.com) - 匿名加密货币交易所。


## ☤ 跨平台界面应用

- [**Sia** 界面](http://sia.tech/apps/) — SC 钱包, 文件托管, 存储
- [**LBRY**](https://lbry.io) — LBRY 钱包, 信息交换平台.

## ☤ Windows 界面应用

- [NiceHash Miner](https://miner.nicehash.com/?refby=386829) — 这里你可以出售你的 GPU/CPU 算力给矿工获利! 根据你的硬件自动进行最优配置(可调整).

[![](https://miner.nicehash.com/images/landing-pages/nhm/nhm2.svg)](https://miner.nicehash.com/?refby=386829)
- [MinerGate](https://minergate.com) - 挖最赚钱的币。

## ☤ MacOS 界面应用

- [MacMiner](http://macminer.fabulouspanda.com/macminer/) — 应用里有 bfgminer, cgminer和sgminer.

## ☤ MacOS 终端应用

- [bfgminer](http://macminer.fabulouspanda.com/commandline/) — 用C写的模块化ASIC/FPGA 终端工具, 提供超频、实时监控、风扇转速控制和远程接口等功能。
- [cgminer](http://macminer.fabulouspanda.com/commandline/) — C语言写的用ASIC和FPGA挖比特币的挖矿工具。
- [sgminer](http://macminer.fabulouspanda.com/commandline/) — Scrypt 显卡挖矿工具.
- [nheqminer](https://github.com/kozyilmaz/nheqminer-macos) — Equihash CPU & GPU 挖矿工具.

## ☤ 推荐硬件

- [NVidia GTX 1080 TI OC](http://amzn.to/2wl1c9j) — 消费级地表最强显卡。
- [Asrock H110 Pro BTC+ 挖矿母版](http://amzn.to/2xadkYk) — 至少能插12个PCI-E显卡.

## ☤ 趣味 加密货币/区块链

- [Bit](https://github.com/ofek/bit) — Python最快的比特币工具库，3行代码实现转账。
- [bcoin](http://bcoin.io) — 纯Node.js实现的全链路比特币，可以在浏览器中运行，有钱包，内存池，区块链和挖矿工具。
- [**BTC** Mempol and Fee Explorer](https://core.jochen-hoenicke.de/queue/#4d)
- [Tezos](https://www.tezos.com) — 自愈区块链。
- [Tendermint](https://tendermint.com) — 任何语言下的拜占庭容错复制状态机(Replicated State Machine)。
- [Cosmos](https://cosmos.network) — 区块链网络和交互框架。
- [URI scheme for Blockchain exploration](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2015-August/010712.html)
- [Blockply](https://blockply.com/) — 有趣又有料的区块链项目合集
- [Blockchain demo](https://github.com/anders94/blockchain-demo) — 区块链概念网页演示。
- [Silly Gamble](https://www.sillygamble.com) — 公开公平公正的区块链小游戏。

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

## ☤ 所有还活跃的加密货币项目

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


## 这篇文章帮助到你了么?

如果您发现这篇文章对您有帮助, 希望您可以通过下面的钱包地址进行捐助, 无论多少我都会很感谢.

- **[BTC](http://coinbin.org/btc)**: `1Me2iXTJ91FYZhrGvaGaRDCBtnZ4KdxCug`
- **[ETH](http://coinbin.org/eth)**: `0x1321Ec9c7550a7c44ef3e583930556c6557411d1`
- **[LTC](http://coinbin.org/ltc)**: `Lbyje2eiSMPfE1Ux6BYJuzN9CS7Nj78Hpu`
- **[LBC](http://coinbin.org/lbc)**: `bYDCRLb2Pcp1V25sRZs1LJkVnaddsNVCAQ`
- **[SC](http://coinbin.org/sc)**: `f23294ad70d2315f68a3265331508a44cd5363b8365f4ece91efd2365548b8f0760d34a8f884`

或者, [表达感谢!](http://saythanks.io/to/kennethreitz)

✨🍰✨
