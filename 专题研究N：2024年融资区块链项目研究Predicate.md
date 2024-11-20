专题研究N：2024年融资区块链项目研究Predicate


按：融资的项目作一个专题研究：1、融资了，说明得到资本界看好，可能是一个好的方向和项目；2、通过研究它们，可以了解外界或圈内人对这个行业的判断，是一种研究区块链发展趋势的捷径和正确的路；3、之前的区块链人物、项目系列研究也基本是追一些热点或按版块研究，已有1000期；基本也将常见的项目和区块链人物研究的差不多；正好可以告一段落（前期落下的一些已计划的还要继续，在1000期以内）；4、基于推特是目前区块链信息最集中和更新快的平台，还依托于此来研究相应的融资项目。5、2024年2月份，硬盘损坏；前期约有3600期（已发布约2000期）资料丢失；现未再续编号。

PANews 10月15日消息，据Fortune报道，由Celo平台的两位前成员创立的加密监管解决方案公司Predicate完成了700万美元的融资，投资方包括Tribe和1kx等机构。Predicate致力于帮助加密公司应对监管挑战，提供一种可以决定某项交易是否获批的逻辑基础服务，这种基础设施广泛应用于Netflix和Venmo等产品。本周，Predicate正式推出其产品，并计划在去中心化理念下运营，现已支持以太坊及其他EVM兼容链，未来将扩展到更多区块链。

Predicate
,
@0xPredicate,
Define rules for onchain interactions,
Ethereum,predicate.io,2023年12月 加入,
7 正在关注,
4,477 关注者,


已置顶:介绍 Predicate。这是第一次，交易先决条件可以由开发人员和社区定义和拥有，而不会损害去中心化。我们很高兴宣布总共筹集 700 万美元来实现这一愿景。 ⬇️为什么要有先决条件？与 Venmo 和 Uber 等应用程序的情况一样，随着 web3 应用程序扩展到更广泛的全球经济，预交易规则成为关键的构建模块。

Predicate 将这个概念带到了链上，提供了一个以最小化信任的方式可执行的先决条件库。我们系统的核心是 Predicate 函数，它评估条件并返回真或假，决定链上操作是否可以继续。

谓词是规则的基础，规则通过堆叠形成策略。任何实体（个人、DAO、组织）都可以创建和管理策略，这些策略使用链上和链下数据，例如资金流、允许列表和可验证凭证。

借助 Predicate 的模块化设计，开发人员可以专注于构建其核心创新。本季度我们推出了一系列激动人心的产品，涵盖了各种交易前要求。可能性无穷无尽——从账户级风险评分、抵押品验证、速率限制、异常检测到链上历史证明。如果你是一名开发者，请详细了解 Predicate 的功能，并通过以下方式联系我们,最后，请阅读有关 Predicate 和我们在 Fortune https://fortune.com/crypto/2024/10/15/predicate-raises-7-million-to-help-blockchain-applications-connect-with-the-financial-world/上的筹款活动的更多信息。下午11:13 · 2024年10月15日

AVS 将改变加密技术。
了解我们与
@eigenlayer
合作的成果、我们为何构建 Predicate 以及我们为何将其设计为 AVS，与
@pumpernikhil
和
@Innovate_grow_
共同主持
@maddelena_b
和
@dipesh_sukhani
一起，下午11:27 · 2024年10月29日
·

1/ Power Transaction Prerequisites with 
@0xPredicate
 (Prev Aethos)
Predicate is using EigenLayer to help developers streamline pre-transaction logic while prioritizing user experience.
Through transaction prerequisites, developers can create more expressive onchain interactions.

@eigenlayer
掌握技术和叙事⛓️ 📚
在最新一期的
@Innovate_grow_
中， 
@dipesh_sukhani
和我与创始人
@pumpernikhil
 
@0xPredicate
一起深入探讨 @0xPredicate
以下是 4 大要点👇

首届 DC 隐私峰会现场直播：BA 成员
@AleoHQ
的政策副总裁 Leena Im 与 
@0xPredicate
 的
@Reillymj
和
@pumpernikhil
 @0xPredicate一起讨论如何实现#privacy 、 #compliance和#decentralization 。

我们很荣幸能与
@PGPforCrypto
 、 
@Coinbase
研究所和
@ProjectGlitch_
就这一重要主题展开合作。 #PrivacyIsNormal

照片来源： 
@HJAB413
来自 BA

隐私协议需要确保合规性，同时还要确保去中心化。了解 Predicate 如何实现这一点，请参加明天的 DC 隐私峰会，届时
@pumpernikhil
将与
@AleoHQ
一起发言。由
@projectglitch_
主办，
AVS 将改变加密技术。

了解我们与
@eigenlayer
合作的成果、我们为何构建 Predicate 以及我们为何将其设计为 AVS，与
@pumpernikhil
和
@Innovate_grow_
共同主持
@maddelena_b
和
@dipesh_sukhani
一起

