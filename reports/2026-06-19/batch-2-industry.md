# 行业产品批 · 2026-06-19

**信源覆盖**：6/40（多数 Tier 2-3 源返回 403；命中 TechCrunch、AWS Blog、NVIDIA Blog、Google DeepMind Blog、HuggingFace Blog、Google Blog）  
**完成时间**：04:39 BJT

---

## 🚀 产品发布（9 篇）

### [1] Amazon Bedrock Managed Knowledge Base 正式上线——企业 RAG 全托管
- **来源** ｜ AWS Blog ｜ 2026-06-17 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://aws.amazon.com/blogs/aws/introducing-amazon-bedrock-managed-knowledge-base-for-faster-more-accurate-enterprise-ai-applications/

AWS 宣布 Bedrock Managed Knowledge Base 正式上线，提供全托管 RAG 管道，支持 S3、SharePoint、Confluence、Google Drive、OneDrive 等原生数据连接器，内置智能解析（Smart Parsing）和多跳检索（Agentic Retriever）。可无缝接入 AgentCore Gateway，兼容 LangChain、CrewAI、LlamaIndex 等 MCP 框架。区域覆盖美国东/西部、澳大利亚、日本、欧洲及 GovCloud，按存储量与检索次数按需计费，新用户可用 Free Tier。相比自建 RAG 方案，免去向量数据库选型、嵌入模型调优等工作，大幅降低企业 AI 应用上线门槛。

📌 **这意味着**：正在评估企业知识库/RAG 方案的 CIO，现在有了 AWS 原生全托管选项；核心决策维度从"如何搭建 RAG"简化为"是否接受 AWS 生态锁定"。

---

### [2] Amazon Bedrock AgentCore 上线 Web Search——零数据外泄的实时联网能力
- **来源** ｜ AWS Blog ｜ 2026-06-17 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://aws.amazon.com/blogs/aws/announcing-web-search-on-amazon-bedrock-agentcore-ground-your-ai-agents-in-current-accurate-web-knowledge/

AWS AgentCore 新增 Web Search 工具，允许 AI Agent 检索实时网络信息，同时保证查询数据不离开 AWS 基础设施——这是与 Perplexity、Brave Search API 等第三方方案的关键差异。底层使用 Amazon 自有搜索索引（同 Alexa+、Kiro 技术栈）结合 Amazon Knowledge Graph，返回标题、摘要、来源 URL 和发布日期。目前仅在 us-east-1 区域 GA，工具本身不额外收费，仅收 Gateway 数据传输费，新用户可获 $200 Free Tier 额度。对受 GDPR、HIPAA 等合规约束的企业，"零数据外泄"是关键卖点。

📌 **这意味着**：金融、医疗等对数据主权敏感行业的 CTO，可将联网检索纳入合规 AI Agent 设计，而无需审批额外供应商或数据处理协议。

---

### [3] AWS Transform 推出持续现代化（Preview）——自动扫描代码库消技术债
- **来源** ｜ AWS Blog ｜ 2026-06-17 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://aws.amazon.com/blogs/aws/proactively-reduce-tech-debt-autonomously-with-aws-transform-continuous-modernization-preview/

AWS Transform 新增"持续现代化"能力（Preview），可自动扫描代码仓库，识别过期依赖、废弃框架、Java 版本落后、SDK 迁移需求等技术债务，数小时内生成扫描结果并自动提 PR 修复。支持两种模式：持续模式（跟随标准演进滚动更新）和 Campaign 模式（处理跨百个应用的大规模框架迁移）。集成 AWS Security Agent 可同步扫描安全漏洞。通过 AWS Transform Web 应用、Kiro Power 或 MCP 与编码 Agent 接入。暂未公布定价。与 GitHub Copilot Workspace、Cursor 等形成直接竞争，但深度 AWS 集成是其差异化护城河。

📌 **这意味着**：考虑"AI 驱动代码库现代化"的 CTO 可将此纳入 PoC 候选；存量 Java/企业应用改造场景优先评估。

---

### [4] General Intuition 融资 $3 亿——用 20 亿视频训练 AI Agent 的具身智能公司
- **来源** ｜ TechCrunch ｜ 2026-06-18 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/18/general-intuition-in-talks-to-raise-300m-at-around-2b-valuation/

