# 行业产品批 · 2026-07-01

**信源覆盖**:23/29(主流媒体 2/8、厂商博客 12/16+3 个额外厂商、垂直 2/5)
**完成时间**:2026-07-01 04:50 BJT

---

## 🚀 产品发布(12 篇)

### [1] X 上线官方 MCP 服务器,AI 工具可直连平台数据
- **来源** ｜ TechCrunch ｜ 2026-06-30 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/30/x-now-offers-an-mcp-server-to-make-its-platform-easier-for-ai-tools-to-use/

X(原 Twitter)推出托管版 Model Context Protocol(MCP)服务器,Claude、Cursor、Grok Build 等 AI 工具可用用户自身账号权限直连 X,支持读帖、搜索、用户查询、话题/对话分析,但不兼容 Write API、无法自主发帖。X 同时上调 API 发帖定价(单帖 $0.015、含链接帖 $0.20)以遏制滥用。GitHub、Slack、Notion、Stripe、Salesforce 此前已提供 MCP 服务器。

📌 **这意味着**:MCP 正成为平台与 AI Agent 对接的事实标准接口;企业在评估社交数据集成方案时应优先考虑官方 MCP 而非自建爬虫。

---

### [2] Proton Lumo 2.0:隐私优先 AI 聊天机器人新增图像生成与"思考模式"
- **来源** ｜ TechCrunch ｜ 2026-06-30 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/30/lumo-protons-privacy-focused-ai-chatbot-gets-an-upgrade/

Proton 发布 Lumo 2.0,新增图像识别与生成、带持久记忆的"Projects"组件升级、"思考模式",响应速度较 1.0 版提升 76%。免费、Plus、Professional 三档订阅即日生效。CEO Andy Yen 强调零访问加密、不留服务端会话日志、不用用户数据训练模型的隐私定位。

📌 **这意味着**:隐私合规要求较高的企业(医疗、法律)可将 Lumo 列入 AI 助理选型候选,作为主流大厂产品的合规替代。

---

### [3] Anthropic 发布 Claude Science:面向科学家的 AI 工作台公测
- **来源** ｜ TechCrunch ｜ 2026-06-30 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/30/anthropics-claude-science-bets-on-workflow-not-a-new-model-to-win-over-scientists/

Anthropic 推出 Claude Science 公测版,定位为"工作流而非新模型"——基于现有 Claude 模型(含 Opus 4.8)连接 60 多个科学数据库,预置基因组学、蛋白质组学、化学信息学等工具包,主助手可调度子助手、配备事实核查 AI 及可复现图表生成,并支持本地实验室基础设施对接。面向 Pro/Max/Team/Enterprise 用户开放,提供最高 3 万美元额度资助 50 个精选科研项目。Allen Institute、UCSF 脑肿瘤中心、Novo Nordisk 已是早期用户。

📌 **这意味着**:药企和科研机构 CIO 可将分散的科研工具链整合进单一可审计平台,但需评估"工作流而非模型"定位与现有科研 IT 架构的契合度。

---

### [4] OpenClaw 开源 AI Agent 项目上线官方 iOS/Android App
- **来源** ｜ Engadget ｜ 2026-06-29 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://www.engadget.com/2204549/theres-now-an-openclaw-app-for-ios-and-android-phones/

OpenClaw(创始人 Peter Steinberger已加入 OpenAI,项目现由 OpenClaw Foundation 运营)发布官方手机 App,通过二维码/配对码与用户现有 OpenClaw Gateway(运行于 Mac/Linux/Windows)经 WebSocket 连接,使 AI Agent 可调用手机摄像头、屏幕、定位、相册、通讯录、日历、提醒事项等权限。项目周下载量已突破 117 万次,是 2026 年增长最快的开源 AI 项目之一。

📌 **这意味着**:开源 Agent 生态正从桌面端向移动端渗透,企业 IT/安全团队需关注员工自行部署个人 Agent 网关带来的设备权限暴露风险。

---

### [5] AWS 宣布 Claude Sonnet 5 全面登陆 Amazon Bedrock,跨区域吞吐达每秒 10 万次请求
- **来源** ｜ AWS Machine Learning Blog ｜ 2026-06-30 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://aws.amazon.com/blogs/machine-learning/introducing-claude-sonnet-5-on-aws-anthropics-most-capable-sonnet-model/