链上执行开始的方式很简单：开发人员部署智能合约，用户将交易发送到公共内存池，验证器逐行执行合约代码以进行状态转换。

后来，我们看到了“协处理器”的引入，它允许合约与链下可验证计算提供商进行通信，并等待以可证明的方式返回结果。这种方法通常更具成本效益，而且由于协处理器可以访问“链下”数据，因此它们可以实现纯链上执行无法支持的用例。

这种“链下计算即服务”模式以前可供智能合约开发人员使用，并且必须在每个应用程序级别激活。但是，如果您想在钱包或用户帐户的智能合约级别公开此功能，该怎么办？

这就是
@0xPredicate
用武之地。借助其 DSL，任何 UI 都可以请求政策遵守证明，并且运营商可以根据来自信息提供商的数据提供这些证明。

这是交易供应链日益复杂的又一例证。它允许用户和前端直接在交易中包含*可选性*，并允许服务提供商在交易在链上完成之前完善交易。

通过这种方式， 
@khalani_network
旨在成为一个平台，在这个平台上，此类证明请求和服务提供商响应可以*完全可组合地编程*、发布、编排、查询和查找以及执行。

我们期待与
@0xPredicate
团队合作，踏上这段激动人心的旅程。

祝贺 Predicate 团队！

今天，我们很高兴地宣布我们对
@0xPredicate
投资，这是一个开放交易先决条件的框架。
使用 Predicate 的策略，实体可以在不影响去中心化的情况下对交易语义进行精细控制。

祝贺
@recvcx
 port co 
@0xPredicate
筹集 700 万美元！
Predicate 率先采用模块化、信任最小化的链上策略来满足交易前提条件。借助这一新原语，我们可以向链上经济添加反洗钱、抵押品验证等功能。Predicate 为下一波开发者和机构开辟了新的设计空间。
在过去的一年里，与
@pumpernikhil
和
@Jessesawa
合作绝对是一件愉快的事，因为他们坚持不懈地执行着他们对 Predicate 的愿景。
这支球队即将取得重大成就！ 🚀

如果您今天在湾区参加 Builder Demo Day 💡别忘了加入我们
@NGC_Ventures
和
@0xPredicate
下午 2 点至 6 点，我们在那里见

@FigmentCapital
为支持性领投人设定了标准。自
@0xPredicate
成立以来，他们一直是我们从 GTM 战略到运营的构思和执行的首选来源之一。他们几乎无时无刻不在工作。
我的许多创业者朋友都告诉我，他们的主要投资者并没有提供太多帮助。Figment Capital 则证明了事实并非如此。

过去 9 年里，我们一直听说“加密货币正在被大规模采用”。
自从我们进入加密行业以来，我们就一直在听到这个词。
现在看来，这种情况正在发生，但很少有人问自己是否已经为这一刻做好了准备。

@0xPredicate
是那些罕见的项目之一，一旦理解，就会从根本上重塑你的世界观。
祝贺
@pumpernikhil
 、 
@Jessesawa
和团队成功筹集最新资金--激动人心的时刻即将来临。

Predicate 允许开发人员为加密应用程序创建并执行可定制的交易包含策略，充当半透膜以增强安全性和控制力，同时保持抗审查性
祝贺加薪，很高兴能够共同建设！

让加密货币变得半渗透且活跃
————————————
想象一下一个细胞，它有一个细胞边界，可以让毒素和营养物质进入。

如果遇到不利的情况，该细胞很快就会死亡。事实上，如果细胞内外没有化学梯度，细胞就会被视为死亡。

换句话说，开放的边界不是边界。

这就是当今加密的状态 —— 交易包含对交易来自谁或交易内容是盲目的。

这是一个很好的价值（抵制审查），但结果是，它允许黑客和用户平等访问，它允许机器人和人类平等访问，流氓 agi 和友好 agi 平等访问。

目前还不清楚这是否是正确的最终状态。

所有天然细胞都是半透性的：允许营养物质进入，但不允许毒素进入。

@0xPredicate
是隐球菌的半透膜。

允许开发人员自行制定细致入微的包容政策。

可以让所有人类免费访问，同时对机器人收取更高的费用；可以排除所有黑客交易，同时包括所有正常交易；可以包括所有合法交易，同时禁止非法交易。

如果基础层能够最大程度地抵抗审查，那么所有这一切都会变得更好，因为您可以在其上构建更多自定义包含策略。

这就是为什么
@0xPredicate
建立在
@eigenlayer
和
@ethereum
之上。

为
@pumpernikhil
创始人之旅加油！

专注于简化交易先决条件的网络
@0xPredicate
在由
@1kxnetwork
 、 
@tribecap
 、 
@FigmentCapital
领投的一轮融资中筹集了 700 万美元，其他参投方包括
@recvcx
 、 
@HashKey_Capital
 、 
@WhiteStarCap
 、Very Early Ventures、 