General Intuition 正在洽谈 B 轮 $3 亿融资，估值约 $20 亿，距去年 $1.34 亿种子轮仅八个月。公司从 Medal（游戏录制平台，月活 1000 万）剥离，利用 Medal 每年 20 亿条视频数据训练具身 AI 和空间/时序推理 Agent。投资方包括 Jeff Bezos（Prometheus）、Eric Schmidt、Khosla Ventures、General Catalyst。OpenAI 此前曾尝试收购 Medal 但未成功，可见该视频数据集的战略价值。新资金主要用于扩充算力，计划 2026 年夏末/秋初发布首款产品，核心方向是面向机器人的 foundation world model。

📌 **这意味着**：机器人/具身 AI 赛道融资热度持续，大规模视频数据集正成为核心竞争壁垒；关注其秋季产品发布以判断 B2B/B2C 定位。

---

### [5] Snap 拆分 AI 视频团队成立 Dotmo——成本压力下的战略剥离
- **来源** ｜ TechCrunch ｜ 2026-06-18 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/18/snap-spins-off-ai-video-team-into-new-company-dotmo-due-to-costs/

Snap 将 AI 视频团队拆分为独立公司 Dotmo，专注 AI 模型驱动的互动游戏和数字娱乐体验。Snap CTO Bobby Murphy 作为主要个人投资者（同时继续担任 Snap CTO），Snap 保留大量股权并提供技术授权，Dotmo 可后续寻求外部融资。这是 Snap 2026 年第二次拆分（此前已拆出 Specs 专注智能眼镜），今年 4 月还裁员约 1000 人（16% 员工）。该"剥离+股权保留"模式让 Snap 在削减 AI 内部成本的同时保留未来上行潜力。

📌 **这意味着**：大厂通过"战略剥离 + 保留股权"控制 GenAI 研发成本的模式正在成型；适合企业 AI 预算决策参考——高成本 AI 研发可考虑类似结构。

---

### [6] XDOF 出走隐身——$7000 万融资，专做机器人训练数据的规模化基础设施
- **来源** ｜ TechCrunch ｜ 2026-06-17 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/17/collecting-robot-training-data-is-dirty-unglamorous-work-some-ai-labs-are-already-paying-xdof-to-do-it/

XDOF 从隐身状态出击，宣布获得 Thrive Capital、Spark Capital、a16z、Lux、WndrCo $7000 万融资，已有 20 家客户（含多家顶级 AI 实验室，身份保密）。提供三层数据采集：实际部署机器人的遥操作数据、使用 GELLO 低成本遥控器的通用遥操作数据、可穿戴设备采集的以自我为中心的人体运动数据。与 UC Berkeley AI 研究室联合发布 ABC 数据集——迄今最大高质量机器人训练集，含 13 万条操作轨迹、400 小时训练素材。仅 60 人团队，2024 年 10 月成立。

📌 **这意味着**：机器人 AI 的"数据飞轮"基础设施正在成型，采购商/集成商可将 XDOF 等专业数据公司纳入机器人 AI 供应链评估体系。

---

### [7] Google Gemma 4 12B——统一无编码器多模态开源模型正式发布
- **来源** ｜ Google Blog ｜ 2026-06 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://blog.google/innovation-and-ai/technology/developers-tools/introducing-gemma-4-12b/

Google 发布 Gemma 4 12B，定位统一的、无编码器（encoder-free）多模态开源模型，引入统一架构设计，移除独立图像/视频编码器组件（具体 benchmark 分数因官方页面限制暂无法获取）。Gemma 系列一贯以可在消费级 GPU 运行、Apache 2.0 许可证著称，12B 参数量适合企业私有部署场景。无独立编码器架构理论上可降低部署复杂度并提升跨模态任务一致性。同月 Google 还发布 DiffusionGemma（4 倍速文本生成）和 Gemini 3.5 Live Translate，显示 Google 在开源与闭源双线持续推进。

📌 **这意味着**：希望本地部署多模态能力的企业，Gemma 4 12B 是开源阵营优先测试选项；建议等完整 benchmark 数据公布后再决定生产部署时间表。

---

### [8] Google DiffusionGemma——扩散架构文本生成速度提升 4 倍
- **来源** ｜ Google Blog ｜ 2026-06 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://blog.google/innovation-and-ai/technology/developers-tools/diffusion-gemma-faster-text-generation/