Anthropic 最新 Sonnet 5 模型已在 Amazon Bedrock 及 AWS 版 Claude Platform 上线,宣称以 Sonnet 价位提供接近 Opus 级别智能,主打编程、智能体与专业文档处理,支持跨多区域每秒 10 万次请求级吞吐。促销价(输入 $2/输出 $10 每百万 token)持续至 2026 年 8 月 31 日,覆盖北美、南美、欧洲及亚太多个区域。

📌 **这意味着**:已采购 AWS 算力的企业可直接在 Bedrock 内低成本试用接近旗舰水平的模型,是压缩 AI 预算、迁移现有 Claude 工作负载的窗口期。

---

### [6] 微软研究院发布 SkillOpt:把 Agent"技能文件"变成可训练参数,52 项测试全部刷新最优
- **来源** ｜ Microsoft Research Blog ｜ 2026-06-30 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://www.microsoft.com/en-us/research/blog/skillopt-agent-skills-as-trainable-parameters/

SkillOpt 将智能体的自然语言"技能文件"当作模型权重之外的可训练参数,无需改动模型本身即可优化。6 个基准 × 7 个模型 × 3 种执行模式共 52 项测试全部取得最优或并列最优;GPT-5.5 直接对话模式平均分从 58.8 提升至 82.3(+23.5 分),SpreadsheetBench 提升 39 分。优化后的小模型(GPT-5.4-mini)平均分超过未优化的大模型基线,最终技能文件平均约 920 个 token,已开源。

📌 **这意味着**:企业可通过低成本的"提示工程式"训练而非昂贵的模型微调提升智能体性能,大幅降低部署门槛。

---

### [7] 微软研究院推出 Memora 记忆架构,长对话 token 消耗最高降 98%
- **来源** ｜ Microsoft Research Blog ｜ 2026-06-29 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://www.microsoft.com/en-us/research/blog/memora-a-harmonic-memory-representation-balancing-abstraction-and-specificity/

Memora 通过"主要抽象"(6-8 词摘要)与"线索锚点"分离存储内容与检索路径,在 LoCoMo 和 LongMemEval 基准上分别取得 86.3% 和 87.4% 准确率,超越 Mem0、RAG 及全上下文推理方案,相比全上下文处理 token 消耗最高降低 98%,单次对话存储条目数仅为 Mem0 的约一半。论文已发表于 ICML 2026,代码开源。

📌 **这意味着**:长期运行的 AI 助理和 Agent 可以更低成本维持跨月乃至跨年的上下文记忆,为企业级长周期 Agent 应用扫清成本障碍。

---

### [8] 思科 AI Defense 推出 Agent Runtime Protection,一行代码加装 LLM/MCP 安全护栏
- **来源** ｜ Cisco AI Blog ｜ 2026-06-29 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://blogs.cisco.com/ai/securing-ai-agents-with-cisco-ai-defense

思科 AI Defense Python SDK 推出"Agent Runtime Protection",开发者调用一行代码 `agentsec.protect()` 即可让所有 LLM 调用和 MCP 交互自动接入安全检测,支持监控/拦截/关闭三种模式,已开源并适配七种主流 Agent 框架及 AWS Bedrock、GCP Vertex AI、Azure AI Foundry。

📌 **这意味着**:CIO 可用极低工程成本为现有 LLM/MCP 调用链路加装安全护栏,降低 Agent 上线的安全合规门槛。

---

### [9] Snowflake 发布"数据-模型-代理"三层安全框架,为 Agent 提供可审计身份
- **来源** ｜ Snowflake AI Blog ｜ 2026-06-26 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://www.snowflake.com/en/blog/securing-the-agentic-enterprise/

Snowflake 发布三层 Agent 安全框架:数据层减少数据扩散、模型层防御提示注入攻击、Agent 层为每个 AI 智能体赋予可审计独立身份,使查询、API 调用和工具触发均可追溯。

📌 **这意味着**:企业批量部署 AI Agent 前,需将身份治理和提示注入防护作为采购评估的硬性指标。

---

### [10] Oracle Fusion SCM 新增四款供应链 Agentic 应用
- **来源** ｜ Oracle News ｜ 2026-06-29 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://www.oracle.com/news/announcement/oracle-adds-new-fusion-agentic-applications-to-help-customers-improve-supply-chain-performance-2026-06-29/

