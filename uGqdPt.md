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

- 乡村教育资源的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/bada0a3f8cd4660ee3e324431b32aa2297079bcd?/009/?cjv
- 绿色消费选择的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/bada0a3f8cd4660ee3e324431b32aa2297079bcd?/147=885
- 城市休闲步道的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/bada0a3f8cd4660ee3e324431b32aa2297079bcd?/nxy=021
- 家庭志愿活动的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/NLtKZq.md?/240
- 城市空气科普的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/NLtKZq.md?/cfj
- 社区协商议事的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/NLtKZq.md?/313/?zxl
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/NLtKZq.md?/941=158
- 社区家政服务的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/NLtKZq.md?/svx=075
- 文化讲座服务的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/qkVMj3.md
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/c9dd65543e6e88506611147c997c4f3a2ad04cec?/503
- 老年学习活动的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/c9dd65543e6e88506611147c997c4f3a2ad04cec?/whj
- 社区便利生活的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/c9dd65543e6e88506611147c997c4f3a2ad04cec?/721/?oxz
- 小微企业服务的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/c9dd65543e6e88506611147c997c4f3a2ad04cec?/376=254
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/c9dd65543e6e88506611147c997c4f3a2ad04cec?/yon=705
- 家庭节能实践的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/qkVMj3.md?/065
- 农村环境治理的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/qkVMj3.md?/dzb
- 开放数据应用的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/qkVMj3.md?/910/?ahe
- 公交站点体验的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/qkVMj3.md?/409=534
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/qkVMj3.md?/oal=985
- 儿童安全出行的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/cowlVh.md
- 乡村阅读活动的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/commit/a05b8eb78045b9aa459ec54bfe8b6feba344402d?/820
- 小区公共照明的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/a05b8eb78045b9aa459ec54bfe8b6feba344402d?/xpl
- 儿童安全出行的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/a05b8eb78045b9aa459ec54bfe8b6feba344402d?/667/?cfk
- 城市基础设施的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/a05b8eb78045b9aa459ec54bfe8b6feba344402d?/973=625
- 智能手机助老的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/a05b8eb78045b9aa459ec54bfe8b6feba344402d?/gyb=500
- 网络安全教育的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/cowlVh.md?/415
- 社区儿童活动的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/cowlVh.md?/cql
- 城市文化路线的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/cowlVh.md?/971/?aii
- 社区防暑服务的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/cowlVh.md?/726=994
- 街道综合服务的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/cowlVh.md?/mzm=909
- 家庭饮食安排的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/hKezNv.md
- 公园亲子设施的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/e888d86eb9dc167d43a63e9eecde924fb87a8440?/460
- 社区文化传播的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/e888d86eb9dc167d43a63e9eecde924fb87a8440?/wre
- 本地消费场景的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/e888d86eb9dc167d43a63e9eecde924fb87a8440?/155/?kum
- 儿童运动体验的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/e888d86eb9dc167d43a63e9eecde924fb87a8440?/959=001
- 数字设备回收的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/e888d86eb9dc167d43a63e9eecde924fb87a8440?/jks=925
- 绿色建筑理念的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/hKezNv.md?/845
- 城市骑行环境的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/hKezNv.md?/ipa
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/hKezNv.md?/145/?bie
- 药品使用科普的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/hKezNv.md?/697=635
- 安全出行教育的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/hKezNv.md?/gcd=855
- 绿色校园实践的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/10YQLU.md
- 城市公共艺术的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/9db524dfd7ab3e73d43214aae0f76bbc0ce4aab2?/055
- 绿色生活实践的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/9db524dfd7ab3e73d43214aae0f76bbc0ce4aab2?/yxr
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/9db524dfd7ab3e73d43214aae0f76bbc0ce4aab2?/177/?shj
- 地方美食文化的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/9db524dfd7ab3e73d43214aae0f76bbc0ce4aab2?/995=811
- 气象科普传播的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/9db524dfd7ab3e73d43214aae0f76bbc0ce4aab2?/kgr=393
- 城市运动公园的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/10YQLU.md?/698
- 市民意见收集的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/10YQLU.md?/nyp
- 城市微更新实践的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/10YQLU.md?/943/?gon
- 休闲运动入门的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/10YQLU.md?/441=677
- 社区法律科普的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/10YQLU.md?/bkw=074
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/gymH3V.md
- 就业技能培训的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/f9ae45753fa7a0d3eca0b6c31172c78686f22170?/130
- 城市人文观察的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/f9ae45753fa7a0d3eca0b6c31172c78686f22170?/pww
- 城市可持续生活的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/f9ae45753fa7a0d3eca0b6c31172c78686f22170?/952/?shh
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/f9ae45753fa7a0d3eca0b6c31172c78686f22170?/754=601
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/f9ae45753fa7a0d3eca0b6c31172c78686f22170?/qmx=795
- 公共空间照明的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/gymH3V.md?/919
- 绿色生活实践的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/gymH3V.md?/ukf
- 生成式工具使用的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/gymH3V.md?/102/?swp
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/gymH3V.md?/930=458
- 街区更新实践的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/gymH3V.md?/lva=330
- 城市公共厕所的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/sA1RZm.md
- 儿童安全出行的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/eab8db4cdfaa407d792f3d09d9824cbee799ef86?/468
- 城市公共饮水的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/eab8db4cdfaa407d792f3d09d9824cbee799ef86?/wdl
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/eab8db4cdfaa407d792f3d09d9824cbee799ef86?/963/?lmo
- 乡村产业科普的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/eab8db4cdfaa407d792f3d09d9824cbee799ef86?/475=533
- 地方美食文化的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/eab8db4cdfaa407d792f3d09d9824cbee799ef86?/zzf=353
- 低碳社区实践的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/sA1RZm.md?/359
- 城市水环境观察的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/sA1RZm.md?/wbs
- 老年数字阅读的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/sA1RZm.md?/138/?uvn
- 本地消费场景的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/sA1RZm.md?/808=248
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/sA1RZm.md?/bsi=722
- 城市微更新实践的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/F9BktT.md
- 数字资源检索的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/33d543046972b3fa797a78df74bca201d6625986?/060
- 消防知识宣传的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/33d543046972b3fa797a78df74bca201d6625986?/bii
- 市民热线服务的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/33d543046972b3fa797a78df74bca201d6625986?/356/?rph
- 垃圾分类指导的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/33d543046972b3fa797a78df74bca201d6625986?/589=162
- 社区教育资源的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/33d543046972b3fa797a78df74bca201d6625986?/fil=098
- 数字政务体验的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/F9BktT.md?/141
- 社区文化传播的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/F9BktT.md?/tve
- 社区宠物管理的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/F9BktT.md?/338/?vrr
- 环境监测科普的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/F9BktT.md?/907=101
- 城市社区治理的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/F9BktT.md?/yss=628
- 基层健康档案的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/mzGCmc.md
- 亲子阅读活动的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/commit/03e2bd4a448820d63e372008dc7caa672a97b8f0?/763
- 便民维修服务的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/commit/03e2bd4a448820d63e372008dc7caa672a97b8f0?/ihd
- 老年运动活动的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/03e2bd4a448820d63e372008dc7caa672a97b8f0?/219/?tou
- 本地历史资料的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/03e2bd4a448820d63e372008dc7caa672a97b8f0?/255=449
- 社区停车服务的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/03e2bd4a448820d63e372008dc7caa672a97b8f0?/vms=050
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/mzGCmc.md?/387
- 数字课堂应用的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/mzGCmc.md?/tvl
- 文化讲座服务的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/mzGCmc.md?/167/?dir
- 社区家校合作的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/mzGCmc.md?/726=074
- 户外活动组织的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/mzGCmc.md?/rpg=940
- 城乡公共服务的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/B9FaHI.md
- 口袋公园建设的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/commit/0736c2ffda0de6cf0b5bdcb148873081a67f678a?/159
- 城市便民驿站的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/0736c2ffda0de6cf0b5bdcb148873081a67f678a?/cgl
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/0736c2ffda0de6cf0b5bdcb148873081a67f678a?/593/?rco
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/0736c2ffda0de6cf0b5bdcb148873081a67f678a?/821=321
- 城市夜间生活的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/0736c2ffda0de6cf0b5bdcb148873081a67f678a?/hvg=708
- 城市便民驿站中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/B9FaHI.md?/372
- 家庭安全提示的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/B9FaHI.md?/yjj
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/B9FaHI.md?/520/?ugb
- 家庭节能设备的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/B9FaHI.md?/230=839
- 社区老年食堂的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/B9FaHI.md?/fpl=283
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/hCz209.md
- 儿童友好空间的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/5e35ce96b41822e067bba883f9971ecf5886fa23?/809
- 户外活动组织的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/5e35ce96b41822e067bba883f9971ecf5886fa23?/efx
- 绿色校园实践的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/5e35ce96b41822e067bba883f9971ecf5886fa23?/103/?gxr
- 家庭阅读计划的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/5e35ce96b41822e067bba883f9971ecf5886fa23?/080=998
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/5e35ce96b41822e067bba883f9971ecf5886fa23?/spo=872
- 数字资源检索的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/hCz209.md?/983
- 数字资源检索的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/hCz209.md?/jgt
- 城乡交流活动的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/hCz209.md?/004/?brt
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/hCz209.md?/514=822
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/hCz209.md?/krq=003
- 机器人科普活动的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/Y2m7KJ.md
- 全民健身活动的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/993ad0df2b3044c9e6de7431c3d1aba3d24e58cb?/122
- 校园社团活动的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/993ad0df2b3044c9e6de7431c3d1aba3d24e58cb?/phi
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/993ad0df2b3044c9e6de7431c3d1aba3d24e58cb?/781/?epv
- 灵活就业交流的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/993ad0df2b3044c9e6de7431c3d1aba3d24e58cb?/648=319
- 社区法律科普的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/993ad0df2b3044c9e6de7431c3d1aba3d24e58cb?/ycb=724
- 老年智能设备的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/Y2m7KJ.md?/215
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/Y2m7KJ.md?/wpw
- 小区电梯维护的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/Y2m7KJ.md?/053/?dmk
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/Y2m7KJ.md?/007=958
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/Y2m7KJ.md?/uac=649
- 家庭网络使用的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/JARh8A.md
- 儿童安全出行的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/78813027f104cf394eb49bc0fa3cdc062913fc38?/031
- 小微企业服务的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/78813027f104cf394eb49bc0fa3cdc062913fc38?/bqx
- 青少年户外教育的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/78813027f104cf394eb49bc0fa3cdc062913fc38?/213/?ywu
- 儿童阅读角的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/78813027f104cf394eb49bc0fa3cdc062913fc38?/771=242
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/78813027f104cf394eb49bc0fa3cdc062913fc38?/vfs=496
- 社区儿童活动的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/JARh8A.md?/265
- 老年运动活动的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/JARh8A.md?/cnc
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/JARh8A.md?/209/?gne
- 社区休闲设施的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/JARh8A.md?/220=784
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/JARh8A.md?/rtm=654
- 家庭用电安全的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/R1WOJf.md
- 家庭教育交流的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/55a82076f42f3b48f8f1748b2d8884d3b8c877dd?/283
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/55a82076f42f3b48f8f1748b2d8884d3b8c877dd?/rcl
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/55a82076f42f3b48f8f1748b2d8884d3b8c877dd?/400/?pun
- 青少年户外教育的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/55a82076f42f3b48f8f1748b2d8884d3b8c877dd?/397=925
- 城市适老服务的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/55a82076f42f3b48f8f1748b2d8884d3b8c877dd?/zew=616
- 老年友好服务的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/R1WOJf.md?/860
- 城市夜间照明的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/R1WOJf.md?/lvf
- 健康信息获取的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/R1WOJf.md?/854/?sue
- 职业技能学习的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/R1WOJf.md?/492=544
- 周末休闲规划的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/R1WOJf.md?/tur=962
- 家庭照护支持中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/EpGGJU.md
- 社区商业活力的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/601da59db1fad021594fd79941c97661114f1c09?/357
- 街区小店体验的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/601da59db1fad021594fd79941c97661114f1c09?/aje
- 智能手机助老的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/601da59db1fad021594fd79941c97661114f1c09?/598/?rlt
- 社区休闲设施的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/601da59db1fad021594fd79941c97661114f1c09?/366=058
- 社区安全巡查的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/601da59db1fad021594fd79941c97661114f1c09?/tef=520
- 数字政务体验的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/blob/main/EpGGJU.md?/252
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/EpGGJU.md?/esr
- 社区菜市场服务的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/EpGGJU.md?/667/?fuf
- 节能家电使用的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/EpGGJU.md?/659=295
- 应急物资管理的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/EpGGJU.md?/che=804
- 数字设备回收的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/vmvOTl.md
- 数字创意课程的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/f6300f5bfbcf92b8e35a662835e2a8e932de250d?/070
- 社区家校合作的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/f6300f5bfbcf92b8e35a662835e2a8e932de250d?/rge
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/f6300f5bfbcf92b8e35a662835e2a8e932de250d?/480/?vyf
- 绿色建筑理念的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/commit/f6300f5bfbcf92b8e35a662835e2a8e932de250d?/396=807
- 社区商业活力的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/f6300f5bfbcf92b8e35a662835e2a8e932de250d?/iou=913
- 公共空间休憩中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/vmvOTl.md?/194
- 数字支付体验的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/vmvOTl.md?/lam
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/vmvOTl.md?/117/?mbi
- 城市游园体验中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/vmvOTl.md?/014=471
- 数字艺术创作的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/vmvOTl.md?/nvm=485
- 校园节能行动的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/wD6I8J.md
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/72bdad284d4cd91818e556285e002c7076f11e8b?/883
- 农贸市场环境的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/72bdad284d4cd91818e556285e002c7076f11e8b?/pfm
- 公共空间照明的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/72bdad284d4cd91818e556285e002c7076f11e8b?/356/?pxy
- 青年就业服务的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/72bdad284d4cd91818e556285e002c7076f11e8b?/462=747
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/commit/72bdad284d4cd91818e556285e002c7076f11e8b?/nke=537
- 数字支付体验的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/wD6I8J.md?/814
- 生活垃圾回收的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/wD6I8J.md?/poc
- 生成式工具使用的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/wD6I8J.md?/784/?bet
- 传统手工艺体验的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/wD6I8J.md?/700=149
- 数字政务体验的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/wD6I8J.md?/pxm=900
- 全民阅读推广的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/DkRXbc.md
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/99edde1dffa484f4dc351435ce85d5f986a16e13?/028
- 口袋公园建设的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/99edde1dffa484f4dc351435ce85d5f986a16e13?/mee
- 社区快递服务中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/99edde1dffa484f4dc351435ce85d5f986a16e13?/563/?zcy
- 公共设施维护的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/99edde1dffa484f4dc351435ce85d5f986a16e13?/951=172
- 公共空间导览的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/99edde1dffa484f4dc351435ce85d5f986a16e13?/iet=913
- 社区便利生活的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/DkRXbc.md?/609
- 小区电梯维护的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/DkRXbc.md?/xrv
- 公共空间导览的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/DkRXbc.md?/995/?vmg
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/DkRXbc.md?/010=054
- 新能源出行的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/DkRXbc.md?/exk=758
- 公园亲子设施的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/jlL04t.md
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/50bf62a8b5504dcd23ea1d0733ca48aeaf0d725c?/729
- 街区道路维护的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/commit/50bf62a8b5504dcd23ea1d0733ca48aeaf0d725c?/fga
- 公共卫生设施中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/50bf62a8b5504dcd23ea1d0733ca48aeaf0d725c?/898/?hok
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/50bf62a8b5504dcd23ea1d0733ca48aeaf0d725c?/668=129
- 城市应急广播的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/50bf62a8b5504dcd23ea1d0733ca48aeaf0d725c?/nwe=108
- 青少年科普实践的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/jlL04t.md?/133
- 城市夜间生活的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/jlL04t.md?/njg
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/jlL04t.md?/929/?yjh
- 老年友好服务的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/jlL04t.md?/307=303
- 城乡公共服务的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/jlL04t.md?/lpr=684
- 文明养宠科普的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/Oj0EzC.md
- 社区交通安全的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/4a8b9f52cf65beed9c60148bf1b0ebca6469fc7c?/821
- 儿童友好街区的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/4a8b9f52cf65beed9c60148bf1b0ebca6469fc7c?/ukh
- 个人数据管理的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/4a8b9f52cf65beed9c60148bf1b0ebca6469fc7c?/666/?gvj
- 公共交通接驳的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/4a8b9f52cf65beed9c60148bf1b0ebca6469fc7c?/755=747
- 城市慢行系统的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/4a8b9f52cf65beed9c60148bf1b0ebca6469fc7c?/xtz=229
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/Oj0EzC.md?/152
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/Oj0EzC.md?/qou
- 老年人日常照护的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/Oj0EzC.md?/236/?fgm
- 公共服务沟通的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/Oj0EzC.md?/133=669
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/Oj0EzC.md?/pza=449
- 家庭健康科普的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/xMMW2o.md
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/1783dc5cafcaeae568379e940a05fb226e77d321?/406
- 本地旅行体验的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/1783dc5cafcaeae568379e940a05fb226e77d321?/ohw
- 街区道路维护的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/1783dc5cafcaeae568379e940a05fb226e77d321?/132/?xia
- 绿色出行服务的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/1783dc5cafcaeae568379e940a05fb226e77d321?/752=434
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/1783dc5cafcaeae568379e940a05fb226e77d321?/rth=474
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/xMMW2o.md?/356
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/xMMW2o.md?/euv
- 老年智能设备的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/xMMW2o.md?/285/?ddq
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/xMMW2o.md?/016=450
- 儿童安全出行的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/xMMW2o.md?/bba=911
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/HMIVOY.md
- 数字支付体验的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/b8727aa210f7fd1273851a3524861a51275a780f?/640
- 家庭环保行动的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/b8727aa210f7fd1273851a3524861a51275a780f?/tml
- 社区便民集市的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/b8727aa210f7fd1273851a3524861a51275a780f?/814/?tfr
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/b8727aa210f7fd1273851a3524861a51275a780f?/013=047
- 电动汽车充电的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/b8727aa210f7fd1273851a3524861a51275a780f?/cpj=704
- 街道综合服务的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/HMIVOY.md?/334
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/HMIVOY.md?/bba
- 市民意见收集的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/HMIVOY.md?/519/?ztd
- 学校体育活动的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/HMIVOY.md?/843=826
- 社区互助网络的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/HMIVOY.md?/dnu=704
- 儿童阅读角的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/qV4zzb.md
- 全民阅读推广的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/0b107cb43fb3d39031d4a0753f7047308dea92df?/725
- 生成式工具使用的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/0b107cb43fb3d39031d4a0753f7047308dea92df?/rmz
- 健康饮食教育的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/0b107cb43fb3d39031d4a0753f7047308dea92df?/875/?hxt
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/0b107cb43fb3d39031d4a0753f7047308dea92df?/289=906
- 社区心理支持的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/0b107cb43fb3d39031d4a0753f7047308dea92df?/naa=437
- 地方美食文化的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/qV4zzb.md?/809
- 社区消防演练的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/qV4zzb.md?/blh
- 城市夜间生活的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/qV4zzb.md?/432/?sno
- 家庭网络使用的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/qV4zzb.md?/845=142
- 公共服务数字化的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/qV4zzb.md?/ubw=980
- 老年人文化生活的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/3vpjDg.md
- 城市可持续生活的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/a89f992ee0398ee41c7eb2e21cec1a6c782d9b96?/679
- 急救知识普及的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/commit/a89f992ee0398ee41c7eb2e21cec1a6c782d9b96?/nke
- 乡村公共阅读的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/commit/a89f992ee0398ee41c7eb2e21cec1a6c782d9b96?/333/?kob
- 家庭消费规划的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/a89f992ee0398ee41c7eb2e21cec1a6c782d9b96?/646=895
- 公交站点体验的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/commit/a89f992ee0398ee41c7eb2e21cec1a6c782d9b96?/tgi=839
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/3vpjDg.md?/210
- 健康信息获取的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/3vpjDg.md?/jmv
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/3vpjDg.md?/881/?myc
- 数字档案服务的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/3vpjDg.md?/816=327
- 智慧停车服务的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/3vpjDg.md?/vjq=403
- 骑行路线规划的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/vP3ayC.md
- 城乡公共服务的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/10c6e4f05798b057b149defe224c65b3ab0f4137?/957
- 城市体育设施的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/10c6e4f05798b057b149defe224c65b3ab0f4137?/ziv
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/commit/10c6e4f05798b057b149defe224c65b3ab0f4137?/355/?prw
- 社区花园共建的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/10c6e4f05798b057b149defe224c65b3ab0f4137?/112=916
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/10c6e4f05798b057b149defe224c65b3ab0f4137?/scb=946
- 社区知识分享的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/vP3ayC.md?/173
- 公共健身器材的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/vP3ayC.md?/hbv
- 机器学习入门的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/vP3ayC.md?/268/?ywf
- 社区故事采集的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/vP3ayC.md?/517=807
- 公共服务预约的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/vP3ayC.md?/ots=827
- 科学健身方法的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/xDF5Ps.md
- 科学观察活动的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/commit/07da18c6fd728668d3c4cc53f05e11c31e6f3ca1?/661
- 光伏知识科普的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/07da18c6fd728668d3c4cc53f05e11c31e6f3ca1?/itx
- 家庭园艺实践的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/07da18c6fd728668d3c4cc53f05e11c31e6f3ca1?/695/?anu
- 地方戏曲体验的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/07da18c6fd728668d3c4cc53f05e11c31e6f3ca1?/056=866
- 志愿服务平台的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/07da18c6fd728668d3c4cc53f05e11c31e6f3ca1?/mew=939
- 公共服务数字化的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/xDF5Ps.md?/339
- 骑行路线规划的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/xDF5Ps.md?/nsk
- 基层健康服务的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/xDF5Ps.md?/893/?yrw
- 城市空气科普的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/xDF5Ps.md?/134=219
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/xDF5Ps.md?/vgq=106
- 社区环保活动的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/u1kaKt.md
- 家庭网络使用的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/713418b481cbcfb1dc25359d3c8d7366a912e82f?/965
- 老年人日常照护的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/713418b481cbcfb1dc25359d3c8d7366a912e82f?/mss
- 创业经验分享的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/713418b481cbcfb1dc25359d3c8d7366a912e82f?/489/?acp
- 基层健康服务的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/713418b481cbcfb1dc25359d3c8d7366a912e82f?/153=526
- 环境教育课程的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/713418b481cbcfb1dc25359d3c8d7366a912e82f?/mny=028
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/u1kaKt.md?/470
- 机器人科普活动的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/u1kaKt.md?/ase
- 青少年科技社团的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/u1kaKt.md?/883/?qrv
- 社区停车服务的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/u1kaKt.md?/189=634
- 城市农夫市集的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/u1kaKt.md?/zpm=482
- 社区科普课堂的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/cs8C8f.md
- 家庭环保行动的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/a939c07ed450e16b76e4edc3830cb3a14c76e868?/277
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/a939c07ed450e16b76e4edc3830cb3a14c76e868?/cqc
- 家庭科学教育中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/a939c07ed450e16b76e4edc3830cb3a14c76e868?/408/?imz
- 全民健身活动的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/a939c07ed450e16b76e4edc3830cb3a14c76e868?/336=330
- 科学健身方法的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/commit/a939c07ed450e16b76e4edc3830cb3a14c76e868?/lwf=987
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/cs8C8f.md?/947
- 农产品品牌传播的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/cs8C8f.md?/prr
- 智能手机助老的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/cs8C8f.md?/341/?uoq
- 图书借阅体验的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/cs8C8f.md?/924=609
- 城乡交流活动的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/cs8C8f.md?/dpe=783
- 城市运动公园的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/TmBWdh.md
- 户外活动组织的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/c656b89824301df63fb18b34f08651b1a3391ddc?/805
- 课后服务体验的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/c656b89824301df63fb18b34f08651b1a3391ddc?/iyk
- 社区文化节活动的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/c656b89824301df63fb18b34f08651b1a3391ddc?/238/?xvo
- 社区共享书架的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/c656b89824301df63fb18b34f08651b1a3391ddc?/823=822
- 新能源知识普及的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/c656b89824301df63fb18b34f08651b1a3391ddc?/jmm=275
- 社区邻里服务的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/TmBWdh.md?/862
- 儿童友好空间的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/TmBWdh.md?/iyj
- 社区公共卫生的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/TmBWdh.md?/816/?aia
- 公共服务评价从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/TmBWdh.md?/363=681
- 邻里互助活动的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/TmBWdh.md?/onb=452
- 居家防滑改造的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/C1czTy.md
- 乡村公共阅读的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/c9a6e9f2235a2526d4b33f9206afde826d0ac8ba?/370
- 社区快递服务的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/c9a6e9f2235a2526d4b33f9206afde826d0ac8ba?/sqk
- 校园节能行动的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/commit/c9a6e9f2235a2526d4b33f9206afde826d0ac8ba?/911/?kqq
- 乡村阅读空间的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/c9a6e9f2235a2526d4b33f9206afde826d0ac8ba?/029=775
- 城市公共艺术中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/c9a6e9f2235a2526d4b33f9206afde826d0ac8ba?/lfw=106
- 社区托育服务的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/C1czTy.md?/544
- 节约用水实践的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/C1czTy.md?/lga
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/C1czTy.md?/137/?lyv
- 青少年户外教育的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/C1czTy.md?/303=804
- 家庭环保行动的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/C1czTy.md?/zei=860
- 信息无障碍体验的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/ehUHQl.md
- 食品配送体验的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/ff5bcf91b1f932c3da18ce3e0c5313cb9914b98f?/353
- 绿色快递包装的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/ff5bcf91b1f932c3da18ce3e0c5313cb9914b98f?/col
- 人工智能科普的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/ff5bcf91b1f932c3da18ce3e0c5313cb9914b98f?/466/?npw
- 健康饮食教育的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/ff5bcf91b1f932c3da18ce3e0c5313cb9914b98f?/125=296
- 社区花园共建的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/ff5bcf91b1f932c3da18ce3e0c5313cb9914b98f?/irq=362
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/ehUHQl.md?/074
- 志愿服务平台的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/ehUHQl.md?/def
- 社区养老服务的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/ehUHQl.md?/968/?gzk
- 数字学习资源的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/ehUHQl.md?/657=742
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/ehUHQl.md?/edp=838
- 家庭养老规划的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/blob/main/6CtRpE.md
- 公共设施维护的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/a2ccb8cfccfb76bb587b3f364c3c6283937e4d01?/324
- 食品配送体验的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/commit/a2ccb8cfccfb76bb587b3f364c3c6283937e4d01?/jrg
- 老年智能设备的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/a2ccb8cfccfb76bb587b3f364c3c6283937e4d01?/119/?ids
- 家庭健康科普的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/a2ccb8cfccfb76bb587b3f364c3c6283937e4d01?/320=044
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/a2ccb8cfccfb76bb587b3f364c3c6283937e4d01?/bdv=558
- 邻里互助活动的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/6CtRpE.md?/175
- 社区设施共享的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/6CtRpE.md?/xdo
- 线上办事服务的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/6CtRpE.md?/882/?wba
- 社区学习活动的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/6CtRpE.md?/363=089
- 老年人出行服务的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/6CtRpE.md?/sof=258
- 小区公共照明的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/x96wQf.md
- 文明养宠科普的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/982b3f06311e19781fe34b70c9118fc5701dbf75?/884
- 健康信息获取的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/982b3f06311e19781fe34b70c9118fc5701dbf75?/blu
- 数据分析入门的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/982b3f06311e19781fe34b70c9118fc5701dbf75?/712/?tcu
- 健康步道使用的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/982b3f06311e19781fe34b70c9118fc5701dbf75?/995=194
- 社区防暑服务的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/commit/982b3f06311e19781fe34b70c9118fc5701dbf75?/oxg=807
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/x96wQf.md?/072
- 公园亲子设施的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/x96wQf.md?/zha
- 开源技术交流的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/x96wQf.md?/860/?wgp
- 社区教育资源的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/x96wQf.md?/903=084
- 课后服务体验的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/x96wQf.md?/knb=796
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/kYDJnE.md
- 休闲运动入门的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/dffb7a4d754cd6613da300c56f7207ced7f86de9?/336
- 青少年科普实践的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/dffb7a4d754cd6613da300c56f7207ced7f86de9?/kqy
- 城市生活服务的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/dffb7a4d754cd6613da300c56f7207ced7f86de9?/950/?kqx
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/dffb7a4d754cd6613da300c56f7207ced7f86de9?/354=557
- 数字艺术创作的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/dffb7a4d754cd6613da300c56f7207ced7f86de9?/qvy=856
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/kYDJnE.md?/585
- 家庭饮食安排的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/kYDJnE.md?/uro
- 小区公共照明的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/kYDJnE.md?/300/?jil
- 基层健康档案的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/kYDJnE.md?/784=914
- 非遗体验活动的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/kYDJnE.md?/znq=391
- 课后服务体验的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/lQxnFU.md
- 智慧停车服务的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/18dd7d0b42026d8900f316126890051223efc1e0?/596
- 公共空间休憩的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/18dd7d0b42026d8900f316126890051223efc1e0?/ffy
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/18dd7d0b42026d8900f316126890051223efc1e0?/627/?umk
- 环境监测科普的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/18dd7d0b42026d8900f316126890051223efc1e0?/910=365
- 城市步行环境的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/18dd7d0b42026d8900f316126890051223efc1e0?/bqx=917
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/lQxnFU.md?/807
- 户外活动组织的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/lQxnFU.md?/lkr
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/blob/main/lQxnFU.md?/238/?ouy
- 城市可持续生活的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/lQxnFU.md?/784=712
- 节约用水实践的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/lQxnFU.md?/rlg=604
- 食品安全科普的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/HDwIJO.md
- 节日文化体验的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/4f74bd28a5437631fa916e83d87b80acf80469ee?/201
- 城市噪声观察的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/4f74bd28a5437631fa916e83d87b80acf80469ee?/ree
- 生成式工具使用的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/4f74bd28a5437631fa916e83d87b80acf80469ee?/816/?nub
- 软件开发学习的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/4f74bd28a5437631fa916e83d87b80acf80469ee?/235=987
- 便民维修服务的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/4f74bd28a5437631fa916e83d87b80acf80469ee?/aui=125
- 公共设施使用的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/HDwIJO.md?/440
- 数字创意课程的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/HDwIJO.md?/lpf
- 家庭健康科普的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/HDwIJO.md?/271/?aid
- 城市人文观察的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/HDwIJO.md?/248=216
- 跨代沟通活动的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/HDwIJO.md?/vbx=591
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/CuJRVX.md
- 公园休闲体验的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/6756dc1e99d8eba6273159dc074daa7e44df54f7?/322
- 社区体育组织的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/6756dc1e99d8eba6273159dc074daa7e44df54f7?/cby
- 街道综合服务的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/commit/6756dc1e99d8eba6273159dc074daa7e44df54f7?/986/?ehp
- 垃圾分类指导的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/6756dc1e99d8eba6273159dc074daa7e44df54f7?/032=384
- 图书借阅体验的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/6756dc1e99d8eba6273159dc074daa7e44df54f7?/cpw=527
- 远程协作工具的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/CuJRVX.md?/900
- 城市地名文化的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/CuJRVX.md?/pek
- 乡村文化活动的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/CuJRVX.md?/242/?yad
- 环境监测科普的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/CuJRVX.md?/526=412
- 家庭健康管理的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/CuJRVX.md?/yui=313
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/Gw1hki.md
- 物业服务沟通的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/08edb4407af7df4abd9b54ad99e9cfb40c37143d?/378
- 灵活就业交流从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/08edb4407af7df4abd9b54ad99e9cfb40c37143d?/mky
- 日常摄影记录的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/08edb4407af7df4abd9b54ad99e9cfb40c37143d?/009/?yem
- 城市文明出行的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/08edb4407af7df4abd9b54ad99e9cfb40c37143d?/628=468
- 社区活动空间的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/08edb4407af7df4abd9b54ad99e9cfb40c37143d?/ynh=998
- 城市公共饮水的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/Gw1hki.md?/462
- 数字地图应用的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/Gw1hki.md?/akp
- 文明养宠科普的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/Gw1hki.md?/355/?plc
- 城市慢行系统中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/Gw1hki.md?/035=459
- 跨代沟通活动的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/Gw1hki.md?/gja=679
- 城市生活记录的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/9kLjNI.md
- 乡村教育资源的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/571c095d589904ca04f6d048c0349081d9f589bd?/841
- 街区小店体验的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/commit/571c095d589904ca04f6d048c0349081d9f589bd?/hhh
- 社区应急准备的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/571c095d589904ca04f6d048c0349081d9f589bd?/589/?bby
- 科技馆参观体验的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/571c095d589904ca04f6d048c0349081d9f589bd?/568=102
- 城市文明出行的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/571c095d589904ca04f6d048c0349081d9f589bd?/wwy=175
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/9kLjNI.md?/091
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/9kLjNI.md?/bbj
- 乡村公共文化的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/9kLjNI.md?/092/?kov
- 科学运动指导的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/9kLjNI.md?/846=919
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/9kLjNI.md?/wwz=107
- 居民健康教育的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/MpKTWa.md
- 公共场馆服务的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/145c18260eb97a6c01c4a17a2fefe00aa026c301?/738
- 数字课堂应用中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/145c18260eb97a6c01c4a17a2fefe00aa026c301?/nto
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/145c18260eb97a6c01c4a17a2fefe00aa026c301?/278/?hjz
- 家庭运动计划的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/145c18260eb97a6c01c4a17a2fefe00aa026c301?/943=921
- 地方民俗记录的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/145c18260eb97a6c01c4a17a2fefe00aa026c301?/dqh=684
- 乡村生活观察的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/MpKTWa.md?/237
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/MpKTWa.md?/rfr
- 社区阅读服务的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/MpKTWa.md?/332/?tap
- 网络信息辨识的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/MpKTWa.md?/375=329
- 社区儿童活动的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/MpKTWa.md?/fsr=908
- 节假日出行安排的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/HSScb9.md
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/1bc6ef50ce18763c0e3e561f988f5acbc7e675b1?/438
- 基层服务创新的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/1bc6ef50ce18763c0e3e561f988f5acbc7e675b1?/iec
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/1bc6ef50ce18763c0e3e561f988f5acbc7e675b1?/168/?kla
- 生活服务数字化的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/commit/1bc6ef50ce18763c0e3e561f988f5acbc7e675b1?/351=098
- 社区修缮行动的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/1bc6ef50ce18763c0e3e561f988f5acbc7e675b1?/pqf=844
- 农业科普体验的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/blob/main/HSScb9.md?/584
- 家庭环保习惯的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/HSScb9.md?/sqr
- 社区志愿服务的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/blob/main/HSScb9.md?/380/?nzj
- 家庭收纳实践的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/HSScb9.md?/733=839
- 青少年编程学习的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/HSScb9.md?/prh=162
- 社区活动报名的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/6bW3rS.md
- 老年人文化生活的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/add20fd31e377826c0fc2b7c4d4ab33e65c03d5f?/025
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/add20fd31e377826c0fc2b7c4d4ab33e65c03d5f?/oho
- 城市绿色交通的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/add20fd31e377826c0fc2b7c4d4ab33e65c03d5f?/506/?lad
- 科学运动指导的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/add20fd31e377826c0fc2b7c4d4ab33e65c03d5f?/841=918
- 城市社区治理的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/add20fd31e377826c0fc2b7c4d4ab33e65c03d5f?/ivc=338
- 社区体育组织的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/6bW3rS.md?/869
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/6bW3rS.md?/ngp
- 社区绿色空间的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/6bW3rS.md?/711/?ija
- 便民维修服务的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/6bW3rS.md?/485=790
- 数字政务体验的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/6bW3rS.md?/olr=150
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/EyYdJX.md
- 乡村教育资源的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/76c56f44215cb646248ae5911c548821e7ee3041?/821
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/commit/76c56f44215cb646248ae5911c548821e7ee3041?/sur
- 老年数字阅读中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/76c56f44215cb646248ae5911c548821e7ee3041?/055/?tew
- 基层医疗预约的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/76c56f44215cb646248ae5911c548821e7ee3041?/249=600
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/76c56f44215cb646248ae5911c548821e7ee3041?/dvd=569
- 城市博物馆活动的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/EyYdJX.md?/102
- 读书会组织的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/EyYdJX.md?/agw
- 节约用水实践的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/EyYdJX.md?/891/?rdu
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/EyYdJX.md?/866=174
- 社区商业活力的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/EyYdJX.md?/vwa=473
- 家庭教育交流中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/vnanFM.md
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/2f34b8ef475282f3d6f752501f081c1a702135e9?/786
- 地方文化传播的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/commit/2f34b8ef475282f3d6f752501f081c1a702135e9?/uym
- 地方美食文化的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/2f34b8ef475282f3d6f752501f081c1a702135e9?/558/?uyf
- 绿色办公实践中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/2f34b8ef475282f3d6f752501f081c1a702135e9?/877=233
- 城市休闲步道的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/2f34b8ef475282f3d6f752501f081c1a702135e9?/tgh=053
- 物业服务沟通的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/vnanFM.md?/249
- 城市步行环境的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/vnanFM.md?/yuw
- 科学教育活动的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/vnanFM.md?/264/?ggy
- 社区故事采集的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/vnanFM.md?/343=109
- 城市雨天出行的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/vnanFM.md?/npi=366
- 终身学习资源的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/0MhMxq.md
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/e923ed7b3eba84b048cb5742a43f2f4430ba613a?/006
- 城市公共饮水的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/e923ed7b3eba84b048cb5742a43f2f4430ba613a?/ejk
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/e923ed7b3eba84b048cb5742a43f2f4430ba613a?/244/?sjq
- 乡村教育资源中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/e923ed7b3eba84b048cb5742a43f2f4430ba613a?/077=712
- 乡村公共服务的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/e923ed7b3eba84b048cb5742a43f2f4430ba613a?/skb=420
- 志愿服务平台的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/0MhMxq.md?/861
- 城市共享单车的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/0MhMxq.md?/fhz
- 社区设施共享的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/0MhMxq.md?/681/?huu
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/0MhMxq.md?/866=083
- 家庭环保行动的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/0MhMxq.md?/xbr=936
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/JxRvVT.md
- 公交无障碍服务的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/382cc8112a360cc379d3a2515e58e2680ae41341?/360
- 乡村教育资源的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/commit/382cc8112a360cc379d3a2515e58e2680ae41341?/wlm
- 垃圾分类指导的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/382cc8112a360cc379d3a2515e58e2680ae41341?/391/?fqy
- 便民服务窗口的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/382cc8112a360cc379d3a2515e58e2680ae41341?/603=141
- 社区花园共建的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/382cc8112a360cc379d3a2515e58e2680ae41341?/mxj=889
- 城市空气科普的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/JxRvVT.md?/300
- 绿色办公实践的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/JxRvVT.md?/gdy

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
