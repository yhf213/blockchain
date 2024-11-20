专题研究N：2024年融资区块链项目研究Katara AI


按：融资的项目作一个专题研究：1、融资了，说明得到资本界看好，可能是一个好的方向和项目；2、通过研究它们，可以了解外界或圈内人对这个行业的判断，是一种研究区块链发展趋势的捷径和正确的路；3、之前的区块链人物、项目系列研究也基本是追一些热点或按版块研究，已有1000期；基本也将常见的项目和区块链人物研究的差不多；正好可以告一段落（前期落下的一些已计划的还要继续，在1000期以内）；4、基于推特是目前区块链信息最集中和更新快的平台，还依托于此来研究相应的融资项目。5、2024年2月份，硬盘损坏；前期约有3600期（已发布约2000期）资料丢失；现未再续编号。

Odaily星球日报讯 Web3 开发者体验平台 Katara AI Inc.宣布完成 220 万美元种子轮融资，Diagram Ventures 和 Sparkle Ventures 联合领投，StreamingFast 以及多位天使投资人参投，截至目前该公司的融资总额已达到 260 万美元。新融资将用于拓展 Web3 客户群之外的 Web2 公司业务。
该初创公司构建了一个开发者体验平台，集成了生成人工智能、机器学习和自然语言处理技术，可自动反馈并实时响应开发者的查询。其目的是简化开发人员引入并提高效率。
此平台可以部署到 Discord、Telegram、Slack 等平台，并且已集成至 Avail Protocol、Hivemapper 和 Filecoin 等 Web3 协议和项目中。（Silicon Angle）

Katara AI，
@KataraAi，
AI-Powered Workflow tools for DevX Teams - backed by 
@diagramventures
, 
@sparkle_VC
, 
@StreamingFast
 and others.
Barcelona / NYC ，katara.ai，2020年1月 加入，
134 正在关注，
117 关注者


Katara AI secures $2.6M led by seed funding❗️
▶️ Workflow automation platform, 
@KataraAi
  raised $2.2M in seed funding totaling $2.6M, led by 
@diagramventures
 , and 
@Sparkle_VC
▶️ Katara aims to expand its platform beyond #Web3 incorporating #Web2 and open-source platforms.
下午5:57 · 2024年8月28日

Katara 
@KataraAi
 Raises $2.2 Million in Seed Round，下午1:52 · 2024年8月28日

介绍：POKT Network 的 AI Litepaper
本文探讨了在网络上部署大型语言模型的潜力，以提供强大且可扩展的人工智能推理。

合并 LLM 或更好——LLM 的知识融合！
几周前，Abacus AI 开源了一款合并堆叠的 LLM。从根本上讲，您要将多个预先训练的 LLM 组合在一起，以形成一个性能更高的新模型！
FuseLLM 进一步采用了这种方法，并从概率分布的角度探索了模型的结合。论文“LLM 的知识融合”（链接见 alt）表明，他们的方法在 27 个任务上的表现比基础模型（在本例中为 Llama-2）高出 5%。这是通过结合模型实现的相当显著的改进！
目前，合并在 LLM 领域正风靡一时，每天都会发布多个合并模型！这似乎是一种非常有创意的方法，并且收益高达 5%，它可能会被多个小型 AI 实验室采用。
我们最好的开源模型的 MMLU 大约为 75-76，如果我们能够通过巧妙地合并这些模型，使它们的性能提高 5%，那么我们可能会达到 80！这使我们的 GPT-4 得分达到 6 分
鉴于这些技术不需要太多计算，我们将在未来几周看到几种方法。

发布的 LLM 研究数量惊人。虽然新论文数量太多，一个人根本读不完，但这些研究可以大致归纳为一组更小的重叠主题。最近，LLM 研究中有三种趋势特别有影响力……

（1）合成训练数据：使用 LLM 生成自己的训练数据长期以来一直是一个热门话题。这方面的例子包括 Constitutional AI、Orca、RLAIF 和 Evol/Self-Instruct。然而，这个主题目前在 AI 研究界引起了极大的兴趣，并产生了几篇出版物：
- 在[1]中，作者表明合成训练数据可用于训练最先进的嵌入模型。
- 我们在 [2] 中看到，可以轻松生成和验证数学和编码问题的合成数据，然后可以使用这些数据来提高 LLM 的性能。