Google 发布 DiffusionGemma，将扩散（Diffusion）模型架构应用于文本生成，宣称相比标准 Gemma 实现 4 倍速度提升。这是 Gemma 系列首次引入扩散范式，区别于传统自回归（autoregressive）生成方式——一次性并行生成而非逐 token 序列生成。该方向与学界 MDLM、MDM 等工作一致，代表 Google 在非自回归文本生成路线的最新落地。具体推理延迟数字和 benchmark 评分因官方页面限制暂无法获取，但 4 倍速提升若在生产环境验证，将显著降低推理成本并提升实时对话场景的用户体验。

📌 **这意味着**：对推理吞吐/成本敏感的 AI 产品团队，DiffusionGemma 值得优先跟踪评测；若延迟数据真实，可能改写实时对话场景的模型选型逻辑，尤其是高并发场景。

---

### [9] Google Gemini 3.5 Live Translate——流畅自然的实时语音翻译产品化
- **来源** ｜ Google DeepMind Blog ｜ 2026-06 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-live-3-5-translate/

Google 发布 Gemini 3.5 Live Translate，主打"流畅、自然的语音翻译"体验，基于 Gemini 3.5 系列针对实时语音场景优化。与 DeepL、Whisper+翻译管道类方案形成直接竞争。Google 此前在 Pixel 设备上已有 Recorder 实时翻译能力，此次将能力独立产品化，面向企业实时翻译场景（跨语言客服、跨国会议、国际现场演讲等）。具体支持语言数量、延迟数据和定价因官方页面限制暂无法获取，预计后续随正式文档披露。

📌 **这意味着**：跨语言客服、跨国会议等场景的 AI 采购方可将 Gemini 3.5 Live Translate 纳入 2026 H2 选型评估，与 Microsoft Azure AI Speech 翻译服务对比测试。

---

## 🏢 厂商动态（7 篇）

### [10] OpenAI IPO 前大动作：引入 Transformer 发明人 Shazeer + 白宫 AI 政策官员 Ball
- **来源** ｜ TechCrunch ｜ 2026-06-18 ｜ **质量分** ｜ 9/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/18/openai-is-bringing-on-some-big-guns-in-the-lead-up-to-its-ipo/

OpenAI 宣布两项重磅人事：（1）Noam Shazeer 加入——2017 年"Attention Is All You Need"论文的 Transformer 架构联合发明人，此前创立 Character AI 并被 Google 以 $27 亿收购，在 Google 工作超 20 年；（2）Dean Ball 将于 7 月 6 日出任战略未来负责人（Strategic Futures Leader），前 Trump 白宫 AI 政策官员、美国 AI 行动计划参与者，向首席战略官 Jason Kwon 汇报。Ball 团队将处理灾难性风险、递归自我改进、劳动力市场影响及与美国联邦政府关系等议题。IPO 进程中的技术深度（Shazeer）与政策影响力（Ball）双线加码意图明显。

📌 **这意味着**：OpenAI 正在为 IPO 构建"技术可信度 + 政策护城河"双重叙事；竞争对手 Anthropic 在美国出口管制压力下，OpenAI 正强化与政府关系的相对优势。

---

### [11] Amazon 宣布将向第三方销售 Trainium AI 芯片——潜在年营收规模 $500 亿
- **来源** ｜ TechCrunch ｜ 2026-06-18 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/18/amazon-hopes-to-challenge-nvidia-more-directly-by-selling-its-ai-chips/

亚马逊 CEO Andy Jassy 披露：若 AWS 芯片业务独立运营，年化营收将达约 $500 亿（接近 Intel 整体年营收水平），远低于 Nvidia $3260 亿但仍是重大市场机会。亚马逊历史上拒绝直接出售芯片（因其更赚钱的商业模式是收取 AI token 处理费 + 周边服务），此次转变是对外部买家强烈需求的回应。Trainium 芯片生产容量几乎瞬间售罄，制造商为台积电，下一代 Trainium4 将于一年后推出。此举将直接与 Nvidia、AMD、Intel 竞争，并可能影响其自身云服务的定价逻辑与差异化策略。

📌 **这意味着**：Nvidia 的 AI 芯片单一供应商风险正在降低；企业 AI 算力采购的谈判筹码增加，建议 2026 H2 芯片采购前等待 Amazon Trainium 正式报价。

---