甲骨文在 Oracle Fusion Cloud 供应链与制造(SCM)中新增四款由多个协同 AI 代理组成的"智能体应用",用于提升库存可见性、降低供应商与运营风险并提高制造效率,同时推出新的库存优化能力以增强供应链韧性,均原生内置于 Fusion SCM 平台。

📌 **这意味着**:CIO 在评估 ERP/SCM 平台时,需关注厂商是否已将多代理协同能力原生内嵌入核心模块,而非依赖第三方插件。

---

### [11] Oracle 推出 Manager Edge:HCM 云端 AI 管理者教练
- **来源** ｜ Oracle News(PR Newswire) ｜ 2026-06-30 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://www.prnewswire.com/news-releases/oracle-helps-organizations-scale-effective-leadership-with-oracle-manager-edge-302814856.html

甲骨文在 Fusion Cloud HCM 中推出 AI 教练工具"Manager Edge",基于反馈、目标、绩效评估及团队互动数据为管理者提供实时个性化领导力指导,可通过 Oracle Touchpoints、Slack 和 Microsoft Teams 访问。

📌 **这意味着**:HR/HCM 采购方应评估 AI 教练工具与现有协作工具的集成深度,作为衡量员工体验 ROI 的新维度。

---

### [12] IBM 开源 ScarfBench:前沿编码 Agent 在企业级 Java 框架迁移任务上成功率不足 10%
- **来源** ｜ Hugging Face Blog ｜ 2026-06-30 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://huggingface.co/blog/ibm-research/scarfbench

IBM Research 发布基准测试 ScarfBench:覆盖 34 个应用、102 种框架实现、204 项迁移任务、约 15.1 万行代码、1331 条专家编写测试,测试 Spring、Jakarta EE、Quarkus 三大框架迁移(Jakarta EE 最难)。前沿编码 Agent 行为成功率普遍低于 10%;Claude Code 自评 30 次构建成功 29 次,但独立验证仅 22 次真正编译通过,暴露 Agent 自我评估过度自信问题。

📌 **这意味着**:企业在用编码 Agent 做遗留系统迁移前,应建立独立于 Agent 自报告的验证机制,不能只看模型自评分数。

---

## 🏢 厂商动态(8 篇)

### [13] 据报 Google 限制 Meta 使用 Gemini 算力额度
- **来源** ｜ Engadget(引自 Financial Times) ｜ 2026-06-29 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://www.engadget.com/2203579/google-reportedly-capped-meta-use-of-gemini-ai-for-coding-chatbots/

据报 Google 在 Meta 超出分配算力额度后对其 Gemini 使用设限,此前 3 月已发出预警。Meta 将 Gemini 用于客服、广告主聊天机器人、编程、有害内容下架及诈骗检测(因 Gemini 在这些任务上表现优于自家 Llama 模型)。Meta 已承诺未来两年投入 6000 亿美元云计算,但自身不运营云业务。同期 Google 另以每月 9.2 亿美元向 SpaceX 采购 xAI 数据中心算力以扩充 Gemini Enterprise 产能。

📌 **这意味着**:即便是巨头之间,大模型 API 也存在算力配额博弈;重度依赖单一外部模型 API 的企业应评估多供应商备份方案以避免被"限流"。

---

### [14] Claude 在 Microsoft Foundry 全面上线,计入 Azure 统一账单
- **来源** ｜ Claude.com Blog(Anthropic) ｜ 2026-06-29 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://claude.com/blog/claude-in-microsoft-foundry

Claude 在 Microsoft Foundry 实现全面上线(GA),企业可在 Azure 环境中使用已有身份认证、计费与治理体系调用 Claude 模型,并可选择美国数据驻留区。计费采用统一的 Claude 消耗单位(CCU),合并入 Azure 账单。Claude Sonnet 5 推广价(输入 $2/输出 $10 每百万 token)持续至 2026 年 8 月 31 日,此后恢复标准价 $3/$15。

📌 **这意味着**:已深度绑定 Azure 生态的企业客户现可用原有治理与计费流程合规接入 Claude,降低多供应商 AI 采购的集成门槛。

---

### [15] 诺基亚、SAP、微软签署多年战略协议,推进云与 AI 驱动转型
- **来源** ｜ SAP News Center ｜ 2026-06-30 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://news.sap.com/2026/06/nokia-sap-microsoft-strategic-multi-year-agreement-advance-cloud-ai-driven-business-transformation/

