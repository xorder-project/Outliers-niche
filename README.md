

## Outliers' niche 另类生境 2019-1-18 第29期

#### X-Order 通证分析甜甜圈🍩 出品~😁😆😝 
定位 （每日5min)  ：outliers 的**playground**：站住并Buildl！🏄 


### 0.链上数据会说话

| btc | 数据 | 趋势|
|---:|:--:|:--|
| [Hashrate](https://www.blockchain.com/charts/hash-rate)| 3715(<-3861) 万 TH/s| 略降|
| [挖矿收入](https://www.blockchain.com/charts/miners-revenue) | 583(<-611) 万美元 | 下降|
| [总转账费用](https://www.blockchain.com/charts/transaction-fees) | 23(<-21) BTC | 上升|
| [未确认交易数](https://www.blockchain.com/zh-cn/btc/unconfirmed-transactions) | 3.8(<-3.5) 千笔 |略升|


|ETH | 数据 | 趋势|
|--:|:--:|:--:|
|[Hashrate](https://etherscan.io/chart/hashrate)| 178(<-189)TH/s| 下降|
|[转账笔数](https://etherscan.io/chart/tx)|52(<-54)万|略降|
|[总转账费用](https://etherscan.io/chart/transactionfee)| 330(<-423) eth| 下降|
|[未确认交易数](https://etherscan.io/chart/pendingtx)| 3.7(<-3.7)万 | 持平|
|[gas 中位数](https://ethgasstation.info/)| 8(<-10) gwei | 下降 |
|[gas 费用(5分钟内可确认)](https://ethgasstation.info/)| 1.3(<-5.1) gwei | 下降|





### 1.核心项目进展
#### ETH: 等候升级重新开启，反思！
- **Pin** [安全警告！Constantinople 升级推迟](https://blog.ethereum.org/2019/01/15/security-alert-ethereum-constantinople-postponement/), ETH的升级遇到了问题，为了方便小伙伴仔细阅读，这里有[中文翻译公告](https://ethfans.org/posts/security-alert-ethereum-constantinople-postponement), 甜甜圈感谢以太坊爱好者的连夜翻译。这次的问题根源在于ChainSecurity发现的EIP-1283的[可重入攻击的疑点](https://medium.com/chainsecurity/constantinople-enables-new-reentrancy-attack-ace4088297d9), 被[Mhswende](https://twitter.com/mhswende/)郑重提出，基金会经过理解讨论发现这个问题的严重性然后决定推迟。


- 升级带来的改变：
	- `EIP145`，提案人Alex Beregszaszi 和 Pawel Bylica，一种更有效的以太坊信息处理方案(逐位移动),让智能合约消耗更少的gas;
	- `EIP1052`，提案人以太坊core开发人员Nick Johnson和Bylica，使得智能合约间的验证更容易,优化以太坊网络大规模代码执行;
	- `EIP1014`,提案人Vitalik，增加了状态通道在ETH上;
	- `EIP1234`，The Thirdening, 提案人Parity的Afri Schoedon，使以太坊网络的区块奖励从3ETH减少到2ETH，此外还会延迟难度炸弹12个月的时间，使得ETH从`POW`平稳过渡到`POS`，这里有ConsenSys刚刚做的[视频解释](https://www.youtube.com/watch?v=-k2oktHQ7cs&feature=youtu.be);
	- `EIP1283`提案日Johnson，引入了一种针对数据存储更改更公平的定价方法。

- [ETH2.0: 我们能够期待什么？一个工程师对于ETH2.0的导语](https://hackernoon.com/what-to-expect-when-eths-expecting-80cb4951afcd): Vitalik的twitter对于升级推迟并没有发言，反而刚刚推荐了一篇关于ETH2.0工程师应该做什么的博客。作者是[summa](https://summa.one/)的创始人James，并非以太坊核心成员。这篇文章相对客观的讲了目前以太坊的各种升级技术方案和可能的问题。对于`beacon chain`,会创造出一种新的Ether，被称为`BETH`。BETH在开始将被不能转账直到第二阶段sharding完成。同时关于sharding和beacon chain之间的通信问题也一直没有被解决。因为智能合约是在beacon chain之后被安置的，所以也可能会出现一些改变。作为工程师的小伙伴，确实需要持续关注ETH的升级，因为这似乎不单单是一个底层的升级，也会影响到很多上层的工作。


- [通证经济：对于自由派激进主义的实验](https://medium.com/gitcoin/experiments-with-liberal-radicalism-ad68e02efd4): 经济学在甜甜圈🍩看来就是分配的科学，而Vitalik本人在2018年9月的时候发布过一篇文章[Liberal Radicalism: A Flexible Design For Philanthropic Matching Funds](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3243656), 提出了Capital-constrained Liberal Radicalism (‘CLR’)。 而Gitcoin则是甜甜圈🍩最痴迷的一个项目，正好发布了Gitcoin Grants项目，期望资助真正有贡献的项目，那么如何做呢？CLR正好派上了用处。简单讲，第一匹配，就是如果有人支持这个项目，基金就匹配支持一下，第二就量上，资助那些有多笔小额资助的项目大于那些由一个人大额支持过的项目，通过一种“Quadratic Voting"的方式。

> The mechanism provides much greater funding to many small contributions than to a few large ones. -- Vitalik



#### EOS：公投2.0进展

- **公投2.0**：这是甜甜圈取的名字😄，EOS社区目前推进这一项[EOS BallotCraft Working Group](https://medium.com/@espin.brand/eos-ballotcraft-guide-published-5eddab9d8cf3)计划，为了自组织管理，我们需要一个很有效的提案和协商系统。这个计划就是为了创造一种流程，能够使得自组织决议变得容易。🍩期待~ 

- [EOS New York 对于公投的入门指导](https://medium.com/eos-new-york/vote-thoughtfully-vote-eos-dcbe009fc727): 甜甜圈🍩看来，要推动群体做一件事情，所花的力量是推动同等数量的自己做这件事情的平方倍，甚至更多，所以以一种最简单的一步一步指导的方式是最可行的。而做这类事情确实需要耐心。感谢New York给我们带来了这个指导。
	- 第一步: 登录并寻找一个提案；直接通过 [bloks](https://bloks.io/vote/referendums)完成
	- 第二步：提交"赞同"或者"反对"投票，注意，投票需要的430bytes的RAM并不会消耗，而是在投票结束后的72小时会退回；
	- 可选：第三步：修改投票，直接进入"我的投票"可以我投票的所有信息，同时可以通过"修改投票”来修改；
	- 第四步：创建新的提案！ **甜甜圈🍩**:甜甜圈觉得这个很赞！任何人都可以提交提案，太棒了！不过创建新的提案是否需要费用？免费！好不好？看看下面的公投提案：

- [EOS 公投提案：公投提案发布是否要免费？](https://eosauthority.com/polls_details?proposal=pollpropcost_20190115&lnc=en): 这个新提案正是甜甜圈🍩考虑的。如果设置提案是免费的，那么是否会造成提案泛滥最后没有人投票呢？哈哈~这是一个好问题，解决之道是：公投本身！这个提案就是为了解决这个问题而来的！你有想法？参与公投吧！发现EOS社区这个公投非常认真😄。期望小伙伴多多探索~
 

- [一个维持EOS自发供应的EOS Worker Proposal Fund的方法](https://medium.com/eos-new-york/a-voluntaristic-approach-to-the-eos-worker-proposal-fund-1b2a94dad20b): 参考Monero的资助项目论坛，EOS New York觉得，如果整个EOS项目都只能又Block.one来资助，那么群众的自发性就会没有了，因此尝试设立一个`eosio.bounty`的账户,自发可以往这打资金，来支持EOS Worker Proposal。 甜甜圈看来，这是一个非常好的尝试👍





### 2.热锅上的项目🔥 
- **Pin**:[Grin正式上主链！！💐](https://grin-tech.org/)&[Beam](https://www.beam.mw/): 利用mimblewimble共识机制的两个兄弟项目。经过一番调试，Grin第一个区块已于北京时间00:01被鱼池挖出。**特别提醒Beam已经在北京时间1月3日主网上线，Grin也在1月15日主网上线**
	- [数据说话](https://grinmint.com/pages/index.html)：用户: 1583(<-1277 up！); 矿工 4096(<-3479 up!); Hashrate: 波动剧烈( Primary 103(<-52 up!), Secondary 55375 G/s(<-44519 G/s)  
		- 出块情况查询：[grinscan](http://grinscan.net)，[grinmint](https://grinmint.com/)
	- **Curated list**，帮助大家更好的认识Grin、Beam这个项目: 
	- [BitcoinTalk 支持Grin！](https://bitcointalk.org/index.php?topic=5098450.0)：简直太赞了😄
	- [Grin vs. BEAM, a Comparison](https://tlu.tarilabs.com/protocols/grin-beam-comparison/MainReport.html)
	- [通证通研究院：Grin 深度报告](https://www.chainnews.com/articles/182565597152.htm)
	- [Grin up 周报更新](https://grinnews.substack.com/)
	- [Tokengazer: Grin挖矿设备投资收益分析报告](http://www.tokengazer.com/#/reportDetail?id=64)
	- [让人兴奋的 Grin 如何走到今天？谁在背后推动它？](https://mp.weixin.qq.com/s/1OCmswCxaoo-2BHGEU5KrQ)
	- [卖掉grin，抛弃Beam](https://www.shenliancaijing.com/portal/activity/activedetail.html?id=4366) 

- [BitTorrent](https://www.bittorrent.com/): binance launchpad准备上BTT这个消息甜甜圈早就告诉大家了，现在binance研究院发布了[BitTorrent的评价报告](https://info.binance.com/en/research/BTT-2019-1-17.html),甜甜圈就在这里为大家解读项目通证经济价值**不包括TokenSale方面甜甜圈不负责**。 
	- 主要活跃信息媒介：[BitTorrent twitter](https://twitter.com/BitTorrent),解读项目，活跃第一手真实信息源最重要，官网更新毕竟是慢的，对于BTT，twitter最快最准确！
	- BitTorrent目的：“BTT为第三方app开发者提供去中心的基础设施平台，并让消费者能够持续为这个平台提供多余的算力”。简单理解就是打造一个基于BitTorrent的平台。 
	- 通证性质：`TRC-10 compatibility` ，基于[TRC10](https://developers.tron.network/docs/trc10-token),这里要明确TRC10是TRC的主网原生通证，不是基于`Tron Virtual Machine(TVM)`的智能合约通证。
	- 通证用途：开始作为BitTorrent软件中购买带宽的内置流通货币，之后会扩展为购买内容、打赏、众筹等功能。
	- 团队：CEO [孙宇晨](https://twitter.com/justinsuntron)；孙宇晨本人就是BitTorrent的CEO，这点非常特别，在孙的twitter和linkedIn上都有证实。同时核心产品是由[Justin F. Knoll](https://www.linkedin.com/in/knolljustin/#experience-section)担任的。 
	- 市场份额和竞品：BitTorrent 22%的全球上传流量和3%的全球下载流量，主导地位

**甜甜圈评论**：这个项目可以看到孙宇晨打造**娱乐帝国**的野心。BTT作为TRON上的原生通证，可扩展性很强，同时基于BitTorrent的现有系统，直接改造成为一个真正意义上的Dapp帝国，甜甜圈觉得架构得很好。


### 3.Dapp跟踪: 聚集黑客羊毛党
- [羊毛党调查](https://www.8btc.com/article/347999): 黑客及羊毛党（或者叫Dapp矿工），这是Dapp项目最害怕的，但是确实没有好的解决方案，看看这篇分析报道，以理解黑客的一些行为。


### 4.近期深度文章
- **Pin一周** [为 2019 年的密码世界划重点](https://mp.weixin.qq.com/s/300o6WLxB5kUVFBM9w238g): 作者对区块链2019年的**十大预测**，涵盖63个点：比特币6项、以太坊8项、其他项目13项、一级市场项目5项、稳定币4项、区块链基金4项、区块链产品5项、区块链公司13项、政策监管5项。
- [Messari 大佬给的2019年致富代码](https://mp.weixin.qq.com/s/EgiHB22jXSe_frFezH_RhQ)：Messari一直是甜甜圈比较关注的项目，他们的工具可用性也非常强。本篇是其创始人对于2019年区块链行业的96个预判中部分摘录，英语功底好的小伙伴可以读下[原文](https://medium.com/@twobitidiot/96-theses-for-crypto-in-2019-1498fe1a14e)。
- [欧洲区块链行业发展研究](https://mp.weixin.qq.com/s/UGrjdmlmEtpL5tWiiO0i5Q): 详述了欧洲当下的区块链发展状况，主要从监管政策还有宏观上分析了各个欧洲的区块链项目。



通证甜甜圈🍩, XOrder.ai 欢迎多提宝贵意见! [邮件](qchen@xorder.ai)
