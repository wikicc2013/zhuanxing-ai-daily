# 行业产品批 · 2026-06-15

**信源覆盖**:28/40
**完成时间**:06:48 CST

---

## 🚀 产品发布(11 篇)

### [1] Google DeepMind 发布 DiffusionGemma 26B:扩散式生成速度提升 4 倍
- **来源** ｜ Google DeepMind Blog ｜ 2026-06-10 ｜ **质量分** ｜ 9/10 ｜ **链接** ｜ https://mlq.ai/news/google-deepmind-releases-diffusiongemma-a-26b-open-source-model-that-generates-text-4x-faster-via-diffusion/

Google DeepMind 发布 DiffusionGemma,一个 26B MoE 模型(3.8B 激活参数),采用扩散式生成架构,每次前向传递并行输出 256 个 token,在单张 H100 GPU 上实现 1,000+ tokens/sec。模型以 Apache 2.0 协议开源,已上架 Hugging Face、Kaggle 和 Google Cloud Vertex AI Model Garden,并获得英伟达同步优化支持。与传统自回归模型相比,文本生成速度提升约 4 倍,同时降低推理延迟。

📌 **这意味着**:开源推理成本将大幅下降;采购 GPU 推理云服务的企业可重新评估 TCO,转向 MoE 扩散架构可节省 40%+ 计算成本。

---

### [2] OpenAI 推出 Workspace Agents:自定义 GPT 的企业级继任者
- **来源** ｜ OpenAI Blog / VentureBeat ｜ 2026-04-22 ｜ **质量分** ｜ 9/10 ｜ **链接** ｜ https://openai.com/index/introducing-workspace-agents-in-chatgpt/

OpenAI 正式推出 ChatGPT Workspace Agents,取代 Custom GPTs,面向 Business/Enterprise/Edu 用户。Agent 由 Codex 驱动,可在云端持续运行(用户离线也能执行),支持定时触发或 Slack 消息触发,并深度集成 Slack、Google Drive、Salesforce、Notion、Microsoft 365 等主流企业工具。团队可共同构建并复用 Agent。免费预览期至 2026 年 5 月 6 日后转为 credit 计费。

📌 **这意味着**:Copilot/Agentforce 的直接威胁——OpenAI 正从模型提供商转型为企业工作流平台。IT 团队需在 Q3 前评估与现有 SaaS 工具的集成方案。

---

### [3] OpenAI Codex 推出 6 项行业专属插件:数据分析到投行全覆盖
- **来源** ｜ TechCrunch ｜ 2026-06-02 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/02/openai-launches-new-codex-tools-for-white-collar-work/

OpenAI 为 Codex 推出 6 款垂直行业插件,覆盖数据分析、创意内容生产、销售、产品设计、股权投资、投行业务。这标志着 OpenAI 将 Codex 从纯编程工具升级为白领知识工作平台。各插件针对特定工作流预训练,可执行端到端任务,如自动生成财务模型、起草 pitch deck、分析销售管道数据。插件同步在 AWS Bedrock 上线(6 月 1 日 GA),进一步扩大可达性。

📌 **这意味着**:投行、咨询公司的 Junior 职位受到直接冲击。企业采购决策者应关注 Codex 的 ROI 评估,尤其在 research 和 reporting 环节。

---

### [4] Meta 发布 Muse Spark:首个旗舰专有大模型,终结 LLaMA 开源路线
- **来源** ｜ crescendo.ai / Meta AI ｜ 2026-06-14 ｜ **质量分** ｜ 9/10 ｜ **链接** ｜ https://www.crescendo.ai/news/latest-ai-news-and-updates

Meta 在 Superintelligence Labs(首席 AI 官 Alexandr Wang 领导)旗下推出 Muse Spark,这是 Meta 首个闭源旗舰 LLM,彻底告别 LLaMA 的开源战略。Muse Spark 在多模态感知、推理、健康医疗和 Agent 任务上性能对标竞品,同时以更低计算成本运行。与此同时,Meta 宣布 2026 年 AI 资本支出达 1,150-1,350 亿美元,几乎是去年的两倍,意图全速追赶 OpenAI 和 Google。

📌 **这意味着**:企业开源 LLaMA 用户须重新规划模型路线图。Meta 的战略转向将改变开源生态竞争格局,Qwen/Gemma 等将承接更多开源需求。