诺基亚与 SAP、微软签署多年战略协议,采用"RISE with SAP"方法论将 S/4HANA 部署于 Azure,整合财务与物流系统,并逐步启用云应用中嵌入的 AI 功能。

📌 **这意味着**:大型企业 ERP 云迁移正与超大规模云厂商及 AI 能力绑定为统一交易,CIO 需同步规划云基础设施与 AI 路线图。

---

### [16] Salesforce 提出"循环工程"理念,Agentforce Voice 案例:Zing Health 双语客服
- **来源** ｜ Salesforce News ｜ 2026-06-29 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://www.salesforce.com/news/stories/loop-engineering/

Salesforce 提出"循环工程"(Loop Engineering)概念,主张赋予智能体目标与进度衡量标准而非脚本化提示词。以客户 Zing Health 为例,其 Agentforce Voice 智能体"Mia"为 33 个医保计划提供双语即时支持,具备智能路由与无缝转人工能力。

📌 **这意味着**:CIO 采购 AI 智能体平台时,应优先考察其是否支持以业务结果为导向的评估与治理机制,而非单纯比拼脚本灵活度。

---

### [17] Palantir 联合英伟达,基于 Nemotron 开放模型为美国政府机构提供主权 AI 引擎
- **来源** ｜ NVIDIA Blog ｜ 2026-06-29 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://blogs.nvidia.com/blog/palantir-secure-ai-us-agencies-nemotron-open-models/

Palantir 推出搭载英伟达 Nemotron 开放模型的"主权 AI 操作系统"智能引擎,整合 AIP、Ontology、Foundry、Apollo 四大产品,面向美国约 300 万联邦雇员及关键基础设施运营商,支持气隙(air-gapped)隔离部署,机构可保留模型权重所有权并用自有数据持续训练。

📌 **这意味着**:政府与受监管行业的 IT 决策者获得了"开放模型+主权部署"的新合规路径,可在不依赖云端 API 的前提下定制专属 AI 能力。

---

### [18] Cohere 联合 Wiz 推出安全运营 AI Agent,事件响应从 2 小时压缩至分钟级
- **来源** ｜ Cohere Blog ｜ 2026-06-25 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://cohere.com/blog/cohere-security-ai-agent-north-wiz

Cohere 企业 AI 智能体平台 North 通过自建 MCP 服务器接入云安全平台 Wiz,构建安全智能体,可自动完成关键发现分诊、攻击链评估(综合互联网暴露面、权限级别、数据敏感度排序)、起草事件响应报告、创建工单及更新 Wiz 状态。官方称该流程此前每起事件最长耗时达 2 小时,相关实现方案已开源供企业复用。

📌 **这意味着**:安全运营团队可将 AI Agent 直接嵌入现有云安全工具链,实现从告警到响应报告的端到端自动化,显著降低 MTTR。

---

### [19] Mistral Connectors 平台升级企业级权限管控,目录覆盖 60+ 集成
- **来源** ｜ Mistral AI News ｜ 2026-06-24 ｜ **质量分** ｜ 5/10 ｜ **链接** ｜ https://mistral.ai/news/more-control-over-connectors/

Mistral 为 Connectors(连接器)平台新增企业级安全功能并已全量上线:可按工作区/组织设置管理员权限、支持作用域限定的 API 密钥防止自动化工作流冒用身份、支持单连接器多账号认证。同时推出 Connectors Debugger(11 步端到端故障排查,公测中)及 Workflows 长任务连接器(公测中),目录已覆盖超 60 个集成(Salesforce、Jira、Slack、GitHub 等)。

📌 **这意味着**:企业 IT 与安全团队现在可对 AI Agent 访问第三方系统的权限做精细化治理,是规模化部署生产级 Agent 的必要前提。

---

### [20] 英伟达 BioNeMo 智能体工具包接入 Claude Science,18/20 大药企已在使用
- **来源** ｜ NVIDIA Blog ｜ 2026-06-30 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://blogs.nvidia.com/blog/claude-science-bionemo-agent-toolkit/

英伟达 BioNeMo Agent Toolkit 现已集成进 Anthropic 的 Claude Science 公测平台,全球前 20 大制药企业中已有 18 家在使用 BioNeMo。RAPIDS-singlecell 可将单细胞数据预处理时间从 52 分钟压缩至 25 秒,nvMolKit 可将化学信息学计算提速最高 3000 倍,科学家可用自然语言调用蛋白质结构预测、分子对接等智能体技能。

