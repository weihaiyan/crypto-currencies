Litecoin(LTC莱特币)-与比特币的对比分析
=====

![litecoin-logo](../logo/litecoin-logo.png)

概述
-----
* 莱特币是一种点对点的电子加密货币，莱特币受到了比特币（BTC）的启发，并且在技术上具有相同的实现原理，莱特币的创造和转让基于一种开源的加密协议，不受到任何中央机构的管理。莱特币旨在改进比特币，与比特币相比，莱特币具有三种显著差异。第一，莱特币网络大约每2.5分钟（而不是10分钟）就可以处理一个块，因此可以提供更快的交易确认。第二，莱特币网络预期产出8400万个莱特币，是比特币网络发行货币量的四倍之多。第三，莱特币在其工作量证明算法中使用了由Colin Percival首次提出的scrypt加密算法，这使得相比于比特币，在普通计算机上进行莱特币挖掘更为容易。


基本信息(2017/5/30)
----
* 发行日期：2011-10-07
* 市值排名：6
* 交易量前三大交易平台：okcoin／火币／	xBTCe
* 官网：[https://litecoin.org/](https://litecoin.org/)
* 钱包下载：[https://litecoin.org/](https://litecoin.org/)
* 区块链浏览器：[http://qukuai.com/ltc](http://qukuai.com/ltc)

市场关注度(2017/5/30)
-----
* 推特：7702
* github：1329
* reddit：29081
* 官网全球排名：96659

创立
-----
* CharlieLee(李启威)：LTC创始人,亚裔美国人，1999年毕业于麻省理工大学，拥有学士和硕士学位，专业是电气工程和计算机科学。2011年，有一些山寨币开始出现，比如IXCoin等等，而查尔斯在当时也推出了一个纯属复制的山寨币，称之为Fairbrix。Fairbrix是一个几乎完全复制Tenebrix(另一个币)的山寨币。这个山寨币刚发布不久便遭受了51%网络攻击，运行网络因此崩溃。（51%攻击是一个新电子货币很难绕过去的一道坎，由于发布初期矿工数量非常少，因此攻击者只需要很低的成本就能够完成51%攻击）（51%攻击是指，当一个挖矿者拥有的算力，达到这个币所有算力的51%，就能够伪造或破坏整个币的运行网络，而使之崩溃，很多电子货币都遭受过51%攻击）；一个月后，查尔斯再次推出了一个全新的电子货币，叫做LiteCoin。


项目进展
-----
* 最近更新：2017/1/11更新至0.13.2版本；该版本基于Bitcoin Core 0.13.2，它带来了激活“segwit”功能的选项，这是通过删除某些非必要数据来将更多交易合并到块中的一种方法。

* 2017年莱特币路线图:

 Litecoin Core: 开发员: shaolinfry, thrasher-;发行0.13.3
同步至Bitcoin Core 0.14.1版本,BIP173：Bech32地址，专为Segregated Witness而设，更安全的地址格式

 “M”地址:开发员: coblee, wangxinxi,把莱特币的P2SH地址从3改为M开头,协助各程序库升级至新地址,鼓励钱包和交易所改用新地址

 安卓钱包:开发员: electo;重新发布安卓钱包

 LoafWallet:开发员: losh11, mlpfrank;支援通过Coinbase Buy Widget购买莱特币,新使用者介面,新的使用教程,安卓钱包- LoafWallet Core C程序库

 Electrum-LTC:开发员: pooler;发布2.8.3.2

 Litecore/Insight:开发员: losh11, coblee, ultragtx；与Litecore及Insight区块浏览器支援隔离见证，改善在线率，以更好服务其它产品

 闪电网络：开发员: coblee, ultragtx, wangxinxi；与闪电网络开发员一同在莱特币上建设闪电网络的基础，建立莱特币与Vertcoin之间的跨链交换
 
 智能数字金：开发员: jl2012；加入MAST,Covenants,及重启一些原有的脚本OP命令，实现智能合约，并容许指定输出地址以提高安全性

 Litecoin.Network：开发员: losh11, mlpfrank, rjmacarthy；Litecoin.network是一个即将发布的项目。它将会被用来跟踪莱特币网络的状况，并把这些信息整合放在一个地方便于浏览。该网站也会跟踪莱特币开发状况，莱特币网络经济状况，挖矿，mempool大小等信息。我们也会提供API以及CSV文件让用户便捷地获取这些历史数据。

 莱特币基金会：
常务董事: 李启威

 董事: 李启威, 王新喜, Franklyn Richards

 社区顾问: 郭宏才

 开发员: losh11, fancycedar

 通过接受捐款 (https://litecoin-foundation.org/donation/)及售卖莱特币品牌的Ledger Nano S硬件钱包及衣服，以支付开发员，保证财务的透明度，聘用全职的Litecoin Core开发员，为莱特币开发提供基础设施包括Github/DigitalOcean/Slack/电邮服务

 重建莱特币网页：开发员: losh11, mlpfrank；Litecoin.com: 介面重建，Litecoin.org: 修复连结并改善设计

 未来的发展：Schnorr签署，机密交易(Confidential Transactions)，扩容研究


BTC与LTC的比较
-----
* 证明方式：比特币使用SHA256散列函数，因此比特币挖掘是一个令人尴尬的任务。Litecoin使用scrypt而不是SHA256作为工作证明。scrypt哈希函数使用SHA256作为子例程，但也取决于对大量内存的快速访问，而不仅仅依赖于快速算术运算，因此使用显卡并行运行多个scrypt实例更为困难。这也意味着专用scrypt硬件（ASIC）的制造成本将比SHA256 ASIC显着更昂贵。由于现代GPU具有大量的RAM，因此它们对于Litecoin采矿是有用的，普通的计算机就可以进行挖矿，而比特币需要专用的挖矿机或超级计算机。


* 区块生成时间：BTC每10min生成一个块，LTC每2.5min生成一个块。对于大多数人而言都希望自己的交易能尽快确认，这方面莱特币具有优势。
 
* 难度调整：比特币和莱特币都是每2016个区块进行难度调整，但是因为莱特币的出块速度比比特币快4被，所以莱特币的难度调整周期约为4天。

* 发行量：比特币2100万，莱特币8400万。
 
最新消息（2017/5）
--------
* 莱特币成功激活隔离见证，并且经过升级的版本已经完成了第一笔交易。一些莱特币用户已经进行了一场投票，选出他们最想要添加到莱特币网络的技术/功能，结果就是用于实现即时可扩展的链下交易的闪电网络勇夺桂冠（77%的选票）。其余的选项分别是以太坊智能合约MAST（4%的人投票），保密交易功能（15%的人投票）和实现链上扩容的Schnorr（4%的人投票）。
* 自隔离见证在网络激活之后，莱特币网络上已经现实演示了一些闪电网络交易。并且交易几乎是瞬间完成的。现在最困难的部分是让用户看到交易的速度，以鼓励大量采用。在比特币找到扩容解决方案之前，莱特币可以借机聚集数以百万计的客户和商家。

 根据莱特币创始人Charlie Lee所说，一些闪电网络实施如今已经可用——尽管大多数已经在莱特币上进行了测试，不过为了客户体验感更佳，这些项目仍然需要进行更多准备——包括Amiko支付、区块链雷霆网络、ACING的éclair技术、Blockstream的闪电网络 、MIT 多媒体实验室的闪电网络软件lit 以及闪电网络实验室的软件lnd。
 
* Coinbase钱包正式支持了数字货币莱特币，而在此前，Coinbase的数字资产交易所GDAX也支持了莱特币交易。

  

 

**关于币种分析文章，请关注小密圈ID：61818889，小密圈将作为第一发布平台，也可添加微信 liqi_studio 进群交流。**

