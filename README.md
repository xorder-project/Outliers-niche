

## Outliers' niche 另类生境 2019-1-14 第27期

#### X-Order 通证分析甜甜圈🍩 出品~😁😆😝 
定位 （每日5min)  ：outliers 的**playground**：站住并Buildl！🏄 


### 0.链上数据会说话

| btc | 数据 | 趋势|
|---:|:--:|:--|
| [Hashrate](https://www.blockchain.com/charts/hash-rate)| 3826 万 TH/s| 下降|
| [挖矿收入](https://www.blockchain.com/charts/miners-revenue) | 635 万美元 | 下降|
| [总转账费用](https://www.blockchain.com/charts/transaction-fees) | 14 BTC | 下降|
| [未确认交易数](https://www.blockchain.com/zh-cn/btc/unconfirmed-transactions) | 2.0 千笔 |下降|


|ETH | 数据 | 趋势|
|--:|:--:|:--:|
|[Hashrate](https://etherscan.io/chart/hashrate)| 183TH/s| 持平|
|[转账笔数](https://etherscan.io/chart/tx)|48万|下跌|
|[总转账费用](https://etherscan.io/chart/transactionfee)| 266 eth| 下降|
|[未确认交易数](https://etherscan.io/chart/pendingtx)| 3.4万 | 持平|
|[gas 中位数](https://ethgasstation.info/)| 10 gwei | 大幅增加 |
|[gas 费用(5分钟内可确认)](https://ethgasstation.info/)| 8.2 gwei | 大幅增加|





### 1.核心项目进展
#### ETH: 聚集升级
- **Pin一周** [Constantinople 升级官网公告](https://blog.ethereum.org/2019/01/11/ethereum-constantinople-upgrade-announcement/), ETH马上就要硬分叉啦，这是官网的报道，甜甜圈特别建议大家直接阅读一手资料，以保障收到的信息的真实性。**block number 7,080,000**，估计在1月16日，社区也越发激烈地讨论起来，包括甜甜圈🍩发现，这次公告使用**Upgrade**,并没有使用**Hardfork**。讨论可以参考上一期（第26期），甜甜圈认为这次社区开始小心翼翼了，社区的信心在经受市场严重的考验，同时要防备可能的分叉

- **升级!** 测试网Rinkeby完成切换，以太坊客户端陆续升级: 甜甜圈🍩也正好借此机会为大家梳理一下ETH客户端。
	- [Geth 客户端最新](https://github.com/ethereum/go-ethereum/releases/tag/v1.8.20): 维护者 Péter Szilágyi，最早发布客户端的升级，目前测试网[Rinkeby 已经完成升级](https://www.rinkeby.io/#stats)。不过确实测试网大部分地址没有完全升级。 
	- [Parity 客户端最新](https://github.com/paritytech/parity-ethereum/releases/tag/v2.1.11): 维护者 [Afri Schoedon](https://twitter.com/5chdn), 完成客户端升级，同时[Afri统计了这次升级的情况，已经有44%的客户端完成了升级](https://twitter.com/5chdn/status/1084154870591090689), Parity用户在切换上已经达到了73%，Good Job👍
	- [EthereumJ Harmony 客户端最新版](https://github.com/ether-camp/ethereum-harmony/releases/tag/v2.3b72): 这是以太坊 Java客户端，维护者zilm13，用的人不太多，不过持续在更新。
	- [Pantheon 客户端最新版](https://github.com/PegaSysEng/pantheon/releases/tag/0.8.3)：这是ConsenSys企业项目PegaSys的Java 客户端，维护者[Lucas Saldanha](https://www.lucassaldanha.com/), 主要为企业级客户服务。
	- [Trinity 客户端最新版](https://github.com/ethereum/py-evm/releases/tag/trinity-v0.1.0-alpha.20): 这是以太坊python客户端。维护者[Jason Carver](https://twitter.com/jasoncarver)，属于以太坊基金会，目前项目依旧在v0.1，项目还需努力推进！
	- [Mist 客户端最新版](https://github.com/ethereum/mist/releases/tag/v0.11.1): 这是著名的Mist，Mist维护者是 [Ev](https://twitter.com/evertonfraga), 目前版本是2018年7月发布的，确实项目推进非常缓慢，这个项目可以之前众人最期待的项目，但是为什么推进缓慢呢？或许在憋大招？:-D
	- [Metamask](https://twitter.com/metamask_io/status/1084126800634994688): Metamask 需要升级吗？需要做什么吗？不需要！ 

- 升级带来的改变：
	- `EIP145`，提案人Alex Beregszaszi 和 Pawel Bylica，一种更有效的以太坊信息处理方案(逐位移动),让智能合约消耗更少的gas;
	- `EIP1052`，提案人以太坊core开发人员Nick Johnson和Bylica，使得智能合约间的验证更容易,优化以太坊网络大规模代码执行;
	- `EIP1014`,提案人Vitalik，增加了状态通道在ETH上;
	- `EIP1234`，The Thirdening, 提案人Parity的Afri Schoedon，使以太坊网络的区块奖励从3ETH减少到2ETH，此外还会延迟难度炸弹12个月的时间，使得ETH从`POW`平稳过渡到`POS`，这里有ConsenSys刚刚做的[视频解释](https://www.youtube.com/watch?v=-k2oktHQ7cs&feature=youtu.be);
	- `EIP1283`提案日Johnson，引入了一种针对数据存储更改更公平的定价方法。

- [以太坊硬分叉进程](https://ethereum-magicians.org/t/eep-5-ethereum-hardfork-process-request-for-collaboration/2305): 由于社区驱动，任何人都可以驱动以太坊向着更好的方向发展，这个EEP-5就是期望能够对以太坊硬分叉进行持续跟踪，这里列举了以太坊的议事流程和硬分叉会发生的一系列事情的关键阶段：
	- 2019-01-16: Constantinople主链硬分叉
	- 2019-05-17: 是否接受“Istanbul”的最后期限
	- 2019-07-19: 主要客户端升级的期限
	- 2019-08-14: Ropsten, Görli 测试链硬分叉
	- 2019-10-16: Instanbul 主链硬分叉

- [在硬分叉和骗局之间](https://decryptmedia.com/4387/ethereum-nowa-scam-causes):  [Ethereum Nowda](https://twitter.com/EliseWatoson/status/1080672622105391105?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed&ref_url=https%3A%2F%2Fdecryptmedia.com%2F4387%2Fethereum-nowa-scam-causes), 号称在1月12日进行分叉, 并能够1:1 获得空投。但是官网会引导你去一个在线钱包，输入私钥，然后就悲剧了😭。同时另一个项目，[ETCV](https://github.com/ethereumclassicvision),大家可否听到过？对，这就是Vitalik在担心的，虽然这个项目官网现在已经看不见了，他也是[打着私钥的主意](https://decryptmedia.com/4427/create2-ethereum-upgrade-developer-launches-constantinople)。


- [EIP1690: 销毁标准提案](https://github.com/ethereum/EIPs/issues/1690): 这个提案的目的非常简单，就是能够销毁一个无用的合约，这个标准通过创建一个`MortabilityStandardInterface`接口，通过`kill`方法来让`owner`销毁一个合约。非常简洁。

- [ProgPOW](https://medium.com/@ifdefelse/understanding-progpow-performance-and-tuning-d72713898db3) 这个由IfDefElse团队开发的抗ASIC算法已经得到了核心开发者的认可，认为需要引入该算法来对抗ASIC，只是目前还未达成一致是在什么阶段引入。大家对ProgPOW算法感兴趣的除了参考上述原文，还可以参考[以太坊爱好者的翻译](https://mp.weixin.qq.com/s/JApOJK22VmDSEGzwyd-ShA)，以及[这篇解释文章](https://mp.weixin.qq.com/s/ZgYYP2D-h8QDWW7dDxwTaA)。

#### EOS：聚焦公投2.0


- [EOS 公投系统1.0](https://eosalliance.io/eos-referendum/): EOS一直以社区公投为宣传点，这被称为是`liquidity democracy`, 这一具体流程是怎样的呢？EOSalliance 为超级节点公投做了一个汇总。期待在这里你看到。

- **公投2.0**：这是甜甜圈取的名字😄，EOS社区目前推进这一项[EOS BallotCraft Working Group](https://medium.com/@espin.brand/eos-ballotcraft-guide-published-5eddab9d8cf3)计划，为了自组织管理，我们需要一个很有效的提案和协商系统。这个计划就是为了创造一种流程，能够使得自组织决议变得容易。🍩期待~ 

- [EOS 公投提案](https://eosauthority.com/polls?lnc=en): 之前甜甜圈给小伙伴们介绍的是EOS超级节点的提案，属于治理层面，而公投，则属于人人可以发言的提案，这里包括[“是否人人一票？”](https://eosauthority.com/polls_details?proposal=1token1vote_20190111&lnc=en),["是否需要烧毁在EOSIO.savings中通胀的4%的通证?"](https://eosauthority.com/polls_details?proposal=1token1vote_20190111&lnc=en)等涉及到全局利益的问题。一些问题才开始2天，甜甜圈🍩发现EOS这里真的还是能够参与很多重要的事情的😄。期望小伙伴多多探索~

- [直接在区块链浏览器上公投](https://bloks.io/vote/referendums/rex4all): bloks浏览器为方便投票进行了很多的努力，使得投票变得容易。有时候，就是一个小小的整合也能使得公投的参与度大大的增加~Gook Job！
 


### 2.热锅上的项目🔥 
- **Pin**:[静待Grin](https://grin-tech.org/)&[Beam](https://www.beam.mw/): 利用mimblewimble共识机制的两个兄弟项目。两者的区别是Beam的商业化倾向相对较明显，期望通过与机构合作，进行融资等方式来进行项目。而Grin的社区属性较强，不接受投资等。**特别提醒Beam已经在北京时间1月3日主网上线，Grin将于1月15日，23:00 (11:00 PM)左右主网上线**
这是Curated list，帮助大家更好的认识Grin、Beam这个项目。
	- [Grin vs. BEAM, a Comparison](https://tlu.tarilabs.com/protocols/grin-beam-comparison/MainReport.html)
	- [通证通研究院：Grin 深度报告](https://www.chainnews.com/articles/182565597152.htm)
	- [Grin up 周报](https://www.chainnews.com/articles/049413235405.htm)
	- [Tokengazer: Grin挖矿设备投资收益分析报告](http://www.tokengazer.com/#/reportDetail?id=64)

- **项目警示** [En-Tan-En](http://www.entanmo.com/): 最近[基于纳什均衡的区块链项目 En-Tan-Mo获2000万元B轮融资](https://www.chainnews.com/articles/923687187654.htm)的新闻让一些小伙伴再次谈及En-Tan-En，甜甜圈调查发现项目真的非常特别，先不说B轮融资2000万，A轮是5000万的事实，甜甜圈急切期望搞清楚团队在哪里？社区在哪里？是否在持续推进？技术上取得了那些进展或者遇到了哪些障碍？这些却难以找到踪迹。同时主网预期2018年12月上线，而目前却迟迟没有动静~ 也期待小伙伴如果有项目团队信息可以联系我们。

### 3.Dapp跟踪:

#### 去中心化交易所

- [WORBLI for Interblockchain跨链](https://medium.com/@WORBLI/worbli-interblockchain-solving-ibc-edf39c165439): 跨链，一直是一个非常火🔥但是很难解决的问题，这其实不单单是一个技术问题，更可能是一个金融方案。所以，[worbli](https://worbli.io/)就出手了😄，在这个方案中，能够做到不单单是一对一数字货币的转换，目前能够在7中数字货币中转换。细节在[youtube](https://www.youtube.com/watch?v=R8SbACHWYNQ&feature=youtu.be)中有。有兴趣的小伙伴可以看一下~
 

### 4.近期深度文章

- [NEO的破局之道](https://www.chainnews.com/articles/769700569485.htm): 在聚集以太坊升级的时候，中国以太坊NEO最近如何了？小伙伴们对于NEO都有着深厚的感情，这篇文章为我们梳理了一些NEO的情况。就甜甜圈🍩看来，最新的进展包括[NEO.ONE](https://neo-one.io/)的成立和发展，[nOS](https://nos.io/)的项目体系的建立，已经最近的[NEO DevCon2](https://devcon.neo.org/)，都没有报道~ 甜甜圈🍩都期望做一期NEO的专刊了😄
- [如果加密世界是个迷宫，有哪些路是需要去尝试的？
](https://orange.xyz/p/302): 文章以自问自答形式描述了区块链目前的几大问题，包括：价值捕捉、游戏、稳定币、代币化证券、初始token分配、代币治理、货币政策、隐私、分发渠道、扩容与去中心化、web3、联盟链、零知识证明
- [为 2019 年的密码世界划重点](https://mp.weixin.qq.com/s/300o6WLxB5kUVFBM9w238g): 作者对区块链2019年的十大预测，涵盖63个点：比特币6项、以太坊8项、其他项目13项、一级市场项目5项、稳定币4项、区块链基金4项、区块链产品5项、区块链公司13项、政策监管5项
- [Pantera雄文：去中心化金融系统](https://mp.weixin.qq.com/s/oWfyX2cSVfdL_0cmQWBx9A)： 本文蕴含了Pantera的投资理念，尤其是最后的对于每个项目的技术，经济模型，团队等等方面的考察重点甜甜圈认为非常有借鉴意义。

通证甜甜圈🍩, XOrder.ai 欢迎多提宝贵意见! [邮件](qchen@xorder.ai)