### [12] NVIDIA 在戛纳广告节展示营销 AI 生态——Blackwell GPU 赋能 2x 训练加速
- **来源** ｜ NVIDIA Blog ｜ 2026-06-18 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://blogs.nvidia.com/blog/nvidia-ai-marketing-advertising-cannes-lions/

NVIDIA 在 Cannes Lions 广告节展示多项 AI 营销合作：Criteo 使用 cuEmbed 库在 Blackwell GPU 上将模型训练速度提升约 2 倍；KERV.ai 通过 Nemotron 3 Nano Omni 实现内容理解速度和效率超 10 倍提升；Alembic 在 DGX Vera Rubin SuperPODs 上运行因果 AI 分析营销 ROI；Higgsfield 提供从创意到优化的全营销自动化 AI 代理（Supercomputer agents）；AWS 发布基于 NVIDIA Triton 的实时竞价生产参考实现。显示 NVIDIA 正将 GPU 生态从后端基础设施延伸至前端营销技术栈。

📌 **这意味着**：CMO 和营销技术采购方需评估 AI 营销代理的 ROI 计算模型；NVIDIA 的"AI 营销平台化"战略意味着未来广告技术堆栈将深度依赖 GPU 基础设施。

---

### [13] Google DeepMind 发布 AI Agent 安全控制路线图——五层纵深防御体系
- **来源** ｜ Google DeepMind Blog ｜ 2026-06 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://deepmind.google/blog/securing-the-future-of-ai-agents/

Google DeepMind 发布 AI 代理安全综合框架，将 AI Agent 视为潜在"内部威胁"，采用改编自 MITRE ATT&CK 框架的威胁建模体系，按"探测规避能力"和"攻击执行能力"两个维度定义风险矩阵（D1-D4 检测级别和 R1-R3 响应级别，映射至 AI 能力里程碑）。五层纵深防御：传统沙箱/端点安全 → 模型对齐训练 → 行为监控（可信 AI 监督器）→ 实时阻断（高风险操作前拦截）→ 异步审计（已分析超 100 万次编码 Agent 任务）。同时发布面向政策制定者的"三层代理安全技术文档"。

📌 **这意味着**：CISO 在审批部署 AI Agent 时，可将此框架作为安全评估基准；Prompt 注入防护仅是入门，行为级监控与人机协作控制点才是核心要求。

---

### [14] Google DeepMind 与多方联合资助多 Agent AI 安全研究——最高 $1000 万
- **来源** ｜ Google DeepMind Blog ｜ 2026-06 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://deepmind.google/blog/investing-in-multi-agent-ai-safety-research/

Google DeepMind、Schmidt Sciences、Cooperative AI Foundation、英国 ARIA（先进研究与发明机构）、Google.org 联合设立最高 $1000 万研究基金，方向为多 Agent AI 安全。申请截止 2026 年 8 月 8 日，秋季公布结果。四个优先方向：可复现的多 Agent 沙箱/测试床（虚拟市集、模拟生态等）、Agent 网络涌现特性科学（检测危险群体行为）、Agent 基础设施安全（跨平台身份/声誉协议）、大规模 Agent 部署监督与控制。核心问题：数百万来自不同机构的 AI Agent 同时交互时，当前孤立评估方法无法捕捉的涌现风险如何防范。

📌 **这意味着**：部署多 Agent 编排系统的企业（如使用 AutoGen、CrewAI、LangGraph 的团队）应开始将群体安全评估纳入 Agent 系统 SLA；学术界申请窗口至 8 月 8 日。

---

### [15] Google DeepMind 携手英国政府 AI 加速规划审批——50% 提速目标，2027 年全国推广
- **来源** ｜ Google DeepMind Blog ｜ 2026-06 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://deepmind.google/blog/unlocking-uk-house-building-with-ai-accelerated-planning/

Google DeepMind 与英国政府 i.AI 孵化器、Faculty 合作，在 Barnet、Dorset、Camden 三个地方议会试点 Gemini 驱动的 AI 规划审批工具。基于早期"Extract"工具（每议会年节省约 255 小时）升级，新原型可整合场地数据、标注适用政策（附引用）、汇总公众咨询反馈并生成初步评估报告草稿，目标将决策时间缩短 50%。每年约 70% 的规划申请属于住宅改建类（householder applications）。规划官员保留全部决策权并可编辑所有 AI 内容，符合英国 AI 治理"人类在环"要求。计划 2027 年推广至英格兰所有地方议会。