(2) LLM 安全性：自 GPT-2 提出以来，安全部署一直是 LLM 开发的首要任务（即，出于安全考虑，GPT-2 权重未向公众发布！）。尽管人工智能社区似乎更愿意在部署 LLM 时承担风险，但安全性仍然是许多实验室的首要任务。然而，我们在最近的研究中了解到，确保 LLM 部署的安全性极其困难：
- [3] 中的研究表明，即使经过了大量的安全训练，训练到 LLM 中的后门攻击仍然存在，形成可以欺骗人类用户的潜在代理。
- 我们在 [4] 中了解到，只要使用适当的提示技术，几乎所有的 LLM 都可以提取训练数据，即使是那些已经经过大量调整的 LLM。

(3) 知识注入：几乎每个企业都对使用自己的内部/专有数据（例如 BloombergGPT、EinsteinGPT、ShopAI 等）训练 LLM 感兴趣。然而，目前尚不清楚如何才能最好地将预训练的 LLM 专门用于特定领域的知识库。在 [5] 中，作者为此对微调和 RAG 进行了广泛的比较，发现 i) 通过微调向 LLM 传授新信息非常困难，但 ii) RAG 在将知识注入 LLM 方面非常有能力。这个主题在过去也得到了广泛的研究：
- [6] 中的作者提出了检索增强生成（RAG），表明这种方法对知识密集型任务的性能有影响。
- LIMA [7] 表明，LLM 的几乎所有知识都是在预训练期间学习的。
- Phi-1 [8]表明，知识型 LLM 可以通过规模较小、精选的数据集（即教科书）进行训练。

--------
[1] Wang, Liang 等人，“使用大型语言模型改进文本嵌入。”arXiv 预印本 arXiv:2401.00368 (2023)。
[2] Singh, Avi 等人，“超越人类数据：利用语言模型扩展自我训练以解决问题。”arXiv 预印本 arXiv:2312.06585 (2023)。
[3] Hubinger, Evan 等人，“潜伏特工：通过安全培训持续存在的欺骗性法学硕士培训”。arXiv 预印本 arXiv:2401.05566 (2024)。
[4] Nasr, Milad 等人，“从（生产）语言模型中可扩展地提取训练数据。”arXiv 预印本 arXiv:2311.17035 (2023)。
[5] Ovadia, Oded 等人，“微调还是检索？比较法律硕士中的知识注入。”arXiv 预印本 arXiv:2312.05934 (2023)。
[6] Lewis, Patrick 等人。“针对知识密集型 NLP 任务的检索增强生成。”《神经信息处理系统进展》第 33 卷 (2020) 期：9459-9474。
[7] 周春婷等，“Lima：对齐少即是多。”arXiv 预印本 arXiv:2305.11206 (2023)。
[8] Gunasekar, Suriya 等人，“教科书就是你所需要的一切。”arXiv 预印本 arXiv:2306.11644 (2023)。

RAG 的 4 个代理级别🤖
一系列的代理功能可以根据您的数据提供从简单到高级的推理。
这是关于 4 个不同级别的代理以及它们如何增强您的 RAG 管道👇的简介🧵
1 ⃣工具使用：可以根据用户查询来查询一组工具的线性管道。
最简单的例子是路由器： https://docs.llamaindex.ai/en/stable/examples/query_engine/RouterQueryEngine.html
2 ⃣推理循环 + 记忆：围绕 RAG 管道的简单循环。给定用户查询和之前的对话历史记录，推断出一个新查询来查询管道。
我们在文本到 SQL 查询引擎上添加了一个简单的重试层： https://docs.llamaindex.ai/en/latest/examples/agent/agent_runner/query_pipeline_agent.html#setup-simple-retry-agent-pipeline-for-text-to-sql
3 ⃣推理循环 + 记忆 + 工具使用：围绕管道的循环，旨在根据用户查询选择一组工具。
在这里，我们将推理循环与工具使用结合起来。这里有一个简单的例子，即路由器顶部的重试层： https://docs.llamaindex.ai/en/stable/examples/agent/custom_agent.html
4 ⃣奇特的推理循环 + 工具使用 + 记忆：推理循环可以变得任意复杂，从顺序的 ReAct 思路链到 LLMCompiler 风格的并行规划和工具使用。
从头开始 ReAct： https://docs.llamaindex.ai/en/latest/examples/agent/agent_runner/query_pipeline_agent.html
在这里查看我们的 LLMCompiler 实现：
