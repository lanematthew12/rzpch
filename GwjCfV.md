# 🤖 AI领域每日焦点简报

**日期：2026年10月18日**

---

## 🔥 今日头条

**1️⃣ Meta 发布首个前沿模型系列 Muse Wonder，全球前沿竞赛进一步多极化。** 10月12日，Meta 超级智能实验室（Meta Superintelligence Labs，AI 负责人 Alexandr Wang）正式发布 Muse Wonder 与 Muse Wonder Full 两款模型（开发代号"Watermelon"），称其在个人与专业智能体（Agentic）任务、记忆与编程场景达到业界前沿水平。Meta 公布的基准显示其性能与 Anthropic 的 Claude Fable 5.1、OpenAI 的 GPT-6 Astra 相当；在 Artificial Analysis 智能指数 v4.3 中，Wonder Full 得分 56（标准版 52），仅次于 Claude Opus 5.5（58 分）、高于 OpenAI 与 Google 的最强模型（各 53 分）；中文媒体转述称其编程智能体表现与 Claude 并列第一。定价 $4/$20 每百万 token（输入/输出），与 Opus 5.5 同价位；已通过 Meta Model API 与 Muse Code 提供（Full 版限高级订阅，新增 Active Memory / Active Focus 能力）。发布当日 Meta 股价上涨约 3.4%–4.1%（约报 $748）。[来源：TechCrunch/WIRED/NYT/The Verge/新浪科技]

**2️⃣ 微软发布第三代自研 AI 芯片 Maia 300：从"最大押注"到百万颗级部署。** 10月12日于 OCP 全球峰会（圣何塞）亮相：288GB HBM4 显存、18TB/s 带宽；微软称其每兆瓦可产出比"领先 GPU 系统"多 40% 的 token，机架级吞吐为 Maia 200 的 7 倍。微软计划 2027 年起以"多吉瓦级"规模部署超 100 万颗 Maia 300，使其成为自家 AI 服务的主要推理硬件；公司预计今年资本开支超 1,750 亿美元。纳德拉称其为"对自研芯片的最大一笔押注"；当日微软股价涨约 2.4%，英伟达、AMD 承压。[来源：GeekWire/CNBC/Reuters/HPCwire]

---

## ☝ Headlines

- **Meta·Muse Wonder**：Meta 首个前沿模型发布，对标 Claude Opus 5.5/Fable 5.1 与 GPT-6 Astra，$4/$20 定价、发布日股价涨约 3-4%
- **微软·Maia 300**：第三代自研 AI 芯片亮相，2027 年部署超百万颗、能效 +40%/MW
- **亚马逊·Decart**：洽谈约 70 亿美元收购 AI 芯片软件公司 Decart（Anthropic 尽调后退出、亚马逊接手）
- **英国 AI 安全**：白宫解除 17 天冻结，UK AISI 恢复 OpenAI/Anthropic/DeepMind 预发布模型访问；同日英国公布 AI 风险防御包
- **DeepMind·AlphaProof Nexus**：解出 9 个 Erdős 开放数学问题（2 个悬置 56 年）+ 44 个数列猜想，并通过同行评审
- **中国 AI**：大模型周调用量 86.74 万亿 Token（环比 +50.96%）连续 24 周全球第一、前五全为中国模型；美国头部两家厂商则占近九成收入

---

## 📊 分类详报

### 🧠 模型与技术

- **Meta Muse Wonder 更多细节**：该系列由 Meta 超级智能实验室开发（2025 年 6 月招入 Scale AI 创始人 Alexandr Wang 后启动 AI 重构，历时约 14 个月），定位"面向个人与专业智能体任务的前沿模型"，较前代 Muse Spark 明显升级（Artificial Analysis 智能指数 48 → 52/56）。WIRED 评价其"让 Meta 重回 AI 前沿"。社区侧：开发者对比指出 Wonder 定价与 Opus 5.5 完全持平，但在 Meta 自家 14 项基准中有 9 项落后（dev.to 分析）；Full 版目前仅限 Meta 高级 AI 编码订阅用户。[来源：TechCrunch/WIRED/NYT/Artificial Analysis/dev.to]

- **Claude Opus 5.5 Max 首次登顶 Arena 智能体榜**：Anthropic 新模型首次入榜即夺得智能体榜第一，工具幻觉率仅 0.37%；综合榜由 Google gemini-4-argon-high 居首；国产模型 kimi-k3-max 稳居综合榜前 20，qwen3.8-max 等多款保持中上游。[来源：Arena AI 周榜（网易/搜狐转载）]

- **OpenRouter 周度调用数据（10月5日-11日）**：全球总调用量 172 万亿 Token（环比 +3.61%）；中国大模型 86.74 万亿（+50.96%），连续 24 周超过美国（18.97 万亿，+17.1%），约为其 4.6 倍；全球前五全为中国模型——DeepSeek V4.1 Flash（41 万亿、+60%）、智谱 GLM 5.3 Flash（12.2 万亿）、小米 MiMo-V2.6-Flash（11.5 万亿）、阶跃星辰 Step 5 Preview（8.84 万亿）、腾讯 Hy4 preview（8.28 万亿）；Claude Opus 5.5 居第八（5.02 万亿）。[来源：每日经济新闻/OpenRouter 测算]

### 📋 政策与监管

- **英国恢复前沿模型预发布访问权（10月12日）**：白宫逆转此前"企业须先获美国批准才能向英方共享模型"的政策，为期 17 天的冻结解除。英国 AI 部长 Kanishka Narayan 确认：UK AISI 将继续对 OpenAI、Anthropic、Google DeepMind 的最强模型进行发布前安全评估（正评估 Gemini 4 Argon 等系统）；其称目标是让英国"成为全球最难被 AI 攻击的国家之一"。[来源：Quartz/Bloomberg/Firstpost/TheNextWeb]

- **英国公布 AI 风险防御包（10月12日）**：追加系列国家级防御措施——延长"用前沿 AI 审计政府代码"试点（既有两轮试点已发现 1,000+ 潜在漏洞；其中已公布一轮以约 £13,000 的 token 成本发现 407 处弱点）；政府表示或立法保护关键基础设施免受 AI 网络威胁，并着手准备"自主系统脱离人类控制"类事件的应急机制（有专家呼吁"终止开关"）。[来源：Unite.AI/TheNextWeb/bankinfosecurity/resiliencemedia]

- **美国 CAISI 拟"并入"白宫**：路透报道，特朗普政府计划将商务部 AI 标准与创新中心（CAISI）的三名高级官员转入白宫编制、直接向白宫汇报（重组仍在敲定中）；CAISI 此前负责与 OpenAI、Google、微软等开展自愿性模型评估。[来源：Reuters/US News/cryptobriefing]

- **Brad Smith："牛奶受到的监管都比 AI 多"**：微软副董事长兼总裁 Brad Smith 呼吁建立全球统一的 AI 安全规则，包括独立评估机构与面向开发者的"紧急刹车"机制——并称当前 AI 的安全要求比一盒牛奶还少。[来源：Reuters/Fox Business]