@cyberFund_
 、 
@GSR_io
 、 
@deptofxyz
 、Everstake Capital、( 
@ConsenSys
 )、 
@nearfoundation
 、 
@cjliu49
 、 
@followrene
 )、 
@marek_
 、 
@sandeepnailwal
 、 
@yorgosv_
 、 
@waikit
 。

介绍 Predicate。这是第一次，交易先决条件可以由开发人员和社区定义和拥有，而不会损害去中心化。我们很高兴宣布总共筹集 700 万美元来实现这一愿景。 ⬇️为什么要有先决条件？与 Venmo 和 Uber 等应用程序的情况一样，随着 web3 应用程序扩展到更广泛的全球经济，预交易规则成为关键的构建模块。
Predicate 将这个概念带到了链上，提供了一个以最小化信任的方式可执行的先决条件库。

像这样：实现隐私、合规和去中心化，以
@AleoHQ
和
@pumpernikhil
政策副总裁、 
@0xPredicate
首席执行官兼联合创始人 Leena Im 为主角

欢迎来到 EigenLayer Unlocked 🪄
我们从 EigenLayer 生态系统中挑选了一批特殊的建设者，从今天开始参加一场为期数周的虚拟活动。
点击此处加入我们：
http://eigen.therollup.co

新一代 DeFi 协议正在以协处理器和 AVS 为核心构建（例如
@lagrangedev
 、 
@0xPredicate
 、 
@OpacityNetwork
等）。
@ishaan0x
将这一趋势称为“智能 DeFi”，我认为没有更好的方式来描述它。
智能合约将再次变得智能。

@EigenLayer
团队的
@ishaan0x
撰写了一篇很棒的文章！

新一代智能 DeFi 协议正在构建中，其核心是以 ZK 协处理器、zkTLS 和其他支持 AVS 的中间件等新颖的原语为核心。

Ishaan 的文章中强调了一些趋势，我认为这些趋势对于 DeFi 的未来非常有预见性：

1. 个性化 DeFi：第一代 DeFi 应用为每个用户提供相同的体验。DEX 具有单一费用等级，与交易量无关，借贷应用不会调整贷款条款，收益聚合器依赖于简单的策略。

随着可验证的链下计算的出现，这种情况将会改变。DEX 将开始推出忠诚度计划，还款历史将反映在借款人的 APY 上，协议参数可以通过 AI 动态调整。

ZK 协处理器将成为这一转变的核心。

2. MEV 拍卖和资源定价：在交易执行时，MEV 的价格发现很难（甚至不可能）在合约中量化。用于证明、DA 和存储的链下网络的资源定价也必须根据网络需求进行调整。

特定应用排序（ 
@SorellaLabs
 ）和 Prover Networks（ 
@LagrangeDev
 ）中的链下拍卖是实现更资本高效市场的早期步骤。

3. 隐私是可以的：想要私人交易并建立尊重用户数据隐私的协议是可以的。

zkTLS ( 
@OpacityNetwork
 ) 将使 DeFi 协议能够将 Web2 数据连接到 Web3，同时仍能保护用户隐私。想象一下现实世界信用价值的证明在链上 DeFi 中被私下使用。

此外，@AethosNetwork 等政策网络将很快实现混合器和私有 DeFi 的存在，同时仍保持监管合规性。

Ishaan 最后指出，基于 EigenLayer 构建的基础设施生态系统正在不断发展，可供开发人员用来构建面向消费者的新形式的 DeFi。再加上有利于应用程序级构建者的资本环境，我们很快就会看到 DeFi 内部发生革命。 https://x.com/eigenlayer/sta/eigenlayer/status/1836218948502851972

📽️管理 AVS 风险
@0xyorke
 、 
@ismael_h_r
 、 
@melynx
和
@pumpernikhil
在
@mchen8864
的主持下进行了一场内容广泛的对话。他们讨论了重新质押稳定性、池化安全性的含义等。
请继续关注我们在 EthCC 举行的 Restaking Day 活动的更多视频

Aethos 正在招聘
我们正在构建一个政策层，因为我们相信，从规模上讲，自主主权只有通过自我监管才有可能实现
我们的团队规模虽小但实力强大，我们在内部积累了大量的动力，今年将投入生产
我们正在寻找具有高代理经验的工程师（我们的堆栈；golang 和 solidity，专注于开发人员工具）
薪酬非常丰厚，远程优先，但纽约优先，告诉你的朋友🙏

我们很高兴地宣布，@aethosnetwork 的创始人兼首席执行官
@pumpernikhil
将作为演讲者参加 BLR RSTK 2024！

Aethos Network 是一个去中心化的策略引擎，可为链上交易执行可定制的规则和条件。

Nikhil 将就启用可编程策略的复杂性发表一场深刻的演讲。他的演讲将非常有见地，所以千万不要错过！

在此注册： https://lu.ma/frwvuq4x
📅 8 月 3 日
📍班加罗尔