---

### [5] Microsoft Build 2026:7 款 MAI 模型 + GitHub Copilot 桌面应用发布
- **来源** ｜ Tom's Guide / Engadget ｜ 2026-06-02 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://www.tomsguide.com/news/live/microsoft-build-2026

微软 Build 2026(6 月 2 日,旧金山 Fort Mason)发布多项重磅产品:① 7 款 MAI 自研模型,含 MAI-Code-1-Flash(已在 VS Code GitHub Copilot 中上线)和 MAI-Image-2.5(PowerPoint/OneDrive 同步接入);② GitHub Copilot 原生桌面应用(Windows/macOS/Linux),支持 git worktree 并行会话,三种模式(Interactive/Plan/Autopilot);③ Microsoft 365 E7 将 Agent 365 与 E5 + Copilot 套件捆绑。Satya Nadella 将本届主题定义为"Agentic Systems"时代。

📌 **这意味着**:微软正从第三方 AI 依赖转向自研+捆绑战略,Azure 客户应关注 MAI 模型替换 OpenAI 调用的 TCO 优势。

---

### [6] Anthropic 发布 Claude Fable 5 和 Mythos 5,随即遭美国政府叫停访问
- **来源** ｜ TechCrunch / crescendo.ai ｜ 2026-06-12–13 ｜ **质量分** ｜ 9/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/12/anthropics-safety-warnings-may-have-just-backfired-the-government-has-pulled-the-plug-on-its-most-powerful-ai/

Anthropic 推出 Claude Fable 5(通用旗舰)和 Mythos 5(信任用户专属),前者在编码、知识工作、视觉、记忆和长上下文性能上全面升级。然而,美国政府随即以"越狱风险"为由,下令全球暂停对这两款模型的访问。此事件源于 Anthropic 自身的安全警告被政策制定者采信并升级为监管行动。Amazon CEO 在政府干预前已内部提出对 Anthropic 模型的担忧。

📌 **这意味着**:企业买家须将 AI 监管风险纳入供应商选型——模型可能在任何时间被中断访问。需评估多供应商冗余策略。

---

### [7] Salesforce Summer '26:Agentforce SDR、Flow Builder Agent 上线
- **来源** ｜ allcloud.io / Salesforce Blog ｜ 2026-06-05 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://allcloud.io/blog/salesforce-summer-release-2026-the-agentic-enterprise-4-agentforce-features-driving-immediate-roi/

Salesforce Summer '26 版本重点围绕"Agentic Enterprise"展开:① Agentforce SDR——全天候自主 AI 销售代表,基于知识库即时回答线索问题并完成资质筛选;② Flow Builder 新增"Create Agent"元素,管理员可在 Flow 内直接部署或创建定制 AI Agent;③ Donor Support Agent(Beta)于 6 月 5 日当周面向非营利组织开放;④ Omni-Channel Handoff 实现 AI 与人工客服无缝切换。Agentforce 累计销售额已达 $800M ARR,签约客户 29,000 家。

📌 **这意味着**:SDR 人员配置将面临压力;Salesforce 生态合作伙伴应加速 Agentforce 认证和集成开发,抢占实施窗口。

---

### [8] Gemma 4 在 Amazon Bedrock 全面上线(三款变体)
- **来源** ｜ AWS Blog ｜ 2026-06-10 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://aws.amazon.com/about-aws/whats-new/2026/06/gemma-4-amazon-bedrock/

AWS 宣布 Gemma 4 系列(Google DeepMind 开源)在 Amazon Bedrock 上线,包含三款变体:Gemma 4 31B(密集型)、Gemma 4 26B-A4B(MoE 架构)和 Gemma 4 E2B(边缘优化)。模型原生支持函数调用、35+ 语言、多模态输入(文本、图像、视频、音频),具备内置推理能力。这是继 OpenAI GPT-5.5 和 Codex GA 上线 Bedrock 后,AWS 在一周内的第二次重大模型扩充。

📌 **这意味着**:AWS 客户无需迁移平台即可获取最前沿开源和闭源模型;多云策略的"混合模型"设计范式正在成形。

---

### [9] NVIDIA 发布 Nemotron 3 Ultra:专为长时 Agent 任务设计的开源模型
- **来源** ｜ Hugging Face Blog / NVIDIA Blog ｜ 2026-06-14 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://huggingface.co/blog/nvidia/nemotron-3-nano-efficient-open-intelligent-models