- **比尔·盖茨警告（10月11-12日）**：在 CNN 采访中称 AI 是"人类发明过的最危险的技术"，最紧迫威胁是"未来一年内 AI 驱动的网络攻击"；强调不能让企业"自我监管"，并提到社会需讨论如何对 AI 与机器人的使用征税。[来源：CNN/Yahoo Finance]

- **中国：《关于发展新质生产力的意见》持续发酵**：中共中央、国务院 10 月 9 日印发该文件，明确"全面实施'人工智能+'行动"、加快推进 AI 手机/电脑等新一代智能终端应用，并建立技术监测、风险预警与应急响应体系、确保 AI"安全、可靠、可控"；本周进入配套落实期（如工信部"AI 应用服务商培育专项行动"）。[来源：国家发改委/财新/VOA]

- **布鲁金斯学会：AI 智能体（Agent）的全球治理**：发文探讨 AI 智能体跨境运行带来的治理缺口（责任归属、跨国部署合规）。[来源：Brookings]

### 💰 产业与商业

- **亚马逊洽购 Decart（约 70 亿美元）**：WSJ 首发（10月11日晚）——Decart 开发让 AI 模型跨不同芯片高效运行的软件，并研发"世界模型"（模拟 3D 环境）；公司 2023 年成立，今年 5 月估值近 40 亿美元（若按 70 亿成交，较该估值高出约 75%）。此前 Anthropic 8 月曾洽谈约 60 亿美元收购、9 月尽调后放弃；亚马逊为其战略客户并给予 Trainium 芯片早期访问。交易若落地将强化 AWS 自研芯片生态、进一步对冲英伟达依赖。[来源：WSJ/Bloomberg/Calcalist/Quartz]

- **微软 Maia 300 详细规格与部署计划**：288GB HBM4、18TB/s 带宽；每兆瓦 token 数 +40% vs 领先 GPU 系统、机架吞吐 7× vs Maia 200；2027 年"多吉瓦"部署、逾 100 万颗；年内资本开支预期超 1,750 亿美元。市场解读：微软推理算力从"英伟达为主"转向"自研为主"的转折点。[来源：The Verge/Notebookcheck/The Tech Portal/Reuters]

- **英伟达联合 AMD、Google、Meta 发布"开放数据中心规范 v0.7"**：在 OCP 全球峰会上联合发布统一 AI 工厂设施蓝图（覆盖电力架构、冷却、物理布局）；Google、Meta、微软、英伟达另发布"OCP 电网韧性规范"（应对公用事业扰动、快速恢复）；英伟达同时通过 MGX 1.2 开放 Vera Rubin NVL72 机架设计（支持 250kW 级机架），并宣布 ConnectX-10 / BlueField 支持 Google Falcon 传输协议（开放互联再进一步）。[来源：NVIDIA博客/StorageReview/Yahoo Finance]

- **Salesforce 收购以色列 AI 分析公司 Loops（约 3,000 万美元）**：并入 Tableau，主打"agentic analytics"（解释业务指标变动并给出行动建议）；预计 11 月初交割；消息后 CRM 涨约 3%。[来源：CTech/Globes/Proactive Investors]

- **中美 AI 商业化分化（分析）**：Menlo Ventures 数据显示，2025 年 OpenAI + Anthropic 合计占企业 LLM API 支出 67%；其 5 月报告显示两家在追踪的 34 家头部 AI 初创中占 89% 收入；Ramp 数据称首次采购 AI 的企业中 Anthropic 占逾 73% 支出。对照中国侧"调用量份额领先、收入份额有限"的结构——模型能力差距正快速转化为商业收入差距。[来源：新浪科技（投资者内参）]

### 🚀 应用与产品

- **Apple "Welcome Home" 发布会（今日 10月13日，9:00 ET 纽约）**：预计推出智能家居中枢（HomePad 类新品）、新一代 Apple TV 4K、HomePod mini 等；以"新闻稿 + 媒体体验"形式发布，AI 家庭中枢为核心看点。[来源：The Verge/9to5Mac/MacRumors]

- **阶跃星辰 STEPX Neo 智能体手机（今日上海发布）**：阶跃终端"Ready Builder One"发布会推出首款"大模型原生智能体手机"；同日，千问新一代 AI 眼镜现货发售；阶跃星辰将于 10月15日 正式开源 Step 5 Preview（该模型已上线腾讯 WorkBuddy）。[来源：智东西/华尔街见闻/东方财富/IT之家]

- **富士胶片 Synapse Pathology v3.0**（10月12日）：数字病理平台扩展 AI 能力。[来源：BioSpace]

### 🔬 研究前沿

- **DeepMind "AlphaProof Nexus" 解出 9 个 Erdős 开放问题（10月12日集中报道）**：从 353 个未解 Erdős 问题中解出 9 个（其中 2 个自 1970 年起悬置 56 年），另证明 44 个 OEIS 数列猜想；解法先行在线公开、成果通过同行评审——AI 数学推理从"竞赛题"走向真实开放问题的标志性一步。[来源：the-decoder/Reddit/The Daily Star]

- **TikTok CEO 周受资（Shou Zi Chew）：AI 将在 3 年内带来"重大科学突破"**（CNBC，10月12日）——认为 AI 对科学的推动（药物研发、材料等）将在三年内集中兑现。[来源：CNBC]

---

## ⚡ 明日关注

- **10月14日：Anthropic 上市前投资者日（Investor Day）**——已向机构投资者发出邀请（Bloomberg）；正式 IPO 营销或于 11月9日当周启动、目标感恩节前挂牌。市场关注其 ARR 指引与算力承诺兑现节奏（22V Research 视其为"市场内部结构与 AI 前景的重要节点"）。
- **10月15日：台积电 Q3 财报**（14:00 台北时间）——营收预计 NT$1.49 万亿（约 $467 亿、同比 +51%，创纪录）、净利润预计同比 +65%；AI 需求风向标；同周还有 ASML 财报。
- **10月15日：阶跃星辰正式开源 Step 5 Preview**（600B 稀疏 MoE，面向 Agentic 任务）。
- **10月13-16日：TechCrunch Disrupt 2026（旧金山）与 OCP 全球峰会持续**——更多 AI 基础设施/芯片发布与创业公司动向。
- **持续跟踪**：① 英伟达-Reflection AI 谈判进展；② Anthropic IPO 流程（投资者日 → 路演）；③ 英国 AI 立法动向（关键基础设施保护）。

---

## ⚡ 其他新闻