📌 **这意味着**：政府/公共部门 AI 应用落地进入新阶段；Google Cloud 在 GovTech 市场与 Microsoft Azure Government 竞争加剧，国内政务 AI 场景可借鉴此"辅助审批"定位。

---

### [16] Pew Research：仅 16% 美国人认为 AI 对社会有正面影响——公众信任创新低
- **来源** ｜ TechCrunch ｜ 2026-06-17 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/17/only-16-percent-of-americans-think-ai-will-have-a-positive-impact-on-society-a-new-study-shows/

皮尤研究中心 2026 年度调查：仅 16% 美国人预期 AI 在未来 20 年对社会产生正面影响，40% 预期负面，67% 不相信政府会有效监管 AI，59% 不信任企业负责任开发 AI，近三分之二认为 AI 发展速度过快。年龄悖论：30 岁以下年轻人最悲观（仅 14% 正面），65 岁以上约 75% 从未使用聊天机器人。市场份额：ChatGPT 44%、Gemini 24%、Copilot 17%、Meta AI 14%，约 25% 用户每日使用，60% 定期阅读 AI 生成新闻摘要。男性每日使用率（27%）高于女性（20%）。

📌 **这意味着**：消费者 AI 产品面临信任危机；企业 AI 推广须配合可验证 ROI 案例和透明度策略，"价值叙事 + 可控人机协作"比"全自动 AI"更容易被接受。

---

## ⚙️ 基础设施 / 技术（5 篇）

### [17] FERC 强制电网快速通道——AI 数据中心供电需求将在 2035 年前三倍增长
- **来源** ｜ TechCrunch ｜ 2026-06-18 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/18/ai-data-centers-just-got-a-government-mandated-fast-lane-to-the-grid/

美国联邦能源监管委员会（FERC）2026 年 6 月 18 日全票通过命令，要求全美六大电网运营商为数据中心等大型用电设施提供互联申请快速通道，研究周期对灵活负载压缩至 60 天，数据中心承担自身接入成本，并探索固态变压器、超导输电线等创新技术。关键局限：命令未解决发电容量短缺问题——截至 2023 年底，电网接入申请总量已超过现有所有发电站总容量；批发电价五年内最高涨幅达 267%；数据中心电力需求预计到 2035 年近三倍增长。

📌 **这意味着**：在美国扩建 AI 数据中心的企业，接入审批流程加速；但底层发电容量缺口未解，核能/可再生能源 PPA 的战略价值进一步凸显，应尽早锁定长期电力协议。

---

### [18] NVIDIA 与 Emerald AI 合作开发"灵活 AI 设施"——自发电 + 电网稳定资产
- **来源** ｜ NVIDIA Blog ｜ 2026-06-18 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://blogs.nvidia.com/blog/ferc-large-load-interconnection/

NVIDIA 欢迎 FERC 裁决，并披露与 Emerald AI 的合作：开发设计为"电网资产"的灵活 AI 设施，具备自发电、实时响应电网状况和提供电网稳定化服务的能力，计划 2026 年晚些时候开始商业部署。NVIDIA 引用劳伦斯伯克利国家实验室研究：电力消费每增加 10%，零售电价可降低约 6 美分/千瓦时，以此支持"AI 数据中心有助于降低电价"的叙事。战略意义：NVIDIA 正将芯片业务延伸至能源基础设施，构建更垂直的 AI 基础设施生态，挑战传统公用事业与数据中心商的分工格局。

📌 **这意味着**：大规模 AI 基础设施采购方应将"可再生能源 PPA + 灵活负载设计"纳入数据中心选址的标准要求项，而非可选项。

---

### [19] HuggingFace + ServiceNow：AI 研究 Agent 查询日志会泄露企业机密——"马赛克效应"
- **来源** ｜ HuggingFace Blog ｜ 2026-06-18 ｜ **质量分** ｜ 9/10 ｜ **链接** ｜ https://huggingface.co/blog/ServiceNow/mosaicleaks

ServiceNow 与 HuggingFace 联合研究揭示：深度研究 Agent（研读内部文档 + 联网搜索）的查询日志会通过"马赛克效应"泄露企业机密——单条查询无害，但组合后可还原私密事实。测试基准 MosaicLeaks 含 1001 条多跳研究链，衡量三类泄露：意图泄露、答案泄露、完整信息泄露。关键发现：仅优化任务性能会恶化隐私——答案泄露率从 34.0% 升至 51.7%；提示词指令无效。解决方案 PA-DR（隐私感知深度研究）将 RL 奖励与隐私惩罚项结合，将泄露降至 9.9% 的同时保持 58.7% 任务成功率。核心结论："不能靠 Prompt 保护隐私，必须训练进去。"