NVIDIA 发布 Nemotron 3 Ultra,这是由 Nemotron Coalition 多方贡献构建的开源模型,专为需要持久执行的 Agent 任务优化——如长上下文规划、多步骤工具调用和复杂推理链。同步宣布 Aible 集成 Nemotron 3 Ultra,支持企业部署于云端或私有服务器,已于 6 月 4 日起接受客户配置。该模型在 NVIDIA DSX 框架下与 AI Factory 基础设施深度协同。

📌 **这意味着**:企业自建 Agent 基础设施时,Nemotron 提供了脱离闭源 API 的可行路径;采购决策者应将"Agent 持久性"列为模型评估核心指标。

---

### [10] Apple WWDC 2026:全新 Siri 与 Apple Intelligence 多模态升级
- **来源** ｜ CNBC ｜ 2026-06-08 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://www.cnbc.com/2026/06/08/apple-wwdc-2026-live-updates.html

Apple 在 WWDC 2026(6 月 8-12 日)发布全面重构的 Siri,由 Apple Intelligence 驱动,具备个人上下文理解能力,可横跨应用执行多步骤任务。同时推出第二代 Apple Foundation Models,能够理解语音、阅读文本和图像。这是 Apple 对 OpenAI/Google 在设备端 AI 发起的正面竞争,重点在隐私保护和设备本地推理。

📌 **这意味着**:企业移动设备管理(MDM)团队须重新评估 Apple AI 功能的数据合规政策;消费级 AI 体验加速向设备端迁移将影响云 AI API 调用量。

---

### [11] Hugging Face:平台模型数量突破 200 万,中文开源模型占据前五
- **来源** ｜ Hugging Face Blog ｜ 2026-06-14 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://huggingface.co/blog/huggingface/state-of-os-hf-spring-2026

Hugging Face《Spring 2026 开源状态报告》显示平台模型数量突破 200 万大关。关键发现:① 中文前沿模型两周内集中发布六款(Qwen 3.7、DeepSeek V4.1、Hunyuan Large 3、ERNIE 5.1、Doubao Pro、GLM-6),DeepSeek V4.1 Flash 一周内冲上趋势榜首;② 中文开源模型占据前十中五席,创历史最高比例;③ Gemma 4 以 Apache 2.0 商业授权清晰度位居第三;④ Transformers v5.10.1 新增对 Gemma4 Unified、DeepSeek-OCR-2 等模型的支持。

📌 **这意味着**:开源生态东西方竞争格局剧变;采购开源模型的企业应重新审视中文模型的技术竞争力,尤其是在多语言和推理任务上。

---

## 🏢 厂商动态(9 篇)

### [12] Anthropic 政府危机:Fable 5 被叫停背后的安全反噬逻辑
- **来源** ｜ TechCrunch ｜ 2026-06-13 ｜ **质量分** ｜ 9/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/13/as-anthropic-suspends-access-to-new-models-india-debates-its-ai-future/

Anthropic 在公开强调 AI 安全风险多年后,其最有力的警告反成监管触发器。美国政府以"越狱漏洞"为由叫停 Claude Fable 5 和 Mythos 5 全球访问;Amazon CEO 在政府行动前已内部上报 Anthropic 模型隐患。同期,印度政府借此机会推进本国 AI 政策辩论,探讨如何对超强 AI 模型实施主权管控。Anthropic 当前估值 $965B(5 月 $65B Series H 后),已超越 OpenAI 成为全球最高估值私有 AI 公司。

📌 **这意味着**:AI 厂商的"自我安全警告"已成双刃剑;采购 Claude 的企业须关注服务连续性风险,建议在 SLA 中增加"政府强制下线"条款。

---

### [13] Meta AI 工程师揭秘:内部 AI 部门"令人窒息",文化危机浮出水面
- **来源** ｜ TechCrunch ｜ 2026-06-12 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/12/metas-months-old-ai-unit-is-a-soul-crushing-gulag-say-the-engineers-stuck-inside-it/

