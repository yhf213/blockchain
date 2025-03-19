专题研究N：2025年融资区块链项目研究Irreducible

按：融资的项目作一个专题研究：1、融资了，说明得到资本界看好，可能是一个好的方向和项目；2、通过研究它们，可以了解外界或圈内人对这个行业的判断，是一种研究区块链发展趋势的捷径和正确的路；3、之前的区块链人物、项目系列研究也基本是追一些热点或按版块研究，已有1000期；基本也将常见的项目和区块链人物研究的差不多；正好可以告一段落（前期落下的一些已计划的还要继续，在1000期以内）；4、基于推特是目前区块链信息最集中和更新快的平台，还依托于此来研究相应的融资项目。5、2024年2月份，硬盘损坏；前期约有3600期（已发布约2000期）资料丢失；现未再续编号。

PANews 1月31日消息，据The Block报道，ZKP基础设施初创公司 Irreducible（前身为 Ulvetanna）完成2400万美元A轮融资，Paradigm和Bain Capital Crypto共同领投，Fenbushi Capital、L2 Iterative Ventures和Robot Ventures参投。据悉，Irreducible去年8月开始融资，9月确定了领投方，并于上个月完成了融资，最新的A轮融资结构为股权融资，但该公司联合创始人兼首席执行官Radisav Cojbasic拒绝对投资后估值发表评论。

Irreducible
，
@IrreducibleHW，
Accelerating the zero-knowledge revolution with the world's fastest proof generation.
BlockchainNew York, NY，irreducible.com，2022年4月 加入，
12 正在关注，
8,643 关注者

重磅消息！ Irreducible 推出了 Alpha 就绪的 Binius 库及其第一个应用程序，即以太坊状态证明服务。这意味着： 以太坊目前使用 Merkle-Patricia Tries，这在历史上对加密证明不友好。这就是为什么它的无状态验证路线图考虑了向替代数据结构 - Verkle 或 Poseidon Merkle 树的转变。我们证明，Binius 是唯一可以在不更改基本协议的情况下为以太坊启用完全无状态解决方案的证明系统，从而为实现 Verge 提供了一条加速而直接的途径。我们的概念验证服务为以太坊提供了一个实用的无状态客户端解决方案，为完整的解决方案奠定了基础，该解决方案允许节点在不保留整个协议状态的情况下验证区块。这降低了节点运营商的带宽要求，解锁了真正的去中心化，使节点可以在笔记本电脑、手机和智能手表的后台运行！无状态客户端要求每个区块都附有 （1） 在执行过程中读取或更新的账户地址和值列表，以及 （2） 证明值准确的简洁加密证明。我们的 PoC 解决了生成此证明时最具挑战性的方面，使用 Binius 压缩和验证所有账户的 Merkle-Patricia Trie （MPT） 数据。在 AMD 9354 CPU 上，~1400 次帐户读取的验证平均延迟为 ~11 秒，可将 3 MiB 数据压缩到 1 MiB。校样可以在这里下载和验证。我们通过使用一种名为 M3 的强大新算术模型来实现这一目标，该模型可以捕获复杂的 MPT作，而不会产生通用 zkVM 的开销。相比之下，高性能的 SP1 验证系统使用其定制的 Keccak-256 预编译和压缩功能模拟 1 亿次 RISC-V 循环，在 ~5 分钟内产生 1.2 MiB 的验证。（我们在此处开源了 SP1 代码以实现透明度）此版本附带一个全面的文档网站http://binius.xyz.开发人员现在可以自由地尝试 Binius - 转到网站的“构建”部分开始构建！下一步：基于 FPGA 的端到端硬件加速，将能够在几秒钟内为以太坊的 SNARKification 路线图进行实时验证。@IrreducibleHW
·
一月 9

即使数学不是你的菜，我写这篇文章也是为了让即使是 ZK 新手也能跟上。查看文章以获得更好的直觉！你以后会感谢我的。😏
https://blog.electisec.tech/binius-1-extension-fields，@0xteddav
·
二月 14

以下是我与
@jimpo_potamus
，联合创始人/首席技术官
@IrreducibleHW
.
Jim 是一个才华横溢的人 - 他是 Coinbase 的第一批工程师之一，回到学术界获得研究生密码学学位，现在正在为 zk 做出核心贡献。