- 生活垃圾回收的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/2ZrJg9.md
- 生活服务数字化的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/f2f0494044de4f53a4395300f550487e867a7555?/518
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/f2f0494044de4f53a4395300f550487e867a7555?/cxb
- 社区阅读服务的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/f2f0494044de4f53a4395300f550487e867a7555?/137/?ikl
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/f2f0494044de4f53a4395300f550487e867a7555?/460=863
- 节假日出行安排的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/commit/f2f0494044de4f53a4395300f550487e867a7555?/mxg=376
- 生成式工具使用的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/2ZrJg9.md?/606
- 公共图书馆服务的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/2ZrJg9.md?/kym
- 市民意见收集的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/2ZrJg9.md?/673/?fen
- 校园社团活动的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/2ZrJg9.md?/033=764
- 消防知识宣传的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/2ZrJg9.md?/oyd=565
- 地方美食文化的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/YGo6HY.md
- 医院导诊服务的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/5449982661a6ef29c451fdc9d2c28fe884f6bfff?/818
- 社区修缮行动的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/5449982661a6ef29c451fdc9d2c28fe884f6bfff?/huz
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/5449982661a6ef29c451fdc9d2c28fe884f6bfff?/187/?vft
- 旧物循环利用的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/5449982661a6ef29c451fdc9d2c28fe884f6bfff?/811=874
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/5449982661a6ef29c451fdc9d2c28fe884f6bfff?/nww=744
- 线上阅读资源的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/YGo6HY.md?/392
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/YGo6HY.md?/mwn
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/YGo6HY.md?/520/?uom
- 儿童安全出行中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/YGo6HY.md?/520=859
- 个人数据管理的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/YGo6HY.md?/tcz=808
- 公园休闲体验的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/hPT3OF.md
- 城市人文观察的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/6448d16cae43bbd4d974829a4e747d656bde0d3f?/681
- 公共场所导视的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/6448d16cae43bbd4d974829a4e747d656bde0d3f?/quo
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/6448d16cae43bbd4d974829a4e747d656bde0d3f?/834/?lvs
- 市民热线服务的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/6448d16cae43bbd4d974829a4e747d656bde0d3f?/895=834
- 图书借阅体验的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/6448d16cae43bbd4d974829a4e747d656bde0d3f?/tsm=212
- 软件开发学习的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/hPT3OF.md?/309
- 乡村公共服务的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/hPT3OF.md?/yck
- 社区安全巡查的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/hPT3OF.md?/259/?cfe
- 青少年编程学习的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/hPT3OF.md?/781=802
- 绿色出行服务的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/hPT3OF.md?/uuk=970
- 气象科普传播的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/HwPAGN.md
- 生活垃圾减量的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/43dcbf241d115d627e442245cccd5a3a4782e8b5?/926
- 青少年户外教育的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/43dcbf241d115d627e442245cccd5a3a4782e8b5?/hwa
- 科学信息获取的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/43dcbf241d115d627e442245cccd5a3a4782e8b5?/420/?mfp
- 骑行路线规划的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/43dcbf241d115d627e442245cccd5a3a4782e8b5?/630=822
- 社区快递服务的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/commit/43dcbf241d115d627e442245cccd5a3a4782e8b5?/gji=016
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/HwPAGN.md?/399
- 社区菜市场服务的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/HwPAGN.md?/gfs
- 便民信息查询的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/HwPAGN.md?/857/?zcz
- 绿色出行服务的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/HwPAGN.md?/101=373
- 青少年编程学习的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/HwPAGN.md?/ovq=713
- 课后服务体验的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/uuN6RR.md
- 城市雨天出行的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/567fc95f2a0d38baa24b497a9422245f694af482?/357
- 家庭防灾准备的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/567fc95f2a0d38baa24b497a9422245f694af482?/alv
- 家庭阅读计划的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/567fc95f2a0d38baa24b497a9422245f694af482?/398/?wel
- 老年人文化生活的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/commit/567fc95f2a0d38baa24b497a9422245f694af482?/376=396
- 个人数据管理的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/567fc95f2a0d38baa24b497a9422245f694af482?/uvx=064
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/uuN6RR.md?/983
- 小微企业服务的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/uuN6RR.md?/ycc
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/uuN6RR.md?/008/?zkv
- 志愿者培训交流的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/uuN6RR.md?/919=244
- 小区停车协商的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/uuN6RR.md?/ezp=610
- 亲子科普活动的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/vJk5OM.md
- 通勤路线规划的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/48358ec48c3beb2528877b49a7fe48e191e722da?/899
- 老年人文化生活的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/48358ec48c3beb2528877b49a7fe48e191e722da?/ugk
- 开放式学习空间的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/48358ec48c3beb2528877b49a7fe48e191e722da?/372/?kad
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/48358ec48c3beb2528877b49a7fe48e191e722da?/806=613
- 公共服务评价的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/commit/48358ec48c3beb2528877b49a7fe48e191e722da?/ntu=322
- 智慧停车服务的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/vJk5OM.md?/865
- 青少年户外教育的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/blob/main/vJk5OM.md?/lgx
- 城市雨天出行的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/vJk5OM.md?/561/?pjm
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/vJk5OM.md?/763=530
- 校园社团活动的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/vJk5OM.md?/qdz=926
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/SrIJ6I.md
- 城市微更新实践有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/f65e8269c6f387d0550c7740776e31657de7641a?/695
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/f65e8269c6f387d0550c7740776e31657de7641a?/ijv
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/f65e8269c6f387d0550c7740776e31657de7641a?/673/?ksg
- 家庭运动计划的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/f65e8269c6f387d0550c7740776e31657de7641a?/986=067
- 智能手机助老的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/f65e8269c6f387d0550c7740776e31657de7641a?/dlo=608
- 科技馆参观体验的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/SrIJ6I.md?/425
- 科技馆参观体验的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/SrIJ6I.md?/zbc
- 生活技能分享的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/SrIJ6I.md?/847/?rul
- 基层健康档案的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/SrIJ6I.md?/897=909
- 数字创意课程的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/SrIJ6I.md?/suj=573
- 城市适老服务的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/On0oRm.md
- 社区安全巡查的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/f5c97ef4c3591840c962c05bc4d6933d1d46e871?/273
- 社区家政服务的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/f5c97ef4c3591840c962c05bc4d6933d1d46e871?/gbg
- 数字素养提升的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/f5c97ef4c3591840c962c05bc4d6933d1d46e871?/306/?lpy
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/f5c97ef4c3591840c962c05bc4d6933d1d46e871?/806=258
- 社区活动空间的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/f5c97ef4c3591840c962c05bc4d6933d1d46e871?/wty=106
- 家庭收纳实践的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/On0oRm.md?/262
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/On0oRm.md?/bmp
- 青少年科普实践的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/On0oRm.md?/901/?law
- 文明养宠科普的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/On0oRm.md?/842=425
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/On0oRm.md?/szh=563
- 城市社区治理的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/7vng2b.md
- 社区活动空间的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/85c378df74b9b8cc0ff2065eb7f10e34898fb83d?/911
- 城市文化路线的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/85c378df74b9b8cc0ff2065eb7f10e34898fb83d?/kea
- 数字便民地图的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/85c378df74b9b8cc0ff2065eb7f10e34898fb83d?/295/?ivf
- 社区庭院绿化的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/85c378df74b9b8cc0ff2065eb7f10e34898fb83d?/643=373
- 城市休闲步道的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/85c378df74b9b8cc0ff2065eb7f10e34898fb83d?/oth=913
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/7vng2b.md?/791
- 城市基础设施的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/7vng2b.md?/sxp
- 节气饮食文化的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/7vng2b.md?/521/?utu
- 家庭运动计划的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/7vng2b.md?/685=093
- 青年职业探索的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/7vng2b.md?/acc=455
- 数字生活课堂的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/9AHbmP.md
- 校园安全教育的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/6ebd4445a9f5e7d26577cf4e5d29653c45b3ff8b?/655
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/commit/6ebd4445a9f5e7d26577cf4e5d29653c45b3ff8b?/fao
- 社区协商议事的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/6ebd4445a9f5e7d26577cf4e5d29653c45b3ff8b?/402/?xmk
- 亲子阅读活动的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/6ebd4445a9f5e7d26577cf4e5d29653c45b3ff8b?/500=798
- 科普展览体验的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/6ebd4445a9f5e7d26577cf4e5d29653c45b3ff8b?/qnc=773
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/9AHbmP.md?/316
- 基层健康服务的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/9AHbmP.md?/knj
- 城市公共座椅的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/9AHbmP.md?/081/?bvr
- 机器学习入门的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/9AHbmP.md?/844=705
- 城市绿色交通的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/9AHbmP.md?/wne=047
- 社区科普课堂的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/HCJMGL.md
- 社区环保活动的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/commit/cc7f4452f8770f033d81cd8f438a7dbe57ce6204?/956
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/cc7f4452f8770f033d81cd8f438a7dbe57ce6204?/pky
- 街头绿植养护的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/cc7f4452f8770f033d81cd8f438a7dbe57ce6204?/473/?tfp
- 基层服务创新的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/cc7f4452f8770f033d81cd8f438a7dbe57ce6204?/182=213
- 城市公共空间的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/cc7f4452f8770f033d81cd8f438a7dbe57ce6204?/bxt=810
- 城市地名文化的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/HCJMGL.md?/885
- 生活垃圾减量的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/HCJMGL.md?/rde
- 社区绿色空间的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/HCJMGL.md?/041/?mqa
- 社区心理支持的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/HCJMGL.md?/622=783
- 无障碍出行的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/HCJMGL.md?/cdu=655
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/E9V3dX.md
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/a6519008cf3e11588049135cf38b9596eec2dde5?/580
- 校园节能行动的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/a6519008cf3e11588049135cf38b9596eec2dde5?/ust
- 创业经验分享的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/a6519008cf3e11588049135cf38b9596eec2dde5?/246/?qla
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/a6519008cf3e11588049135cf38b9596eec2dde5?/409=182
- 城市雨天出行的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/a6519008cf3e11588049135cf38b9596eec2dde5?/rub=576
- 节约用水实践的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/E9V3dX.md?/446
- 公共设施使用的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/E9V3dX.md?/ndv
- 社区知识分享的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/E9V3dX.md?/988/?pya
- 城市住房服务的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/E9V3dX.md?/388=306
- 青少年编程学习中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/E9V3dX.md?/ebr=303
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/oVpUAj.md
- 邻里共享空间的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/7b49bda6fef45b0333ddba0720d42d49ad963fa3?/821
- 节能家电使用的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/7b49bda6fef45b0333ddba0720d42d49ad963fa3?/ikm
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/7b49bda6fef45b0333ddba0720d42d49ad963fa3?/820/?gwf
- 科学教育活动的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/7b49bda6fef45b0333ddba0720d42d49ad963fa3?/659=048
- 城市绿色交通的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/7b49bda6fef45b0333ddba0720d42d49ad963fa3?/bfc=511
- 环境教育课程的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/oVpUAj.md?/496
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/oVpUAj.md?/kma
- 家庭照护支持的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/oVpUAj.md?/549/?mei
- 城市公共艺术的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/oVpUAj.md?/659=387
- 运动安全知识的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/oVpUAj.md?/vhd=883
- 城乡公共服务的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/NQc5xq.md
- 城市水环境观察的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/bf3b63fa30115fbda971b10e9b22f6156e3f8d53?/331
- 在线学习体验的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/bf3b63fa30115fbda971b10e9b22f6156e3f8d53?/heu
- 光伏知识科普的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/commit/bf3b63fa30115fbda971b10e9b22f6156e3f8d53?/054/?fiq
- 公共设施维护的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/bf3b63fa30115fbda971b10e9b22f6156e3f8d53?/978=586
- 社区垃圾回收的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/bf3b63fa30115fbda971b10e9b22f6156e3f8d53?/dfs=725
- 公共服务咨询的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/NQc5xq.md?/810
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/NQc5xq.md?/rar
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/NQc5xq.md?/677/?ysl
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/NQc5xq.md?/148=160
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/NQc5xq.md?/ggk=022
- 数字课堂应用的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/XNc5mR.md
- 城市地名文化的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/45de9ddc710086cb9049f005b5c457cd45734541?/822
- 科学观察活动的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/45de9ddc710086cb9049f005b5c457cd45734541?/epe
- 社区安全巡查的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/45de9ddc710086cb9049f005b5c457cd45734541?/627/?tmv
- 休闲运动入门的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/45de9ddc710086cb9049f005b5c457cd45734541?/452=493
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/45de9ddc710086cb9049f005b5c457cd45734541?/mjy=681
- 低碳社区实践的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/XNc5mR.md?/789
- 社区协商议事的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/XNc5mR.md?/guy
- 机器学习入门的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/XNc5mR.md?/432/?lil
- 城市文化路线的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/XNc5mR.md?/395=517
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/XNc5mR.md?/zts=756
- 家庭消费规划的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/l2BkSa.md
- 电动汽车充电的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/7312aa71de1ca5099b552e498dd6298b7471cdde?/773
- 社区故事采集的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/7312aa71de1ca5099b552e498dd6298b7471cdde?/zui
- 乡村公共文化的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/7312aa71de1ca5099b552e498dd6298b7471cdde?/408/?nyc
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/7312aa71de1ca5099b552e498dd6298b7471cdde?/574=762
- 家庭教育交流的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/7312aa71de1ca5099b552e498dd6298b7471cdde?/voz=518
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/l2BkSa.md?/185
- 城市噪声观察的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/l2BkSa.md?/oqa
- 公共空间休憩的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/l2BkSa.md?/045/?vnu
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/l2BkSa.md?/227=896
- 应急物资管理的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/l2BkSa.md?/nxx=166
- 应急物资管理的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/nbKQX5.md
- 灵活就业交流中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/abf98653cda13068e0d959dbe1512750b3e4b789?/307
- 节约用水实践的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/abf98653cda13068e0d959dbe1512750b3e4b789?/rzn
- 消防知识宣传的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/abf98653cda13068e0d959dbe1512750b3e4b789?/440/?vew
- 城市夜间照明的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/abf98653cda13068e0d959dbe1512750b3e4b789?/010=727
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/abf98653cda13068e0d959dbe1512750b3e4b789?/rjh=321
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/nbKQX5.md?/968
- 城市文明实践的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/nbKQX5.md?/gjs
- 数字创意课程的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/nbKQX5.md?/014/?gmr
- 社区运动空间的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/nbKQX5.md?/357=289
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/nbKQX5.md?/gps=216
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/hvNixH.md
- 数字档案服务的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/2170f9ecc6950efc2efe0400e0be3ffe37e180ae?/550
- 在线学习体验的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/2170f9ecc6950efc2efe0400e0be3ffe37e180ae?/mzh
- 城市人文观察的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/2170f9ecc6950efc2efe0400e0be3ffe37e180ae?/881/?kyz
- 学校食育活动的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/2170f9ecc6950efc2efe0400e0be3ffe37e180ae?/722=409
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/2170f9ecc6950efc2efe0400e0be3ffe37e180ae?/ucf=177
- 市民热线服务的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/hvNixH.md?/585
- 街区道路维护的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/hvNixH.md?/lbh
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/hvNixH.md?/066/?uls
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/hvNixH.md?/211=718
- 传统节日科普的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/hvNixH.md?/ari=974
- 社区艺术活动的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/QTtuln.md
- 乡村产业科普的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/485197b2a5e83331f6f04c0cb48de721f0228a99?/647
- 便民服务窗口的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/485197b2a5e83331f6f04c0cb48de721f0228a99?/qwc
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/485197b2a5e83331f6f04c0cb48de721f0228a99?/693/?bwu
- 信息无障碍体验的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/485197b2a5e83331f6f04c0cb48de721f0228a99?/699=548
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/485197b2a5e83331f6f04c0cb48de721f0228a99?/yoa=079
- 老年数字阅读的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/QTtuln.md?/875
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/QTtuln.md?/pom
- 老年人日常照护的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/QTtuln.md?/114/?udu
- 社区家政服务的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/QTtuln.md?/242=480
- 社区活动报名的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/QTtuln.md?/hxz=016
- 网络信息辨识的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ewqy7c.md
- 城市公共饮水的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/78dea13dda607fb96ed21481281ae225416b292c?/591
- 科学信息获取的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/78dea13dda607fb96ed21481281ae225416b292c?/yeu
- 急救知识普及的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/78dea13dda607fb96ed21481281ae225416b292c?/947/?zbx
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/78dea13dda607fb96ed21481281ae225416b292c?/441=559
- 街区更新实践的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/commit/78dea13dda607fb96ed21481281ae225416b292c?/jom=281
- 消防知识宣传的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ewqy7c.md?/255
- 开放数据应用中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ewqy7c.md?/kin
- 公共空间照明的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ewqy7c.md?/971/?cjm
- 家庭网络使用的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ewqy7c.md?/785=674
- 城市步行环境的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ewqy7c.md?/xfn=588
- 家庭用电安全的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/86uHZz.md
- 公共服务预约的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/commit/635ef30cfe0137a469b197a3a0b7d93ceb79bfb9?/124
- 社区安全巡查的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/commit/635ef30cfe0137a469b197a3a0b7d93ceb79bfb9?/mhe
- 邻里互助活动的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/635ef30cfe0137a469b197a3a0b7d93ceb79bfb9?/988/?pyi
- 社区共享书架的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/635ef30cfe0137a469b197a3a0b7d93ceb79bfb9?/500=977
- 地方文化传播的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/635ef30cfe0137a469b197a3a0b7d93ceb79bfb9?/sgi=594
- 农贸市场环境的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/86uHZz.md?/759
- 公共服务咨询的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/86uHZz.md?/bez
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/86uHZz.md?/389/?xty
- 城市适老服务的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/86uHZz.md?/205=340
- 城市生活记录的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/86uHZz.md?/zmq=965
- 新能源出行的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/3GBEq1.md
- 市民热线服务的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/commit/61c055ded673461489543eaa0b6ff226a7c64c82?/783
- 社区养老服务的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/61c055ded673461489543eaa0b6ff226a7c64c82?/mra
- 青少年科技社团的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/61c055ded673461489543eaa0b6ff226a7c64c82?/452/?hjq
- 社区学习活动的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/61c055ded673461489543eaa0b6ff226a7c64c82?/359=058
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/61c055ded673461489543eaa0b6ff226a7c64c82?/hzs=421
- 本地历史资料的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/3GBEq1.md?/311
- 健康信息获取的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/3GBEq1.md?/wro
- 学校体育活动的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/3GBEq1.md?/451/?uvn
- 小微企业服务的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/3GBEq1.md?/670=559
- 本地旅行体验的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/3GBEq1.md?/uyl=076
- 城市夜间照明的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/O9ETu9.md
- 便民信息查询的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/ddb0dde937f7e25f2da34dcd781aaa8e8d4959a5?/809
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/ddb0dde937f7e25f2da34dcd781aaa8e8d4959a5?/mwu
- 药品使用科普的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/ddb0dde937f7e25f2da34dcd781aaa8e8d4959a5?/967/?fic
- 线上办事服务的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/ddb0dde937f7e25f2da34dcd781aaa8e8d4959a5?/512=694
- 数字政务体验的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/ddb0dde937f7e25f2da34dcd781aaa8e8d4959a5?/obe=524
- 城市微更新实践的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/O9ETu9.md?/948
- 非遗体验活动的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/O9ETu9.md?/hgh
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/O9ETu9.md?/067/?hxw
- 邻里互助活动的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/O9ETu9.md?/393=216
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/O9ETu9.md?/ohe=463
- 街道综合服务的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/eCEO4p.md
- 社区生活指南的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/8f8a7d6000cd5c454d8ea78528424242f5043c47?/581
- 健康步道使用的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/commit/8f8a7d6000cd5c454d8ea78528424242f5043c47?/cxo
- 食品配送体验中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/8f8a7d6000cd5c454d8ea78528424242f5043c47?/620/?hkq
- 公共设施使用的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/8f8a7d6000cd5c454d8ea78528424242f5043c47?/186=531
- 家庭环保行动的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/commit/8f8a7d6000cd5c454d8ea78528424242f5043c47?/pwm=506
- 家庭照护支持的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/eCEO4p.md?/177
- 家庭养老规划的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/eCEO4p.md?/ysm
- 节气饮食文化的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/eCEO4p.md?/789/?fwq
- 户外活动组织的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/eCEO4p.md?/037=612
- 社区学习活动的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/eCEO4p.md?/sop=469
- 机器学习入门的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/pRunCG.md
- 社区生活指南的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/060f2c1f975ee99d42377b091e7f15fb7ccc4dda?/405
- 创业经验分享的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/060f2c1f975ee99d42377b091e7f15fb7ccc4dda?/zid
- 公共场所导视的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/060f2c1f975ee99d42377b091e7f15fb7ccc4dda?/547/?ipf
- 城市公共标识的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/060f2c1f975ee99d42377b091e7f15fb7ccc4dda?/591=344
- 青少年户外教育的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/060f2c1f975ee99d42377b091e7f15fb7ccc4dda?/weg=874
- 图书借阅体验的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/pRunCG.md?/853
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/pRunCG.md?/vqp
- 社区活动策划的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/pRunCG.md?/035/?qpb
- 节能家电使用中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/pRunCG.md?/445=860
- 食品安全科普的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/pRunCG.md?/lzf=690
- 邻里互助活动的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/iwfusU.md
- 老年友好服务中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/3421ea3b82f2e9ff50f141dcb3d7b28bb79548bc?/505
- 生活垃圾回收的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/commit/3421ea3b82f2e9ff50f141dcb3d7b28bb79548bc?/fbn
- 青年职业探索的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/3421ea3b82f2e9ff50f141dcb3d7b28bb79548bc?/597/?sqd
- 社区老年食堂的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/3421ea3b82f2e9ff50f141dcb3d7b28bb79548bc?/111=429
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/3421ea3b82f2e9ff50f141dcb3d7b28bb79548bc?/vko=846
- 家庭食品保存的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/iwfusU.md?/579
- 绿色建筑理念的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/iwfusU.md?/bsh
- 公共健身器材的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/iwfusU.md?/649/?lpg
- 物业服务沟通的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/iwfusU.md?/454=189
- 老年人文化生活中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/iwfusU.md?/uxg=540
- 劳动教育实践的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/m0NWZj.md
- 城市公共艺术的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/e1258f3720eaae75e4fb6c30eded33f0f117cca1?/009
- 公园休闲体验的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/e1258f3720eaae75e4fb6c30eded33f0f117cca1?/vgx
- 旧物循环利用的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/e1258f3720eaae75e4fb6c30eded33f0f117cca1?/667/?iql
- 学校体育活动的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/e1258f3720eaae75e4fb6c30eded33f0f117cca1?/552=836
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/e1258f3720eaae75e4fb6c30eded33f0f117cca1?/kxa=869
- 公共服务指南的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/m0NWZj.md?/897
- 乡村公共服务的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/m0NWZj.md?/fyc
- 创业经验分享的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/m0NWZj.md?/716/?gmd
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/m0NWZj.md?/485=991
- 公共场所导视的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/m0NWZj.md?/pof=233
- 城市步行环境的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/29g6ry.md
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/e4b6c3f4dcf0df645118729fb2bd2df130c15968?/429
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/e4b6c3f4dcf0df645118729fb2bd2df130c15968?/xvh
- 城乡公共服务的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/e4b6c3f4dcf0df645118729fb2bd2df130c15968?/411/?zmu
- 社区活动策划的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/e4b6c3f4dcf0df645118729fb2bd2df130c15968?/539=472
- 数字便民地图的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/e4b6c3f4dcf0df645118729fb2bd2df130c15968?/hxz=328
- 社区学习活动的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/29g6ry.md?/884
- 城市公共艺术的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/29g6ry.md?/oim
- 低碳社区实践的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/29g6ry.md?/226/?djp
- 数字生活课堂的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/29g6ry.md?/567=882
- 科学运动指导的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/29g6ry.md?/idq=491
- 城市运动公园的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/XSXWzm.md
- 城市社区治理的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/9295b0a0f7415e3d52c139e7de4b3226e7f76cfa?/465
- 软件开发学习的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/9295b0a0f7415e3d52c139e7de4b3226e7f76cfa?/fig
- 线上阅读资源的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/9295b0a0f7415e3d52c139e7de4b3226e7f76cfa?/616/?brc
- 便民维修服务的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/9295b0a0f7415e3d52c139e7de4b3226e7f76cfa?/933=764
- 文明养宠科普的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/9295b0a0f7415e3d52c139e7de4b3226e7f76cfa?/jyy=263
- 职业技能学习的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/XSXWzm.md?/645
- 家庭运动计划的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/XSXWzm.md?/jps
- 家庭消费规划的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/XSXWzm.md?/147/?vjx
- 城市人文观察的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/XSXWzm.md?/814=181
- 家庭教育交流的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/XSXWzm.md?/aam=942
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/zNYG6M.md
- 数字素养提升的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/fb0b587d144019763c2ab4a15143dac6263119e9?/054
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/fb0b587d144019763c2ab4a15143dac6263119e9?/zgs
- 数字艺术创作的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/fb0b587d144019763c2ab4a15143dac6263119e9?/394/?duq
- 社区心理支持的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/fb0b587d144019763c2ab4a15143dac6263119e9?/693=308
- 城市休闲步道的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/fb0b587d144019763c2ab4a15143dac6263119e9?/yon=151
- 旧物循环利用的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/zNYG6M.md?/108
- 社区志愿服务中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/zNYG6M.md?/aai
- 乡村阅读空间的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/zNYG6M.md?/219/?epc
- 校园节能行动的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/zNYG6M.md?/462=652
- 基层健康档案的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/zNYG6M.md?/dmi=282
- 急救知识普及的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/767VhU.md
- 安全出行教育的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/496f4ecc819a8b06999eb7c96111c817e4bb4409?/636
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/496f4ecc819a8b06999eb7c96111c817e4bb4409?/aez
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/496f4ecc819a8b06999eb7c96111c817e4bb4409?/081/?cgb
- 家庭环保行动的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/commit/496f4ecc819a8b06999eb7c96111c817e4bb4409?/337=533
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/496f4ecc819a8b06999eb7c96111c817e4bb4409?/ath=885
- 环境教育课程的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/767VhU.md?/373
- 城市公共标识的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/767VhU.md?/gyc
- 公共设施维护的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/767VhU.md?/673/?rvq
- 城市体育设施的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/767VhU.md?/381=677
- 社区读书角建设的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/767VhU.md?/bbp=158
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/EZfHmp.md
- 开放数据应用的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/d09e9eed4b1f801d45272f9a05d984439ce9dfc8?/965
- 家庭理财科普的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/d09e9eed4b1f801d45272f9a05d984439ce9dfc8?/eyg
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/d09e9eed4b1f801d45272f9a05d984439ce9dfc8?/912/?fkt
- 公交站点体验的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/d09e9eed4b1f801d45272f9a05d984439ce9dfc8?/170=441
- 新能源知识普及的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/d09e9eed4b1f801d45272f9a05d984439ce9dfc8?/dzj=666
- 社区公共议事的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/EZfHmp.md?/894
- 社区互助网络的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/EZfHmp.md?/gsh
- 家庭环保行动的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/EZfHmp.md?/404/?uci
- 城市休闲步道的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/EZfHmp.md?/480=362
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/EZfHmp.md?/rnj=151
- 公共服务咨询的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/e7tcjK.md
- 城市可持续生活的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/c069e14aec28446ff2f1efcff4c616e93edd57ff?/291
- 创业经验分享的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/c069e14aec28446ff2f1efcff4c616e93edd57ff?/kne
- 老年人文化生活的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/c069e14aec28446ff2f1efcff4c616e93edd57ff?/016/?osw
- 家庭健康管理的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/c069e14aec28446ff2f1efcff4c616e93edd57ff?/150=741
- 农村环境治理的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/c069e14aec28446ff2f1efcff4c616e93edd57ff?/kqt=609
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/e7tcjK.md?/618
- 消防知识宣传的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/e7tcjK.md?/ykv
- 公共图书馆服务的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/e7tcjK.md?/341/?zba
- 社区文化节活动的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/e7tcjK.md?/176=573
- 青少年心理健康的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/e7tcjK.md?/mrw=067
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/mO5ncw.md
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/f2c0eac6ff72d20308beede46b5c3607e27505fd?/859
- 街区绿化养护的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/f2c0eac6ff72d20308beede46b5c3607e27505fd?/cbn
- 软件开发学习的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/f2c0eac6ff72d20308beede46b5c3607e27505fd?/770/?pzj
- 社区宠物管理的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/f2c0eac6ff72d20308beede46b5c3607e27505fd?/019=714
- 运动安全知识的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/f2c0eac6ff72d20308beede46b5c3607e27505fd?/zum=456
- 社区阅读服务的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/mO5ncw.md?/953
- 街头绿植养护的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/mO5ncw.md?/xrp
- 青年职业探索的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/mO5ncw.md?/125/?afb
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/mO5ncw.md?/566=464
- 社区互助网络的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/mO5ncw.md?/jko=915
- 市民意见收集的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/8cSLn4.md
- 劳动教育实践的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/3d95b48df524492b9d2f9a1e7bbebc86c9d64443?/227
- 社区商业活力的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/3d95b48df524492b9d2f9a1e7bbebc86c9d64443?/vdr
- 家庭节能设备的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/3d95b48df524492b9d2f9a1e7bbebc86c9d64443?/698/?ynv
- 小微企业服务的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/3d95b48df524492b9d2f9a1e7bbebc86c9d64443?/565=920
- 城乡公共服务的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/3d95b48df524492b9d2f9a1e7bbebc86c9d64443?/lup=001
- 创业经验分享的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/8cSLn4.md?/158
- 地方民俗记录的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/8cSLn4.md?/gxu
- 城市体育设施的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/8cSLn4.md?/086/?jnc
- 老年人日常照护的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/8cSLn4.md?/810=454
- 城市公共标识的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/8cSLn4.md?/ygd=567
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/u6k8bF.md
- 基层健康档案的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/48e5724d70da34cdc2b4b21b7048daf31db8e8b3?/471
- 科普展览体验的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/commit/48e5724d70da34cdc2b4b21b7048daf31db8e8b3?/mwx
- 社区手工活动的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/48e5724d70da34cdc2b4b21b7048daf31db8e8b3?/003/?yhz
- 公共服务评价中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/48e5724d70da34cdc2b4b21b7048daf31db8e8b3?/443=665
- 社区公共议事的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/48e5724d70da34cdc2b4b21b7048daf31db8e8b3?/inf=995
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/u6k8bF.md?/913
- 食品安全科普的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/u6k8bF.md?/qdc
- 学校食育活动的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/u6k8bF.md?/908/?kik
- 城市农夫市集的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/u6k8bF.md?/419=350
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/u6k8bF.md?/atr=075
- 健康饮食教育的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/WbS3ME.md
- 儿童友好空间的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/74316ba67a8d05d1494efe27e0891e61cafc3e8b?/935
- 医院导诊服务的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/74316ba67a8d05d1494efe27e0891e61cafc3e8b?/xgt
- 城市博物馆活动的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/74316ba67a8d05d1494efe27e0891e61cafc3e8b?/551/?wya
- 街区更新实践的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/74316ba67a8d05d1494efe27e0891e61cafc3e8b?/956=698
- 数字地图应用的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/74316ba67a8d05d1494efe27e0891e61cafc3e8b?/evb=952
- 城市空气科普的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/WbS3ME.md?/047
- 公共场所导视的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/WbS3ME.md?/vje
- 绿色出行服务的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/WbS3ME.md?/329/?meg
- 乡村文化活动的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/WbS3ME.md?/552=809
- 老年友好服务的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/WbS3ME.md?/rsk=172
- 社区便民集市的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/JAjP6A.md
- 老年人文化生活的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/628c51dfbc3134978de5d4b5f1b9ea031b2705e8?/448
- 城市微更新实践的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/628c51dfbc3134978de5d4b5f1b9ea031b2705e8?/bxn
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/commit/628c51dfbc3134978de5d4b5f1b9ea031b2705e8?/933/?ene
- 个人时间管理中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/628c51dfbc3134978de5d4b5f1b9ea031b2705e8?/306=914
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/628c51dfbc3134978de5d4b5f1b9ea031b2705e8?/mwk=272
- 生活垃圾回收的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/JAjP6A.md?/899
- 农村环境治理的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/JAjP6A.md?/kfr
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/JAjP6A.md?/148/?xlf
- 城市公共艺术的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/JAjP6A.md?/415=198
- 社区交通安全的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/JAjP6A.md?/iyt=634
- 节气饮食文化的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/7f5ONJ.md
- 城市公共饮水的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/7bd3c92d5f7df9e954bb41f152dc6c80228d4b7c?/541
- 科学教育活动的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/7bd3c92d5f7df9e954bb41f152dc6c80228d4b7c?/owt
- 便民服务地图的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/7bd3c92d5f7df9e954bb41f152dc6c80228d4b7c?/402/?gqn
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/7bd3c92d5f7df9e954bb41f152dc6c80228d4b7c?/528=846
- 数字生活课堂的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/7bd3c92d5f7df9e954bb41f152dc6c80228d4b7c?/iyn=784
- 儿童运动体验的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/7f5ONJ.md?/552
- 社区邻里服务的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/7f5ONJ.md?/ivj
- 城市休闲步道的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/7f5ONJ.md?/691/?oye
- 线上办事服务的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/7f5ONJ.md?/550=711
- 社区阅读服务的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/7f5ONJ.md?/spt=215
- 图书借阅体验的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/dTjHZA.md
- 公共设施使用的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/c062fcf0638605b1af1edd4d84ab1faf3feadd9f?/671
- 数字阅读服务的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/commit/c062fcf0638605b1af1edd4d84ab1faf3feadd9f?/hns
- 公共服务评价的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/c062fcf0638605b1af1edd4d84ab1faf3feadd9f?/162/?gau
- 在线教育体验的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/c062fcf0638605b1af1edd4d84ab1faf3feadd9f?/101=601
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/c062fcf0638605b1af1edd4d84ab1faf3feadd9f?/dwu=484
- 机器人科普活动的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/dTjHZA.md?/405
- 乡村生活观察的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/dTjHZA.md?/uhq
- 灵活就业交流的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/dTjHZA.md?/134/?rtp
- 旧物循环利用的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/dTjHZA.md?/329=745
- 健康信息获取的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/dTjHZA.md?/svw=739
- 公共服务预约的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/i46OiL.md
- 城市生活服务的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/95ad613609be7f12b0d65c825a389896ff83b2fa?/780
- 社区学习活动的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/95ad613609be7f12b0d65c825a389896ff83b2fa?/urs
- 公共交通信息服务的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/95ad613609be7f12b0d65c825a389896ff83b2fa?/287/?ayc
- 乡村产业科普的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/95ad613609be7f12b0d65c825a389896ff83b2fa?/250=489
- 社区活动报名的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/95ad613609be7f12b0d65c825a389896ff83b2fa?/hab=005
- 全民健身活动的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/i46OiL.md?/621
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/i46OiL.md?/kfg
- 绿色建筑理念的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/i46OiL.md?/863/?gpn
- 人工智能科普的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/i46OiL.md?/357=080
- 农村环境治理中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/i46OiL.md?/jag=414
- 城市文明出行的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/HRPYZH.md
- 城市适老服务的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/eb98cb3cfd84dd8a58b3cc1722ba4f52e54c7942?/651
- 应急物资管理的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/eb98cb3cfd84dd8a58b3cc1722ba4f52e54c7942?/sgi
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/eb98cb3cfd84dd8a58b3cc1722ba4f52e54c7942?/649/?rxa
- 社区儿童活动中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/eb98cb3cfd84dd8a58b3cc1722ba4f52e54c7942?/646=940
- 亲子科普活动的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/eb98cb3cfd84dd8a58b3cc1722ba4f52e54c7942?/cza=772
- 在线学习体验的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/HRPYZH.md?/018
- 个人信息保护的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/HRPYZH.md?/qdr
- 城市步行友好的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/HRPYZH.md?/325/?qov
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/HRPYZH.md?/980=748
- 健康饮食教育的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/HRPYZH.md?/arv=192
- 个人信息保护中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/vUwOAx.md
- 城市生活记录的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/09ca4fb246360dec1d2d70134bb5aa1399614200?/432
- 公共服务预约的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/09ca4fb246360dec1d2d70134bb5aa1399614200?/dqa
- 儿童运动体验的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/09ca4fb246360dec1d2d70134bb5aa1399614200?/849/?cjq
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/09ca4fb246360dec1d2d70134bb5aa1399614200?/318=469
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/09ca4fb246360dec1d2d70134bb5aa1399614200?/tpz=987
- 城乡交通衔接的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/vUwOAx.md?/554
- 社区设施共享的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/vUwOAx.md?/bxp
- 乡村公共阅读的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/vUwOAx.md?/711/?ppd
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/vUwOAx.md?/054=834
- 校园节能行动的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/vUwOAx.md?/lyf=700
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/LjOU2Q.md
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/431d7cf67ef9caebae1f0333fb30d76a29dd9395?/983
- 基层健康服务的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/431d7cf67ef9caebae1f0333fb30d76a29dd9395?/vvk
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/431d7cf67ef9caebae1f0333fb30d76a29dd9395?/185/?zxc
- 绿色校园实践的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/431d7cf67ef9caebae1f0333fb30d76a29dd9395?/451=390
- 城市慢跑路线的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/431d7cf67ef9caebae1f0333fb30d76a29dd9395?/yuw=256
- 城市公共厕所的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/LjOU2Q.md?/674
- 青年职业探索的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/LjOU2Q.md?/tkv
- 城乡交通衔接的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/LjOU2Q.md?/532/?iid
- 农产品品牌传播的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/LjOU2Q.md?/383=858
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/LjOU2Q.md?/vwk=766
- 个人信息保护的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/GF7fj5.md
- 乡村文化空间的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/15a088344c1fe6be7087234c513ffc614c6f6ce3?/695
- 城市地名文化的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/15a088344c1fe6be7087234c513ffc614c6f6ce3?/hcf
- 社区养老服务的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/15a088344c1fe6be7087234c513ffc614c6f6ce3?/260/?jaf
- 地方文化传播的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/15a088344c1fe6be7087234c513ffc614c6f6ce3?/648=614
- 文化讲座服务的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/15a088344c1fe6be7087234c513ffc614c6f6ce3?/fqx=307
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/GF7fj5.md?/039
- 城市树木认养的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/GF7fj5.md?/nsj
- 校园节能行动的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/GF7fj5.md?/850/?osh
- 绿色办公实践的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/GF7fj5.md?/379=158
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/GF7fj5.md?/wqa=317
- 城市公共饮水的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/GfuxxV.md
- 社区信息发布中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/cc3da222b37622262831f7714d57250d867f61bc?/301
- 家庭急救准备的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/cc3da222b37622262831f7714d57250d867f61bc?/pfm
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/cc3da222b37622262831f7714d57250d867f61bc?/014/?zbe
- 社区活动空间的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/cc3da222b37622262831f7714d57250d867f61bc?/699=686