📌 **这意味着**:制药与生物科技企业的研发负责人可借助自然语言交互的 AI Agent 大幅压缩计算周期,需评估与 Claude Science 及 NVIDIA 加速库的集成路径。

---

## ⚙️ 基础设施 / 技术(6 篇)

### [21] Firefly Aerospace 首次在月球轨道运行英伟达 Jetson 边缘 AI 平台
- **来源** ｜ NVIDIA Blog ｜ 2026-06-29 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://blogs.nvidia.com/blog/firefly-aerospace-nvidia-jetson-lunar-orbit/

Firefly Aerospace 将在"萤火虫二号"任务(预计 2026 年末发射)中使用英伟达 Jetson 模块处理 Ocula 月球成像数据,实现轨道端实时 AI 推理。此前"萤火虫一号"(2025 年 3 月)需下传约 120GB 原始数据,新方案大幅压缩处理延迟;Elytra 飞行器将在月球轨道运行约 5 年。

📌 **这意味着**:边缘 AI 芯片正从地面数据中心延伸至太空基础设施,为航天与国防类客户提供了星载实时推理的新参考架构。

---

### [22] AWS 助力 Outpost VFX:H100 分布式训练把模型交付周期从两周压缩至 2 天
- **来源** ｜ AWS Machine Learning Blog ｜ 2026-06-30 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://aws.amazon.com/blogs/machine-learning/how-outpost-vfx-uses-aws-to-accelerate-ai-model-training-for-visual-effects/

视觉特效公司 Outpost VFX(业务覆盖英国、加拿大、印度)与 AWS 生成式 AI 创新中心合作 6 周,将训练架构从单卡 RTX 3090 的 G5 实例迁移至搭载 H100 的 EC2 P5 实例,采用 PyTorch 分布式数据并行(DDP),训练速度提升 8 倍,单次换脸模型微调交付时间由 1-2 周缩短至 2 天。

📌 **这意味着**:多 GPU 分布式训练正成为内容生产类企业突破单卡瓶颈、缩短产品迭代周期的标准化路径,可作为同类工作负载迁移的参考案例。

---

### [23] AWS 与 IBS Software 合作:用 Bedrock 模型蒸馏构建双语货运 NER 系统,成本降低 14 倍
- **来源** ｜ AWS Machine Learning Blog ｜ 2026-06-30 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://aws.amazon.com/blogs/machine-learning/building-bilingual-ner-for-cargo-logistics-with-amazon-bedrock/

航空货运软件商 IBS Software 基于 Amazon Bedrock 的托管蒸馏功能,将 Nova Pro(教师模型)蒸馏为 Nova Lite(学生模型),用 500 封英日双语邮件标注数据训练,实现 23 种实体类型识别,F1 得分达 95.085%,运营成本降低 14 倍,蒸馏模型保留教师模型 98% 性能,单封邮件处理低于 2 秒。

📌 **这意味着**:模型蒸馏正成为企业在保证精度前提下大幅压缩推理成本的成熟路径,适合有大批量结构化文本处理需求的传统行业复制。

---

### [24] OpenAI 与博通联合发布首款定制 AI 推理芯片 Jalapeño
- **来源** ｜ OpenAI News ｜ 2026-06-25 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://openai.com/index/openai-broadcom-jalapeno-inference-chip/

OpenAI 与博通(Broadcom)联合公布双方合作研发的首款定制 AI 推理芯片"Jalapeño",专为大语言模型推理优化设计,计划于 2026 年底开始初步部署,旨在降低对英伟达 GPU 的依赖、提升推理成本效率。

📌 **这意味着**:头部 AI 厂商正加速自研推理芯片以摆脱 GPU 供应瓶颈,企业长期采购成本结构可能因此重塑,需关注其专用芯片是否对外开放租用。

---

### [25] 论文:35B 参数 Agent 模型通过扩展"决策视野"逼近万亿参数性能
- **来源** ｜ arXiv ｜ 2026-06-29 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://arxiv.org/abs/2606.30616

InternScience 团队提出 350 亿参数混合专家 Agent 模型 Agents-A1,论文主张通过扩展"Agent 决策视野"(而非堆叠参数量)逼近万亿参数级性能,基于平均约 4.5 万 token 的长程知识-动作轨迹训练,采用全域 SFT、领域级教师模型、多教师领域路由蒸馏三阶段训练,在多项基准上与 GPT-5.5、DeepSeek-V4-pro、Kimi-K2.6 等大模型表现相当。