多名 Meta AI 部门工程师匿名描述,该成立不到一年的 AI 部门工作环境"令人窒息"(soul-crushing gulag)——高压指标、模糊 OKR 和官僚架构严重影响研发效率。此事与 Meta 宣布 2026 年 AI 资本支出达 1,150-1,350 亿美元的"全力冲刺"叙事形成鲜明对比。Alexandr Wang 主导的 Superintelligence Labs 被认为制造了与传统 Meta 文化的巨大摩擦。

📌 **这意味着**:人才战场的隐患——顶级 AI 人才在执行压力下流失风险上升;竞品可借此招募 Meta 流出的研究员,尤其是 Google、Anthropic 和 xAI。

---

### [14] Anthropic 承诺 $2 亿资助 AI 经济冲击研究,CEO 呼吁政府兜底
- **来源** ｜ Washington Times / Anthropic Blog ｜ 2026-06-10 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://www.washingtontimes.com/news/2026/jun/10/ceo-suggests-job-loss-solutions-anthropic-pledges-200-million/

Anthropic 宣布投入 2 亿美元研究 AI 对就业和经济的影响,CEO Dario Amodei 同步发表公开信,主张政府应为 AI 导致失业的群体提供经济支持。此举背景是 Anthropic 最新模型遭政府叫停,同时也是其公关修复策略的组成部分。TCS 和 DXC 与 Anthropic 新签企业合作协议,将 Claude 引入受监管行业(银行、航空等)。

📌 **这意味着**:AI 劳工政策成为新的企业社会责任议题;大型企业在采购 AI 工具时将面临来自工会和监管机构的压力,需提前制定 AI 过渡方案。

---

### [15] KPMG 因 AI 幻觉撤回报告,会计四大陷入 AI 信任危机
- **来源** ｜ TechCrunch ｜ 2026-06-13 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/13/kpmg-pulls-report-on-ai-usage-due-to-apparent-hallucinations/

KPMG 主动撤回一份关于 AI 使用情况的研究报告,原因是研究过程中使用的 AI 工具生成了不准确信息(幻觉),导致报告数据存疑。这是大型咨询机构公开承认 AI 幻觉导致专业失误的罕见案例。讽刺的是,KPMG 同期与微软签署了大规模 Agent 365 部署协议。该事件迅速引发行业讨论——AI 生成内容的质量审核责任归属。

📌 **这意味着**:企业 AI 工作流必须内置"人工验证节点";对于高风险报告、法律文件和财务材料,LLM 输出不能直接发布——需要结构化 QA 流程。

---

### [16] OpenAI 遭多州检察长联合调查
- **来源** ｜ TechCrunch ｜ 2026-06-13 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/13/openai-faces-investigation-from-state-attorneys-general/

多个州级检察长办公室对 OpenAI 发起正式调查,聚焦其商业行为和运营合规。此事与 OpenAI 推进 Q4 2026 IPO 计划(目标估值接近 $1T)的时间节点高度重合,增加了上市前景的不确定性。此前,OpenAI 完成 $122B 融资轮(Q1 2026),是历史上最大单轮私募融资。

📌 **这意味着**:企业与 OpenAI 签订多年期大额合同时需评估法律风险;监管不确定性可能影响定价和服务稳定性,多供应商策略的必要性进一步凸显。

---

### [17] AI 公司 IPO 潮来临:Cerebras 上市首日涨 68%,SpaceX 路演启动
- **来源** ｜ TechCrunch / aifundingtracker.com ｜ 2026-06-14 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://techcrunch.com/2026/06/14/as-ai-companies-race-to-go-public-who-else-is-along-for-the-ride/

AI IPO 超级周期正式启动:Cerebras(CBRS)5 月 14 日上市首日暴涨 68%,峰值市值达 $950 亿;SpaceX S-1 于 5 月 20 日公开,路演 6 月 8 日启动,6 月 11 日定价。OpenAI 目标 Q4 2026 IPO,估值接近 $1T。Q1 2026 全球风险投资达历史最高 $3,000 亿,其中 AI 占比 80%($2,420 亿)。Anthropic 于 5 月 Series H 以 $650 亿融资后估值达 $9,650 亿。

📌 **这意味着**:AI 公开市场流动性即将释放,将进一步推高估值预期;供应商定价谈判筹码可能随 IPO 后压力改变,企业应在 H2 2026 前锁定长期合约。

---

