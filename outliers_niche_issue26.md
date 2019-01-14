

## Outliers' niche 另类生境 2019-1-11 第26期

#### X-Order 通证分析甜甜圈🍩 出品~😁😆😝 
定位 （每日5min)  ：outliers 的**playground**：站住并Buildl！🏄 


### 0.链上数据会说话

| btc | 数据 | 趋势|
|---:|:--:|:--|
| [Hashrate](https://www.blockchain.com/charts/hash-rate)| 4581 万 TH/s| 上涨|
| [挖矿收入](https://www.blockchain.com/charts/miners-revenue) | 837 万美元 | 上涨|
| [总转账费用](https://www.blockchain.com/charts/transaction-fees) | 24 BTC | 持平|
| [未确认交易数](https://www.blockchain.com/zh-cn/btc/unconfirmed-transactions) | 8.5 千笔 |上涨明显|


|ETH | 数据 | 趋势|
|--:|:--:|:--:|
|[Hashrate](https://etherscan.io/chart/hashrate)| 186TH/s| 持平|
|[转账笔数](https://etherscan.io/chart/tx)|58万|上涨|
|[总转账费用](https://etherscan.io/chart/transactionfee)| 365 eth| 上升|
|[未确认交易数](https://etherscan.io/chart/pendingtx)| 3.4万 | 持平|
|[gas 中位数](https://ethgasstation.info/)| 6.3 gwei | 持平 |
|[gas 费用(5分钟内可确认)](https://ethgasstation.info/)| 1.2 gwei | 持平|





### 1.核心项目进展
#### ETH:
- **Pin一周** [Constantinople 硬分叉必须知道的](https://www.reddit.com/r/ethereum/comments/abv70c/heres_a_summary_of_the_constantinople_update/): 白驹过隙，eth马上就要硬分叉了，这篇reddit总结了这次君士坦丁堡硬分叉的升级内容，引入PoW+PoS混合共识机制,升级提案如下：
	- `EIP145`，提案人Alex Beregszaszi 和 Pawel Bylica，一种更有效的以太坊信息处理方案(逐位移动),让智能合约消耗更少的gas;
	- `EIP1052`，提案人以太坊core开发人员Nick Johnson和Bylica，使得智能合约间的验证更容易,优化以太坊网络大规模代码执行;
	- `EIP1014`,提案人Vitalik，增加了状态通道在ETH上;
	- `EIP1234`，提案人Parity的Afri Schoedon，使以太坊网络的区块奖励从3ETH减少到2ETH，此外还会延迟难度炸弹12个月的时间，使得ETH从`POW`平稳过渡到`POS`;
	- `EIP1283`提案日Johnson，引入了一种针对数据存储更改更公平的定价方法。

- [以太坊硬分叉进程](https://ethereum-magicians.org/t/eep-5-ethereum-hardfork-process-request-for-collaboration/2305): 由于社区驱动，任何人都可以驱动以太坊向着更好的方向发展，这个EEP-5就是期望能够对以太坊硬分叉进行持续跟踪，这里列举了以太坊的议事流程和硬分叉会发生的一系列事情的关键阶段：
	- 2019-01-16: Constantinople主链硬分叉
	- 2019-05-17: 是否接受“Istanbul”的最后期限
	- 2019-07-19: 主要客户端升级的期限
	- 2019-08-14: Ropsten, Görli 测试链硬分叉
	- 2019-10-16: Instanbul 主链硬分叉

- **KOL chemistry**:[Vitalik:期望将Constantinople硬分叉改名为升级](https://twitter.com/VitalikButerin/status/1083450179347394560)，Vitalik 一早twitter问给以太坊社区说Constantinople 硬分叉容易造成误解，不如参考Zcash社区，将这次名称改为 Constantinople 网络升级(Constantinople network upgrade),然后社区有完全赞同的，参考[zcash路线图](https://z.cash/blog/the-zcash-network-upgrade-pipeline/), 但是也有KOL站出来表示反对，总体的意思是我们是否需要为了避免社区小白的可能的误解来讲本来清楚的技术名词变得含糊不清，硬分叉和升级在技术上是明显可分的，就是升级一般可以向后兼容，而硬分叉则完全不想后兼容，包括Aragon的John Light在内持有这个观点：

> "it is totally orwellian（奥威尔式） to me. framing it as an upgrade is coercive. I've always hated that. if you have to ruin backwards compatibility, show your reasoning for it, don't sugarcoat the thing in euphemisms." -- @nic__carter  

- ConsenSys: [Joe Lubin: 下一个杀手级应用就是杀手级的生态系统](https://media.consensys.net/joe-lubin-the-next-killer-app-is-a-killer-ecosystem-1a5f789c82b4), ConsenSys的10号的这篇blog真实的表达了ConsenSys作为以太坊的核心，所期望为 Web 3.0做的所有努力。之前我们会说一个世界计算机，太宏伟，可是Ethereum真的在朝着这方向进发， 甜甜圈🍩为之打call💪

> Ethereum is emerging as one of the foundational components of a world computer — a web 3 flavored constellation of interoperating protocols. Web 3, the decentralized world wide web, will consist of many decentralized protocols: for trusted transactions, automated agreements, smart software objects, storage, bandwidth, heavy compute, identity, reputation, proof of location, legally enforceable agreements, certificates, resource and asset tokenization like kWh, equities, real estate, and more.  -- Joe Lubin

- [EIP1688: Improve feeds available from the EIPs website](https://github.com/ethereum/EIPs/issues/1688): 这个提案特别有趣，这是对于EIP呈现方式和工作流的一个改进。我们看到EOS目前以论坛的形式来提proposals，但是以太坊现在需要直接在github上提，同时提案被`jekyll`以静态页面的方式生成，当时这样查询到所有EIP提案的状态就变得比较困难，提案者bmann建议有一个全局的feed能够将EIPs和当下的状态全部呈现出来，甜甜圈🍩也是这样想的，点赞👍 



#### EOS：

- **PIN最后一周**EOS 年度总结: [A growing ecosystem of users](https://twitter.com/block_one_/status/1075657757578018816): 这里有一幅完整的EOS生态的图，期望大家喜欢❤️

- [Transit API: 为Dapp签名服务](https://medium.com/@boscorebos/as-an-active-eos-bp-how-does-eos-nation-see-bos-e2603d4e5194)：在EOS New York超级节点看来，用户体验是最重要的，同时Dapp是目前EOS最重要的优势，那么就要服务好用户，可是目前最大的问题是钱包体验特别不好，同时EOS的签名系统也有很多问题，所以EOS New York整合了钱包商，包括著名的Scatter、MeetOne、Ledger等，将API统一，这个工作非常重要，为EOS New York打call!💪

> User Experience is king. -- EOS New York

- Fork链:[BOS: 商业EOS](https://www.boscore.io/) 这个项目很特别，基本聚拢了这个EOS 中国生态的所有知名节点和项目，包括EOS Asia、引力区、MeetOne，同时目前宣布[1月17日主链上线](https://twitter.com/atticlab_it/status/1083391978446995457)，有趣的是这个项目主页并没有团队，反而主网上线是由[Atticlab](https://atticlab.net/)twitter发布的，Atticlab是一家技术公司，其中的关联值得调查。


- [EOS 治理: EOSIO.Fortum部署智能合约](https://eosauthority.com/approval/view?scope=eoscanadaops&name=deployforum&lnc=en): 对于EOSIO的论坛，需要不是一个智能合约，目前在投票阶段,几个核心超级节点都已经投出支持票，EOS Canada更在为之[宣传](https://twitter.com/EOS_Canada/status/1082642979863564288), 目前投票情况已经通过，我们就等候部署吧！ 


### 2.热锅上的项目🔥 
- **Pin**:[Grin](https://grin-tech.org/)&[Beam](https://www.beam.mw/): 利用mimblewimble共识机制的两个兄弟项目。两者的区别是Beam的商业化倾向相对较明显，期望通过与机构合作，进行融资等方式来进行项目。而Grin的社区属性较强，不接受投资等。**特别提醒Beam已经在北京时间1月3日主网上线，Grin将于1月15日，23:00 (11:00 PM)左右主网上线**
这是Curated list，帮助大家更好的认识Grin、Beam这个项目。
	- [Grin vs. BEAM, a Comparison](https://tlu.tarilabs.com/protocols/grin-beam-comparison/MainReport.html)
	- [通证通研究院：Grin 深度报告](https://www.chainnews.com/articles/182565597152.htm)
	- [Grin up 周报](https://www.chainnews.com/articles/049413235405.htm)

- [Codex](https://codex.one/): Codex，这个注册在爱沙尼亚🇪🇪的合规数字货币交易所，目前在针对[EOS CPU交易这块做了一些派发的推广](https://cryptoradar.org/codex-exchange-and-attic-lab-eos-bp-collaborated-for-eos-cpu-giveaway/)，中心化交易所直接切入CPU这块吸引了甜甜圈的眼球，同时🇪🇪也是甜甜圈很向往的一个自由国度，推荐小伙伴可以试试~ 
- [NUMERAI](https://numer.ai/homepage) Numerai是一个很神奇的项目，他针对数据科学家每周进行数据锦标赛，然后获胜者除了现金奖励还有他的代币NMR的奖励，然后科学家可以用NMR继续投入押注进行新一轮锦标赛。他确实实现了使得token分布在最直接使用它的人手中，值得借鉴。


### 3.Dapp跟踪:
很多甜甜圈🍩的关注者都觉得Dapp其实就是博彩和收藏类卡牌类游戏，这个甜甜圈在这里纠正一下，Dapp在甜甜圈看来是任何使用区块链技术的App应用。所以这个版块会推荐一些特别的新尝试，即使目前不🔥，只要有趣：

#### 社交

- [Alchemy.daostack](https://alchemy.daostack.io/): 大家是否厌倦了steemit这些不严肃的话题，期望对于一些真实的提案有交互，支持那些重要的有意义的提案？这个项目在甜甜圈🍩看来就是一个最好的尝试，使用这个提案系统，能够实现这一去中心化的提案系统，你可以stack那些具有价值的提案，同时你甚至可以在你stack的提案被获得通过的时候获得一些token奖励。在alpha阶段，试试看吧~
 

### 4.近期深度文章

- [STO 进展: STO需要被首先在监管平台上交易](https://www.coindesk.com/security-token-trades-on-regulated-platform-in-market-first): STO的期待在2018年一直持续，但是进展上走势很艰难，甜甜圈最近和一些投资人聊发现更多投资人最关心的问题还是流动性，如果STO不能提供充足的流动性，那么似乎和新三板就没有什么区别，也无法获得足够的收益回报。不过甜甜圈觉得STO中还有很多机会，现有的监管框架的融合并能够提供足够的流动性将成为重中之重。
- [监管：全球区块链监管框架已成](https://www.8btc.com/article/343831): 2019年是反思和buidl的一年，昨天[国家互联网信息办公室发布《区块链信息服务管理规定》](https://www.8btc.com/article/343803)小伙伴都意见注意到了，甜甜圈觉得对于合规，如果长远看一件事情是正确的，合规是必须做的~这篇文章为小伙伴梳理了全球合规最新的进展，推荐给小伙伴~
- [Bitcoin 网络转账费处于6年最低位](https://www.longhash.com/news/bitcoin-btc-transaction-fees-are-at-their-lowest-in-six-years): 如果要说加密货币的严冬，看看网络转账费就可以了，目前如果以最小单位`satoshi`计算,2019年1月1日才660，相当于0.02美金，确实很低很低。。。
- [区块链行业2018年度盘点](https://mp.weixin.qq.com/s/Z62iPugViRm-dsXCzvKu1g)：从数据的角度展示并总结了区块链行业18年的各类现象。

通证甜甜圈🍩, XOrder.ai 欢迎多提宝贵意见! [邮件](qchen@xorder.ai)
