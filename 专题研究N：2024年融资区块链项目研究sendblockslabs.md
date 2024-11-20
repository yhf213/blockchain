专题研究N：2024年融资区块链项目研究sendblockslabs

按：融资的项目作一个专题研究：1、融资了，说明得到资本界看好，可能是一个好的方向和项目；2、通过研究它们，可以了解外界或圈内人对这个行业的判断，是一种研究区块链发展趋势的捷径和正确的路；3、之前的区块链人物、项目系列研究也基本是追一些热点或按版块研究，已有1000期；基本也将常见的项目和区块链人物研究的差不多；正好可以告一段落（前期落下的一些已计划的还要继续，在1000期以内）；4、基于推特是目前区块链信息最集中和更新快的平台，还依托于此来研究相应的融资项目。5、2024年2月份，硬盘损坏；前期约有3600期（已发布约2000期）资料丢失；现未再续编号。

PANews 7月2日消息，据Chainwire报道，区块链数据管理初创公司SendBlocks宣布获得820万美元种子轮融资，由Castle Island Ventures领投，其他投资者包括Pitango、Illuminate Financial、Laser Digital（野村）和Starkware等。SendBlocks通过其可定制的平台简化区块链数据访问，使企业、生态系统和应用程序能够定义和获取所需数据。现有客户包括Bancor和SphereX。SendBlocks的首个产品是“通用结算层”，支持任何编程语言结算区块链交易。公司还在开发“通用零知识电路”，以实现“无信任的远程计算”和跨区块链的智能合约。项目预计将在2024年底进入测试网。此次融资将用于扩大研发团队和提升市场营销及销售力度，以吸引更多顶级协议和生态系统。

sendblockslabs
，
@sendblockslabs，
Blockchain data pipelines, made simple. 
Say goodbye to indexing, wasting gas on event-logs and constantly querying RPCs. Start writing functions.
sendblocks.io，2024年2月 加入，
127 正在关注，
452 关注者，


如果有一种简单的方法来获取实时清算警报就好了。http://sendblocks.io/notifications，下午3:21 · 2024年8月5日
·

我们脸红了！很高兴能和 Rohan 一起工作🙏下午4:22 · 2024年7月29日
·

@sendblockslabs
而且该球队被低估了。

让他做饭！不，真的🧑‍🍳
当
@shrem_itay
邀请你去吃家常菜时，你却饿着肚子去！ 🤤
我们公司聚会玩得很开心，而且非常兴奋我们在 Kahoot 打败了老板:) 

嗯.. 真有趣！我们..
✔正式脱离隐身状态😎 ；
✔受到一些知名人士的报道📰 ；
✔设法将泰勒·斯威夫特的引用放入新闻稿中💫
如果你错过了，所有细节都在第一条评论中🤸‍♂️ 

我们认为情况恰恰相反😇 😈
但如果你在 ethcc bru - 赶上
@shrem_itay
和
@missronigur
并亲自看看😉

我们认为情况恰恰相反😇 😈
但如果你在 ethcc bru - 赶上
@shrem_itay
和
@missronigur
并亲自看看😉 

不要错过最精彩的屋顶哈希小时🍸我们将在
@EthCC
 ) 第一天与
@StellarOrg
 、 
@bitgetglobal
 、 
@ApeBond
 、 
@sendblockslabs
 、 
@beefyfinance
 、 
@Somnia_Network
和
@MergeMadrid
在布鲁塞尔最具历史意义的景点之一举办！ 

我们..出名吗？ 😎

开玩笑而已，但我们非常高兴能够正式脱离隐身状态🥂

非常感谢我们的投资者的持续支持，感谢我们的客户成为如此出色的合作伙伴，以及感谢
@BusinessInsider
撰写的文章🙏

非常感谢 SendBlocksonim！第一条评论中的链接（您知道算法） 🔗

@CastleIslandVC
 | 
@Pitango
 | 
@IlluminateFM
 | 
@LaserDGroup
 | 
@StarkWareLtd
 | Itay Malinger 
@curvmpc
 | 
@KatzAnton
 | Zero Knowledge Ventures | Larry Sukernik 
@hi_Reverie
 | 
@SpherexTech
 | 
@Bancor
 | Itay Shrem 
@shrem_itay
 | Michael Kellner | Idan Meshita | Or Shrim | Adam Fisher 
@ind_curiosity
 | Mariel Cherkassky | Daniel Yoffe | Dor Sharabi | Or Aharonee | Roni Gur

对于最新的#Kraken / #Certik漏洞的快速思考。
TLDR：本机传输和内部调用可能很难正确处理，而处理不当可能会导致非常危险的后果。 🧵Kraken 漏洞的根本原因似乎是他们需要找到所有转移到其存款地址的原生代币。这可以在外部交易或内部交易中发生。由于原生传输不会发出任何事件，因此必须深入研究交易跟踪才能找到这些传输。这意味着您必须使用更复杂的 RPC 查询并扩展后端以处理所有数据。为了避免这种情况，人们通常依赖事件和外部交易状态来减少所需的处理量。但捷径很难走。在 Kraken 的案例中，攻击者在中间部署了一个恶意合约，并使外部交易成功而内部交易失败。在这种情况下，会发出 LogFeeTransfer 事件并将交易标记为成功，这可能使 Kraken 的后端在交易跟踪中搜索发送到其存款地址的任何本机转账。这可能导致 Kraken 的后端将原生代币的内部转移标记为成功，即使事实并非如此，从而导致“双重支付”原生代币的能力。我们知道处理链上数据可能很困难，因此我们构建了平台来帮助轻松获取任何数据点。SendBlocks 的创建正是为了跟踪与地址相关的所有活动（无论是内部还是外部），而无需开发人员进行任何后端工作。

合作提醒！很高兴能与 OG 合作 - 
@Bancor
 | 
@CarbonDeFixyz
 😎
我们的通知现已与 Bancor 集成，让用户可以密切关注他们的 Mantle 交易👀
完整故事见此处： https://sendblocks.io/sendblocks-provides-bancor-real-time-data-for-users/

“这是强化版的区块链数据”是来自
@monad_xyz
建设者的直接引述👷‍♀️我们下周将在 Foundry 见到谁？ 

我们很高兴参加 Consensus 并为
@monad_xyz
的纽约活动做好准备！
感谢我们一路上遇到的所有很棒的人，并期待继续建立这些关系< 3

“我刚刚阅读了文档，它简直就是强化版的区块链数据”——这种开发人员的反馈让我们感到很开心🙂
我们自己的
@ShremItay34961
昨天在
@monad_xyz
的建筑商办公时间玩得很开心！
我们很高兴看到 Monad 生态系统不断发展💙

谁要去奥斯汀参加
@CoinDesk
的共识会议？我们自己的
@shrem_itay
会去那里，很乐意一起喝点东西，讨论 web3 的一切！加入我们的 DM :)

您知道吗？通知可将用户留存率提高 800% 以上🤯 ，没错，这不是笔误。更多信息请见此处：
https://sendblocks.io/increasing-user-engagement-with-fully-customizable-notifications/

随着 EIP 3074 的推出，账户抽象正在得到提升，但你知道它也会抽象交易吗？更多信息请见此处>> 
https://sendblocks.io/internal-function-calls-why-should-you-care/

从数十年的情报机构经验到 web3 构建，从企业软件到区块链数据 - 你好，世界，我们是 SendBlocks！
https://sendblocks.io/hello-world/