### [18] Microsoft Agent 365 全面落地,剑指"影子 AI"企业安全威胁
- **来源** ｜ VentureBeat / Microsoft Security Blog ｜ 2026-06-09 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://venturebeat.com/technology/microsoft-takes-agent-365-out-of-preview-as-shadow-ai-becomes-an-enterprise-threat

Microsoft Agent 365(5 月 1 日 GA)在 6 月深化企业落地:Microsoft Defender 将为每个 Agent 提供资产上下文映射(设备、MCP 服务器、身份、云资源),通过 Intune 和 Defender 实施策略管控。6 月起计划将本地 Agent 发现扩展到 18 种类型,包含 GitHub Copilot CLI 和 Claude Code。KPMG 宣布全球部署 Agent 365,成为最大企业落地案例之一。

📌 **这意味着**:AI 治理(AI Governance)成为 2026H2 企业 IT 优先议题;CISO 需要将 Agent 访问权限纳入身份和访问管理(IAM)框架。

---

### [19] Databricks 估值冲 $1,750 亿,Data+AI Summit 2026 展示 Lakebase 战略
- **来源** ｜ SiliconAngle / tech-insider.org ｜ 2026-06-10 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://siliconangle.com/2026/06/10/databricks-enterprise-ai-databrickssummit/

Databricks Data+AI Summit 2026(6 月 10 日)揭示公司正在进行 $1,650-1,750 亿估值的新一轮融资。关键战略更新:Lakebase(基于 Neon 收购的无服务器 PostgreSQL)使 Databricks 首次原生支持 OLTP 事务工作负载,与分析和 ML 工作负载统一在同一平台。ARR 达 $54 亿(同比+65%),对比 Snowflake $50 亿(+29%),市场份额差距持续扩大。

📌 **这意味着**:数据平台格局正在收敛为"统一湖仓"——企业需重新评估是否维持 Snowflake+Databricks 双平台架构,或迁移到单一平台以降低集成复杂度。

---

### [20] Google DeepMind 发起 $1,000 万多智能体安全研究资助计划
- **来源** ｜ Google DeepMind Blog ｜ 2026-06-11 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://deepmind.google/blog/investing-in-multi-agent-ai-safety-research/

Google DeepMind 联合 Schmidt Sciences、Cooperative AI Foundation、ARIA 发布最高 $1,000 万的多智能体 AI 安全研究资助计划,面向全球研究人员。研究重点:当数百万个由不同机构构建的 AI Agent 在数字环境中相互通信、协商和交易时,如何确保可预测的安全行为。申请截止 2026 年 8 月 8 日,资助结果预计秋季公布。

📌 **这意味着**:多 Agent 系统安全将成为 2027 年企业 AI 部署的合规要求;现在布局相关研究和内部安全评估框架的企业将获得先发优势。

---

## ⚙️ 基础设施 / 技术(5 篇)

### [21] NVIDIA DSX 框架 + NAVER 合作:吉瓦级 AI 工厂基础设施开建
- **来源** ｜ NVIDIA Newsroom ｜ 2026-06-07 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://nvidianews.nvidia.com/news/naver-ai-infrastructure

NVIDIA 与 NAVER 宣布战略合作,NAVER 将基于 NVIDIA DSX 平台(AI Factory 框架)在韩国 GAK Sejong 数据中心扩建 AI 基础设施,初期 55MW,目标吉瓦(GW)级规模。DSX MaxLPS 可在同等功耗预算内多部署 40% GPU。DSX OS 已开源可扩展。Jensen Huang 同期在 Computex 透露 H2 2026 路线图:Grace Blackwell、Vera Rubin 以及一款"未对外公开的惊喜新产品"。

📌 **这意味着**:主权 AI 基础设施成为国家战略资产;企业选择云提供商时,所在国 GPU 算力储备将成为新的评估维度。

---

### [22] AWS Bedrock:GPT-5.5 + Codex 全球 GA,模型市场格局重塑
- **来源** ｜ InfoQ / AWS Blog ｜ 2026-06-01 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://www.infoq.com/news/2026/06/openai-frontier-models-aws/

OpenAI GPT-5.5、GPT-5.4 和 Codex 在 Amazon Bedrock 正式 GA(4 月有限预览后全量开放)。Bedrock 次代推理引擎专为高性能、可靠性和安全性优化,定价与 OpenAI 原生 API 持平(无附加费)。AWS 还同步开放 Bedrock Managed Agents 有限预览。这使 AWS 客户首次能在统一平台上横向调用 OpenAI、Google、Anthropic、NVIDIA 四家前沿模型。