新 EP：为什么 ZK Proof 的采用将在 2025 年爆炸式增长
ZK 验证一直很昂贵，但这种情况正在迅速改变。
在今天的节目中，
@Robbie_rollup
坐下来
@jimpo_potamus
之
@IrreducibleHW
和
@BruestleJeremy
之
@RiscZero
涵盖：
> ZK 证明的成本
> 新时代

重磅消息！我们筹集了 $24M 的 A 轮融资，由
@paradigm
和
@BainCapCrypto
，由
@fenbushi
,
@l2iterative
,
@robotventures
以及像
@AnnaRRose
,
@_bfarmer
,
@dlubarov
,
@sinahab
和
@varunsrin
!作为我们的旗舰证明系统，Binius 正在为加密证明设定新标准——更快、更高效，并且专为扩展而构建。借助基于 FPGA 的定制数据中心，我们为 Risc Zero、Polygon 等 zkVMs 提供支持。

RISC Zero 即将达到前所未有的速度。
我们正在与
@IrreducibleHW
将 Binius 集成到 RISC Zero zkVM 中。
加速。

很高兴地宣布我们与
@RISCZero
集成 Binius，为原来的 RISC-V zkVM 带来超快的性能。
我们共同为 ZK 性能和可访问性设定了新标准。RISC Zero 率先推出了第一款 RISC-V zkVM。现在，借助 Binius 的二进制字段架构，他们的 zkVM 即将达到前所未有的验证速度。通过此次集成，Binius 的突破性性能将覆盖 RISC Zero 和
@boundless_xyz
生态系统，使下一代 ZK 速度普遍可用。我们通过使用一种名为 M3 的强大新算术模型来实现这一目标，该模型可以捕获复杂的 MPT作，而不会产生通用 zkVM 的开销。相比之下，高性能的 SP1 验证系统使用其定制的

在 AMD 9354 CPU 上，~1400 次帐户读取的验证平均延迟为 ~11 秒，可将 3 MiB 数据压缩到 1 MiB。校样可以在这里下载和验证。

此版本附带一个全面的文档网站http://binius.xyz.开发人员现在可以自由地尝试 Binius - 转到网站的“构建”部分开始构建！下一步：基于 FPGA 的端到端硬件加速，将能够在几秒钟内为以太坊的 SNARKification 路线图进行实时验证。

今天，我要告别黄金海岸，一个我在过去 ~3 年里称之为家的地方。我们的使命
@IrreducibleHW
在别处需要我，现在是时候把柏林当作家了。再来一个 Stone and Wood for the bon voyage。Cu later good ol Straya🇦🇺🦘🐨🏄

Binius OS 与 ZK Whiteboard Sessions S2M5 的发布一起：“小字段/二进制字段”
@jimpo_potamus
从
@IrreducibleHW
!

今天，我们开源了更多的 Binius 代码！
binius-models 存储库是一个包含用于 Binius 算法的 Python 原型（模型）代码的包。这个学习资源对我们来说非常宝贵，希望对您来说也是如此！

Binius 1 岁生日快乐！🎂我们的生日愿望？成长为世界上最快的可验证计算机！
去年的情况如下👇

我们的新博客文章演示了使用位切片在 Nvidia GPU 上的高吞吐量二进制塔式 sumcheck，比 CPU 基线加速 4 倍！在此处了解更多信息👇

我们再次使 FRI-Binius 证明更小、更快！
上周，我们发布了 FRI-Binius 论文的更新，该论文改进了用于小场多项式承诺的环切换技术。https://eprint.iacr.org/2024/504

我深入研究了 Binary Tower Fields 的低级算术属性。
1/ 早在 2024 年 5 月，我就与 Paar 教授进行了交谈，了解到之前有很多工作比较了素数场和二进制场的硬件效率🧵👇

在我们的新博客文章中，Irreducible 团队描述了一种基于 GKR 的无符号整数乘法方法。这种技术将显著降低许多重要 Binius 任务的投入成本！在此处了解更多信息👇

Irreducible 已加入开发 AggLayer 的贡献者名单🌊Polygon Labs 和
@IrreducibleHW
正在基于 Binius 构建一个生产级的 zkVM，将二进制字段的突破性特性带到可验证的链下计算问题中。

Irreducible 正在与 Polygon 合作，在 Binius 的开发中迈出下一步：生产级 zkVM。我们的共同愿景是一个开源 VM，它将为Polygon AggLayer提供低成本、硬件加速的二进制证明。
了解更多信息：https://irreducible.com/posts/irreducible-x-polygon-labs-collaboration