---

## 📈 关键数据（10月11-13日）

| 指标 | 数值 | 变化/说明 |
|------|------|------|
| 全球大模型周调用量（10/5-11） | 172 万亿 Token | 环比 +3.61%（OpenRouter 测算） |
| 中国大模型周调用量 | 86.74 万亿 Token | 环比 +50.96%；连续 24 周全球第一 |
| 美国大模型周调用量 | 18.97 万亿 Token | 环比 +17.1% |
| Meta Muse Wonder 定价 | $4 / $20（每百万 Token 入/出） | 与 Claude Opus 5.5 同价位 |
| Meta / 微软股价（10/12） | Meta 约 $748（+3.4%–4.1%）；MSFT +2.4% | 模型与自研芯片发布驱动 |
| 微软 Maia 300 | 288GB HBM4；18TB/s；+40% tokens/MW | 2027 年部署超 100 万颗；资本开支预期 >$1750 亿（今年） |
| 亚马逊洽购 Decart | 约 $70 亿 | 较 5 月估值（近 $40 亿）高约 75% |
| AlphaProof Nexus 成果 | 9 个 Erdős 问题 + 44 个数列猜想 | 其中 2 题悬置 56 年；已通过同行评审 |
| 英国网络防御试点 | 累计发现 1,000+ 潜在漏洞 | 单轮试点：407 处弱点/£13,000 token 成本 |

---

*本简报由 Hermes Agent 自动生成*  
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  # 2027第七届中国（厦门）国际跨境电商展览会（中跨展）官方网站等*  
*仅供参考，不构成投资建议*
