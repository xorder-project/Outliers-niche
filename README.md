

## Outliers' niche 另类生境 2019-1-7 第24期

#### X-Order 通证分析甜甜圈🍩 出品~😁😆😝 
定位 （每日5min)  ：outliers 的**playground**：站住并Buildl！🏄 


### 0.链上数据会说话

| btc | 数据 | 趋势|
|---:|:--:|:--|
| [Hashrate](https://www.blockchain.com/charts/hash-rate)| 3938 万 TH/s| 略降|
| [挖矿收入](https://www.blockchain.com/charts/miners-revenue) | 793 万美元 | 上升|
| [总转账费用](https://www.blockchain.com/charts/transaction-fees) | 17 BTC | 持平|
| [未确认交易数](https://www.blockchain.com/zh-cn/btc/unconfirmed-transactions) | 1.5 千笔 |持平|


|ETH | 数据 | 趋势|
|--:|:--:|:--:|
|[Hashrate](https://etherscan.io/chart/hashrate)| 187TH/s| 持平|
|[转账笔数](https://etherscan.io/chart/tx)|49万|下降|
|[总转账费用](https://etherscan.io/chart/transactionfee)| 300 eth| 略降|
|[未确认交易数](https://etherscan.io/chart/pendingtx)| 3.3万 | 下降|
|[gas 中位数](https://ethgasstation.info/)| 7.7 gwei | 上升 |
|[gas 费用(5分钟内可确认)](https://ethgasstation.info/)| 1 gwei | 下降|





### 1.核心项目进展
#### ETH:
- **PIN** [Constantinople 主链硬分叉会在 区块 #7080000, 估计时间在2019年1月**15**日](https://twitter.com/peter_szilagyi/status/1071052095535628288) 

- [Constantinople 硬分叉必须知道的](https://www.reddit.com/r/ethereum/comments/abv70c/heres_a_summary_of_the_constantinople_update/): 白驹过隙，eth马上就要硬分叉了，这篇reddit总结了这次君士坦丁堡硬分叉的升级内容，引入PoW+PoS混合共识机制,升级提案如下：
	- `EIP145`，提案人Alex Beregszaszi 和 Pawel Bylica，一种更有效的以太坊信息处理方案(逐位移动),让智能合约消耗更少的gas;
	- `EIP1052`，提案人以太坊core开发人员Nick Johnson和Bylica，使得智能合约间的验证更容易,优化以太坊网络大规模代码执行;
	- `EIP1014`,提案人Vitalik，增加了状态通道在ETH上;
	- `EIP1234`，提案人Parity的Afri Schoedon，使以太坊网络的区块奖励从3ETH减少到2ETH，此外还会延迟难度炸弹12个月的时间，使得ETH从`POW`平稳过渡到`POS`;
	- `EIP1283`提案日Johnson，引入了一种针对数据存储更改更公平的定价方法。

- [智能合约漏洞示例](https://smartcontractsecurity.github.io/SWC-registry/): 智能合约安全问题是最最重要的，ConsenSys这里有一个汇总，对于可能出现的问题都有示例，并且在这个[github](https://github.com/SmartContractSecurity/SWC-registry)上都可以贡献,一起来贡献吧！

- [项目进展: OpenZeppelin 正式发布2.1](https://github.com/OpenZeppelin/openzeppelin-solidity/releases): 这是 OpenZeppelin正式支持Solidity 0.5.0的开端，而且是不兼容之前版本的。同时增加了`WhitelistCrowdsale`,使得基于白名单的购买变得更容易，让`ERC20`和`ERC721`更有效，消耗更少的gas。

- [项目进展：ZKSNARKs Plasma部署测试网](https://ignis.thematter.io/#/login): 目前 [ZKSNARKs Plasma部署测试网并已经取得的500TPS的成绩](https://www.trustnodes.com/2019/01/06/zksnarks-plasma-eth-scaling-solution-of-500-tx-s-launched-on-testnet)，非常迅速，连Vitalik 也惊呼速度快👍，进展超出了🍩甜甜圈的想象呢！
	
- [状态通道项目总结](https://blog.coinfund.io/the-state-of-state-channels-2018-edition-f5492134ab96)：很明显，`EIP1014`的部署使得状态通道在ETH上变得越发紧要，那么有哪些状态通道的项目呢？这里为我们从普遍状态通道、状态通道网络、直接状态通道、支付通道网络和直接支付通道五个分类将目前所有涉及的项目做了一个归纳。涉及到众多项目，不止于以太坊上的项目，很有价值。

- [产业：ConsenSys和AMD创立W3DCloud](https://content.consensys.net/wp-content/uploads/W3BCLOUD-.pdf): ConsenSys 在2019年开始就努力将产业化作为重点，W3BCLOUD期望打造的是一个软硬件结合的独立云计算区块链基础设施，这次[合作](https://www.coindesk.com/ethereum-studio-consensys-teams-up-with-chip-manufacturer-amd)非常值得期待~

- [Awesome Layer2](https://github.com/Awesome-Layer-2/Awesome-Layer-2): layer2是大家都比较关注的，这里汇总了一些不同的layer2的项目，值得收藏。

#### EOS：

- **PIN最后一周**EOS 年度总结: [A growing ecosystem of users](https://twitter.com/block_one_/status/1075657757578018816): 这里有一幅完整的EOS生态的图，期望大家喜欢❤️

- [Block.one: 投票人回扣](https://medium.com/coinmonks/possible-improvements-to-eos-governance-7432b7afea1b): 这篇文章依旧在发酵，包括block.one的CEO [Brendan Blumer](https://twitter.com/BrendanBlumer)本人，对此也有更多的后续言论。核心观点是超级节点应该更多的给到投票人分红，并引入自由市场定价去生产区块，将更多价值带给代币持有人，并提高投票率。目前超级节点是不能正式给到投票人返利的，这个明显有贿选之意，但是Brandan Blumer给这个释放了口子，你如何看呢？

- [Fork链：beos 项目主网推迟](https://steemit.com/bitshares/@stan/beos-launch-delay): 这个项目是EOS的Fork，创始人是BM的爸爸: Stan Larimer。 期望能够链接BTS和EOS。由于这是完全的Fork，同时价值完全由BTS背书，所以能够实现BTS和EOS的跨链互换。最初主网期望再2019年2月上线，现在因为法务和开发的问题将推迟。

- EOS 治理: 今日无战事~

**甜甜圈🍩评论**：在年初，EOS的超级节点的活动和更新进入了真空，相比于以太上的日新月异的持续更新，EOS似乎进入了瓶颈？之前超级节点的成本问题，和EOS治理上的专治，都似乎使得EOS的超级节点的社区贡献在降低？或许只是新年的修整？我们期待EOS社区给我们更多的好的消息

### 2.热锅上的项目🔥 
- **Pin两期**:[Beam](https://www.beam.mw/): 上期的报告提到了Grin这个项目，我们提到Grin的时候就不得不提到Beam，因为他们都是利用mimblewimble这个特殊的共识机制来构建的一个项目。两者的区别是Beam的商业化倾向相对较明显，期望通过与机构合作，进行融资等方式来进行项目。而Grin的社区属性较强，不接受投资等。**特别提醒Beam 北京时间1月3日22:00。已经开始挖矿**
搜集了几篇文章，帮助大家更好的认识Beam这个项目。
	- [Grin vs. BEAM, a Comparison](https://tlu.tarilabs.com/protocols/grin-beam-comparison/MainReport.html)
	- [Beam Emission Schedule](https://medium.com/beam-mw/mimblewimble-emission-schedule-215551948259)
	- [Grin刷屏了，它的亲兄弟Beam为啥这么冷清？](https://mp.weixin.qq.com/s?__biz=MzA4MzE1MzQ3MA==&mid=2450141375&idx=2&sn=08d6b4f054ffc2570f0047c36402a009&chksm=880457eebf73def8ac9cf4208d7bdfddaf32ba496cf577d9854f005491333615c76ae4d7dd61&scene=0)

- [AVADO](https://ava.do/ )：最近ETH社区新出了一个很cool的硬件工具，很受程序员们喜爱，可以快速同步ETH全节点数据并且内置整合了[Dappnode](https://dappnode.io/)，Dappnode可以帮助用户整合所有不同链的全节点，BTC，XMR，DGD等等。避免了借用别人全节点的中心化问题，又可以自由的搭建测试自己的一些DAPP，价格有些小贵，不过还是很值得推荐的。:-D


### 3.Dapp跟踪

#### 游戏：
- **链上热点** [Cryptoflowers](https://cryptoflowers.io/): Cryptokitties 也已经上线一年多了，现在这类收藏类的NFT游戏会不会再次🔥呢？甜甜圈🍩认为这类游戏还是缺乏实用性。为什么我要养一个只能访问网页才能看到的🌹呢? 当年电子宠物出现的时候，可以使用一个被挂在钥匙圈上的可爱的“硬件”的，宠物是需要常常伴随的，如果按照这个逻辑，难道之后的智能音响能够拥有电子身份🆔并成为宠物？😄真的有可能~

#### [Loom](https://loom.games/) 专题
- [Zombie Battleground](https://loom.games/): 有小伙伴问🍩，为什么loom的项目不介绍呢？甜甜圈想了半天，发现因为这个 Zombie卡牌类的游戏是在让甜甜圈觉得恐怖😱。Anyway，还是需要介绍一下，实际上这款游戏是直接可以玩的，loom基于以太坊的plasma，目前虽然还没有能够部署到主链中，但是plasma相对可以独立，因此功能不受影响。然后就是这款游戏好玩吗？甜甜圈🍩问：“炉石好玩吗？” 本质是就是区块链上的炉石传说。Enjoy~

- [DelegateCall](https://delegatecall.com/): 这是loom的问答社区，上面都是loom的问题，不过目前非常不活跃。相比于Steemit，确实差了很多。


### 4.近期深度文章
- [硬核：为什么说 Layer 1+Layer 2 才是未来加密经济的基础设施](https://www.chainnews.com/articles/217921812340.htm)  偏技术的分析到了layer2的重要性。
- [比特币大区块实验之路](https://mp.weixin.qq.com/s/J2O4aPXPgSmB21B5f8MhEg) 回顾了比特币围绕着大区块这个主题的发展历史，感兴趣的小伙伴们可以了解一下。
- [Bitmex深度报告: 比特币的广泛运用是否会颠覆金融系统](https://blog.bitmex.com/thetimes/)： 这篇文章深度解释了目前银行系统如何发债并探索区块链如何拓展其中的"信用"。这篇文章认为可以通过避免存款来加速信贷周期运转。非常值得一读！



通证甜甜圈🍩, XOrder.ai 欢迎多提宝贵意见! [邮件](qchen@xorder.ai)