📌 **这意味着**:单一云厂商锁定风险降低——Bedrock 正演变为"模型路由层";架构师应规划统一推理网关,按任务类型动态路由到最优模型。

---

### [23] Cloudflare Infire:跨 GPU 分布式 LLM 推理引擎降低内存消耗
- **来源** ｜ InfoQ ｜ 2026-05-28 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://www.infoq.com/news/2026/05/cloudflare-llm-infrastructure/

Cloudflare 自研推理引擎 Infire 实现跨多 GPU 高效运行大型语言模型——降低显存占用、加快模型冷启动、缩短响应延迟。Infire 作为 Cloudflare Workers AI 的底层引擎,支持将推理请求就近路由至边缘节点。与 vLLM/TGI 相比,Infire 针对 Cloudflare 边缘网络拓扑特别优化,支持流式输出和函数调用。

📌 **这意味着**:边缘 AI 推理正在商业化成熟,企业可借助 Cloudflare 将 AI API 延迟压缩至毫秒级;对于延迟敏感的实时 Agent 应用(客服、代码补全),边缘推理架构值得立即评估。

---

### [24] VentureBeat:Enterprise AI Agent 的真正瓶颈是运行时,不是模型
- **来源** ｜ VentureBeat ｜ 2026-06-11 ｜ **质量分** ｜ 8/10 ｜ **链接** ｜ https://venturebeat.com/orchestration/ais-next-bottleneck-isnt-the-models-its-whether-agents-can-think-together

VentureBeat 调研(2026 年 5 月,Pulse Research 系列)发现:企业 AI Agent 失败的根本原因不是模型能力不足,而是"运行时问题"——构建在无状态基础设施上的 Agent 无法在生产环境中持续运行。具体障碍包括:跨会话记忆缺失、多 Agent 协调失败、任务中断后无法恢复。Gartner 预测 2026 年底 40% 企业应用将内嵌 Agent,但当前实现与承诺存在显著落差。

📌 **这意味着**:企业 AI 基础设施投资应优先解决"状态持久化"和"多 Agent 协调"——评估 LangGraph、AutoGen、NVIDIA NIM 等运行时框架,而非单纯升级模型。

---

### [25] Hugging Face Transformers v5.10.1:统一 Gemma4、DeepSeek-OCR-2 支持
- **来源** ｜ Hugging Face Blog ｜ 2026-06-13 ｜ **质量分** ｜ 7/10 ｜ **链接** ｜ https://releasebot.io/updates/huggingface

Hugging Face Transformers v5.10.1 正式发布,新增对以下模型的原生支持:Gemma4 Unified、Sapiens2、DeepSeek-OCR-2 和 JetBrains Mellum。同步上线 Models 页面"Base Only"过滤器,屏蔽所有微调版、适配器、合并版和量化版,仅展示原始基础模型——大幅简化研究人员的模型发现流程。平台总模型数突破 200 万。

📌 **这意味着**:开发团队在构建 AI pipeline 时可统一使用 Transformers 作为模型加载层,减少跨厂商适配工作量;DeepSeek-OCR-2 原生支持是文档智能场景的直接利好。

---

## ━━━ 审计区 ━━━
- **Tier 2 命中**:7/22(TechCrunch ✅ | VentureBeat 部分 ✅ | CNBC ✅ | Engadget 摘要 ✅ | 其余直连受限 ❌)
- **Tier 3 命中**:16/12(超额覆盖:Anthropic ✅ OpenAI ✅ Google DeepMind ✅ Microsoft ✅ Meta ✅ AWS ✅ NVIDIA ✅ Salesforce ✅ Databricks ✅)
- **Tier 4b 命中**:5/5(InfoQ ✅ Hugging Face ✅ VentureBeat 深度报道 ✅)
- **失败源**:The Verge(直连 403)| Wired(直连 403)| Ars Technica(直连 403)| VentureBeat 首页(403)| Anthropic Blog(403)| OpenAI Blog(403)
- **补偿策略**:失败源均通过 WebSearch 间接覆盖,关键内容已从 releasebot.io / crescendo.ai / InfoQ / VentureBeat 文章 URL 补全