📌 **这意味着**：CISO 必须立即审计企业内部研究 Agent 的查询日志管理策略；采购 Agent 产品时须询问其隐私对齐训练机制，而非仅依赖 System Prompt 约束。

---

### [20] HuggingFace：LoRA 并非总是最优——PEFT 方法评测揭示参数效率前沿
- **来源** ｜ HuggingFace Blog ｜ 2026-06-18 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://huggingface.co/blog/peft-beyond-lora

HuggingFace PEFT 团队对 LoRA、BEFT、Lily、LoRA-FA、OFT、GraLoRA 等方法进行多维度横向评测。数学任务（MetaMathQA）：Lily 以 54.9% 准确率超越标准 LoRA 的 53.2%，但需更多显存（25.6 GB vs 22.6 GB）；BEFT 仅需 20.2 GB 但准确率降至 32.9%。图像生成任务：OFT 在相似度指标（0.708）上严格优于 LoRA（0.697），同时使用更少显存（9.01 vs 9.97 GB）。结论：不存在单一最优 PEFT 方法，需根据准确率/显存/速度三者权衡选择；PEFT 统一 API 使方法切换成本极低，建议纳入微调实验管线。

📌 **这意味着**：MLE/MLOps 团队应将 PEFT 方法选择纳入模型实验管线，而非默认 LoRA；尤其在显存受限的私有部署场景，OFT 等方法值得优先测试。

---

### [21] HuggingFace：大模型受益于 Agent 优化，小模型（≤14B）反而退化——能力拐点实测
- **来源** ｜ HuggingFace Blog ｜ 2026-06-18 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://huggingface.co/blog/is-it-agentic-enough

HuggingFace 使用 pi coding agent 和 agent-eval 基准测试框架，对 Kimi-K2.6、GLM-5.1、MiniMax-M2.7 等大模型及 Qwen3-4B、Qwen3-14B 等小模型进行工具调用和 Agent 能力评测。关键发现：CLI 优化对大模型有益（减少任务时间），但对小模型有害——Qwen3-14B 在"classify-sentiment"任务上因将文档误判为可调用工具，准确率从 100% 降至 0%。评测框架同时衡量"完成任务用了多少轮/Token/秒"，揭示常规成功/失败指标掩盖的权衡取舍。建议对任何 ≤14B 模型在工具感知场景下进行专项测试。

📌 **这意味着**：在 ≤14B 参数规格部署 AI Agent 前，必须进行工具感知专项评测；Agent 能力存在约 14B 参数的能力拐点，小模型的 Agent 优化策略不能简单复制大模型经验。

---

## ━━━ 审计区 ━━━

- **Tier 2 命中**：1/22
  - ✅ TechCrunch（8 篇）
  - ❌ The Verge（403）｜ Wired（403）｜ Ars Technica（403）｜ VentureBeat（403）｜ ZDNet（403）｜ Engadget（403）｜ CNET（拒绝访问）
- **Tier 3 命中**：4/12
  - ✅ AWS Blog（3 篇）｜ NVIDIA Blog（2 篇）｜ Google DeepMind/Google Blog（7 篇部分有详情）
  - ❌ Anthropic Blog（403）｜ OpenAI Blog（403）｜ Microsoft AI Blog（403）｜ Meta AI Blog（无近期内容）｜ IBM Research（403）｜ Salesforce（403）｜ Databricks（403）｜ Snowflake（403）
- **Tier 4b 命中**：1/5
  - ✅ HuggingFace Blog（3 篇）
  - ❌ InfoQ（403）｜ IEEE Spectrum（403）｜ arXiv（403）｜ ACM（未访问）
- **失败源汇总**：The Verge、Wired、Ars Technica、VentureBeat、ZDNet、Engadget、CNET、Anthropic Blog、OpenAI Blog、Microsoft AI Blog、IBM Research Blog、Salesforce Blog、Databricks Blog、Snowflake Blog、InfoQ、IEEE Spectrum、arXiv（共 17 源返回 403 或访问拒绝）