📌 **这意味着**:中小规模 Agent 模型有望通过训练方法创新逼近旗舰模型表现,为预算有限的企业提供自部署 Agent 模型的新选项。

---

### [26] Hugging Face 推出 Every Eval Ever:汇总 2.2 万模型、22 万条评测结果的开放数据库
- **来源** ｜ Hugging Face Blog ｜ 2026-06-30 ｜ **质量分** ｜ 6/10 ｜ **链接** ｜ https://huggingface.co/blog/eee-community-evals

"Every Eval Ever"(EEE)数据库聚合约 22.9 万条评测结果,覆盖 2.2 万多个模型、2200 多个基准,来自 31 种不同上报格式,估算独立复现成本高达数十万美元。配套转换工具支持 MMLU-Pro、GPQA、HLE、GSM8K 等基准格式统一,与 EvalEval Coalition 合作,模型主页现已展示带来源标注的评测结果。

📌 **这意味着**:模型选型团队可大幅减少自建评测基础设施的重复投入,直接复用社区已验证的评测结果库进行横向对比。

---

## ━━━ 审计区 ━━━

- **主流科技媒体命中**:2/8
  - ✅ TechCrunch(3 篇)
  - ✅ Engadget(2 篇)
  - ❌ The Verge(搜索/直连均无结果)
  - ❌ Wired(窗口内无可验证 AI 文章)
  - ❌ Ars Technica(窗口内无可验证 AI 文章)
  - ❌ VentureBeat(找到候选文章但日期偏旧或与权威批重复,未采用)
  - ❌ ZDNet(无结果)
  - ❌ CNET(无结果)

- **厂商博客命中**(国际大厂 8 + 企业 SaaS 8,共 16):9/16,另有 3 个清单外厂商(Cisco、Mistral、Cohere)补充命中
  - ✅ Anthropic(1 篇,Claude Science 改用 TechCrunch 版本以避免重复计入)
  - ✅ AWS Machine Learning Blog(3 篇)
  - ✅ Microsoft Research(2 篇)
  - ✅ NVIDIA Blog(3 篇)
  - ✅ Oracle News(2 篇)
  - ✅ Salesforce News(1 篇)
  - ✅ SAP News Center(1 篇)
  - ✅ Snowflake AI Blog(1 篇)
  - ➕ Cisco AI Blog(1 篇,清单外补充)
  - ➕ Mistral AI News(1 篇,清单外补充)
  - ➕ Cohere Blog(1 篇,清单外补充)
  - ❌ OpenAI(候选文章 GPT-5.6 系列与权威批重复,改用 Broadcom 芯片合作计入基础设施)
  - ❌ Google AI / DeepMind(候选文章与昨日批次重复,未采用)
  - ❌ Meta AI(候选文章 Brain2Qwerty 与昨日批次完全重复,未采用)
  - ❌ IBM(403 屏蔽,窗口内无可验证文章)
  - ❌ ServiceNow(403 屏蔽,窗口内无可验证文章)
  - ❌ Workday(找到内容但发布日期为 6/2,过旧未采用)
  - ❌ Adobe(找到内容但发布日期为 6/18,过旧未采用)
  - ❌ Databricks(403 屏蔽,无可验证文章)

- **垂直/工程源命中**:2/5
  - ✅ Hugging Face Blog(2 篇)
  - ✅ arXiv(1 篇,摘要级)
  - ❌ InfoQ(403 屏蔽,候选文章日期无法确认在窗口内)
  - ❌ IEEE Spectrum(403 屏蔽,候选文章日期无法确认在窗口内)
  - ❌ ACM(无相关内容)

- **失败源**:The Verge、Wired、Ars Technica、ZDNet、CNET、Google AI/DeepMind(重复)、Meta AI(重复)、IBM、ServiceNow、Databricks、InfoQ、IEEE Spectrum、ACM

- **去重说明**:Meta Brain2Qwerty v2、DeepMind AI 控制路线图、DeepMind 多智能体安全基金已于 2026-06-30 批次发布,本期不再收录;GPT-5.6 系列预览、Anthropic Mythos 5 权限恢复已于权威批(batch-1)收录,本期不再重复。

- **总计**:26 篇 | 12 产品 + 8 厂商动态 + 6 基础设施
