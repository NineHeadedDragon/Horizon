---
layout: default
title: "Horizon Summary: 2026-05-25 (ZH)"
date: 2026-05-25
lang: zh
---

> 从 35 条内容中筛选出 11 条重要资讯。

---

1. [微粗糙度降低阻力，推翻航空工程原理](#item-1) ⭐️ 9.0/10
2. [APKPure 上的 Telegram 版本被植入间谍后门](#item-2) ⭐️ 9.0/10
3. [Epic 公开虚幻引擎 6，首秀游戏《火箭联盟》](#item-3) ⭐️ 9.0/10
4. [Show HN：免费开源网页版多轨音频编辑器](#item-4) ⭐️ 8.0/10
5. [DeepSeek Reasonix：利用高缓存实现低成本的原生编码代理](#item-5) ⭐️ 8.0/10
6. [从 Go 迁移到 Rust 的指南引发语言争论](#item-6) ⭐️ 8.0/10
7. [LLM 代理的约束衰减：后端代码生成脆弱性](#item-7) ⭐️ 8.0/10
8. [微软开源已知最早的 DOS 源代码](#item-8) ⭐️ 8.0/10
9. [内存现占 AI 芯片成本近三分之二](#item-9) ⭐️ 8.0/10
10. [Armin Ronacher 批评 AI 生成的错误报告](#item-10) ⭐️ 8.0/10
11. [马斯克宣布 Grok V9-Medium（1.5T）训练完成](#item-11) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [微粗糙度降低阻力，推翻航空工程原理](https://www.wired.com/story/a-fundamental-principle-of-aeronautical-engineering-has-been-overturned/) ⭐️ 9.0/10

日本东北大学的一项研究推翻了长期以来的观点，即表面越光滑空气阻力越小。他们发现分布式微粗糙度可以延迟层流到湍流的转换，在风洞测试中阻力降低高达 43.6%。 这一发现挑战了航空工程的基本原理，可能导致更高效的飞机设计，减少燃料消耗和排放。它也与其他领域（如帆船和高尔夫球设计）的理解统一起来，在这些领域中已知粗糙度有助于性能提升。 所使用的微粗糙度在 1000 至 1500 目砂纸范围内，与竞技帆船手使用的类似。该研究发表在《流体力学杂志》上，而 Ichiro Tani 于 1940 年的原始研究在 1989 年已被重新解释以暗示这一效应。

hackernews · littlexsparkee · 5月24日 19:10 · [社区讨论](https://news.ycombinator.com/item?id=48260117)

**背景**: 在流体动力学中，边界层流动可以是层流（平滑）或湍流（混乱）。层流具有较小的表面摩擦，但不稳定，可能转变为湍流，增加阻力。人们认为表面粗糙度会触发早期转换，因此表面保持光滑。然而，这项研究表明微粗糙度可以通过抑制扰动来稳定层流，延迟转换并减少阻力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Laminar–turbulent_transition">Laminar – turbulent transition - Wikipedia</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0142727X23001297">Drag reduction effect of distributed roughness on the transitional flow state using direct numerical simulation - ScienceDirect</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，竞技帆船手早已知道细砂纸能改善水动力学，质疑为何未应用于空气动力学。其他人则提到了 Tani 1940 年研究及其 1989 年重新解释的历史背景。一些人对如此简单的效应早前未被理解表示惊讶，而另一些人则讨论了飞机制造的实际影响。

**标签**: `#aeronautics`, `#fluid dynamics`, `#drag reduction`, `#surface roughness`, `#laminar flow`

---

<a id="item-2"></a>
## [APKPure 上的 Telegram 版本被植入间谍后门](https://x.com/EricParker/status/2058411298195661221) ⭐️ 9.0/10

在 APKPure 上分发的重打包 Telegram 12.6.5 版本被发现包含 DataCollector 间谍软件框架，该框架可窃取聊天记录、通讯录、照片和其他敏感数据。 此事件危及了数百万从 APKPure 下载 Telegram 的用户的隐私，突显了第三方应用商店的安全风险以及验证应用完整性的重要性。 该后门在 classes3.dex 中注入了名为 DataCollector 的 3000 多行代码模块，使用 AES-GCM 加密窃取的数据，并将其外泄至命令与控制服务器 38.190.225.166。

telegram · zaihuapd · 5月24日 11:38

**背景**: APKPure 是一个第三方 Android 应用商店，提供包括 Telegram 在内的各种应用的 APK 文件，Telegram 是一个流行的安全通信平台。像 DataCollector 这样的间谍软件框架旨在静默窃取个人信息。AES-GCM 是一种高级加密标准，提供机密性和真实性，常用于保护传输中的数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41597-024-03027-3">AndroDex: Android Dex Images of Obfuscated Malware</a></li>
<li><a href="https://medium.com/@thomas_40553/how-to-secure-encrypt-and-decrypt-data-within-the-browser-with-aes-gcm-and-pbkdf2-057b839c96b6">The Ultimate Developer’s Guide to AES - GCM : Encrypt and... | Medium</a></li>

</ul>
</details>

**标签**: `#安全`, `#间谍软件`, `#Telegram`, `#APKPure`, `#后门`

---

<a id="item-3"></a>
## [Epic 公开虚幻引擎 6，首秀游戏《火箭联盟》](https://www.pcgamer.com/gaming-industry/epic-reveals-first-unreal-engine-6-game-and-its-not-fortnite/) ⭐️ 9.0/10

Epic Games 在巴黎《火箭联盟》冠军系列赛上公开了虚幻引擎 6，并宣布《火箭联盟》将从虚幻引擎 3 直接跨代升级至 UE6，完全跳过 UE5。 这标志着 Epic 的重大战略转变，展示了跨越式升级路径，可能影响游戏开发生态和 Epic 的元宇宙布局，尤其是在 UE5 的 PC 端优化饱受批评的背景下。 《火箭联盟》最初基于 Xbox 360 时代的 UE3，此次直接跨越至 UE6，升级幅度堪比续作。UE6 预告片中还出现了《堡垒之夜》等游戏的片段，暗示了统一元宇宙平台的意图。

telegram · zaihuapd · 5月25日 02:20

**背景**: 虚幻引擎 5 发布四年来已成为影视和游戏行业最广泛使用的中间件之一，但在 PC 端因性能问题屡遭批评。Epic 决定让《火箭联盟》直接从 UE3 跳升至 UE6，表明其希望绕过 UE5 的优化问题，将未来开发统一到新引擎上。

**标签**: `#游戏引擎`, `#虚幻引擎6`, `#Epic Games`, `#Rocket League`, `#行业新闻`

---

<a id="item-4"></a>
## [Show HN：免费开源网页版多轨音频编辑器](https://audiomass.co/?multitrack=1) ⭐️ 8.0/10

Audiomass 是一款免费开源的多轨音频编辑器，完全在网页浏览器中运行，在 Hacker News 上展示后获得 412 分和 88 条评论。 该工具填补了无需重型桌面软件即可快速编辑音频的需求，对于开发者、音乐人以及任何需要在浏览器中快速进行波形编辑的人来说非常有用。 该编辑器支持实时效果、多轨叠加，并且默认支持 .flac 文件；不过，某些功能如淡入淡出时间控制尚未实现。

hackernews · pantelisk · 5月24日 15:25 · [社区讨论](https://news.ycombinator.com/item?id=48258015)

**背景**: 基于网页的音频编辑器允许用户无需安装软件即可录制、编辑和制作音频。Audiomass 使用现代网络技术构建，完全开源，提供了类似于 Cool Edit Pro 等经典工具的直观用户界面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://audiomass.co/">AudioMass - Audio Editor</a></li>

</ul>
</details>

**社区讨论**: Hacker News 社区反响热烈，称赞其直观的用户体验以及对 .flac 文件的支持。一些用户希望增加云端协作功能和更精细的效果控制，另一些用户则对项目使用的编码风格表示怀旧。

**标签**: `#audio editing`, `#open source`, `#web app`, `#music production`, `#Hacker News Show HN`

---

<a id="item-5"></a>
## [DeepSeek Reasonix：利用高缓存实现低成本的原生编码代理](https://esengine.github.io/DeepSeek-Reasonix/) ⭐️ 8.0/10

DeepSeek Reasonix 是一个专为 DeepSeek API 设计的原生编码代理，利用前缀缓存稳定性来降低成本。它旨在通过缓存优先的循环为终端用户提供高效的 AI 编码辅助。 Reasonix 展示了针对特定模型缓存行为进行优化可以大幅降低运营成本，从而可能使 AI 辅助编码更加普及。它也凸显了模型原生工具这一日益增长的趋势。 Reasonix 仅针对 DeepSeek 模型，因为其循环不变量是围绕 DeepSeek 的缓存机制设计的。该代理在终端中运行，直接与 api.deepseek.com 通信，无需翻译层。

hackernews · Alifatisk · 5月24日 13:02 · [社区讨论](https://news.ycombinator.com/item?id=48256953)

**背景**: AI 中的缓存通过存储和重用先前结果来降低成本和延迟。DeepSeek 提供前缀缓存，可以显著降低重复或相似输入的令牌使用量。Reasonix 旨在通过保持请求中稳定的前缀来最大化缓存命中率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/esengine/deepseek-reasonix">GitHub - esengine/DeepSeek-Reasonix: DeepSeek-native AI ...</a></li>
<li><a href="https://esengine.github.io/DeepSeek-Reasonix/">Reasonix — DeepSeek-native AI coding agent for your terminal</a></li>
<li><a href="https://api-docs.deepseek.com/quick_start/agent_integrations/reasonix">Integrate with Reasonix | DeepSeek API Docs</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一；一些用户赞赏缓存效率，但批评网站的 UX 并质疑是否需要专门的代理。一位评论者指出，通用的 harness 已经有效处理了缓存。

**标签**: `#DeepSeek`, `#caching`, `#coding agent`, `#AI`, `#cost optimization`

---

<a id="item-6"></a>
## [从 Go 迁移到 Rust 的指南引发语言争论](https://corrode.dev/learn/migration-guides/go-to-rust/) ⭐️ 8.0/10

一篇从 Go 迁移到 Rust 的全面指南发布，引发了社区关于两种语言权衡的广泛讨论，特别是在错误处理、托管运行时与包管理方面。 此讨论突显了软件工程社区中关于为后端开发选择 Go 还是 Rust 的持续辩论，影响着语言采用和项目架构的决策。 该指南承认 Go 的简洁性，但指出 Rust 通过'?'操作符实现了更优的错误处理；社区评论则强调托管运行时的权衡，以及 Rust 相比于 Go 精简标准库的庞大依赖树。

hackernews · jabits · 5月24日 18:31 · [社区讨论](https://news.ycombinator.com/item?id=48259808)

**背景**: Go 和 Rust 都是现代系统编程语言，但它们的设计理念不同：Go 优先考虑简洁性和带有垃圾回收的托管运行时，而 Rust 则通过借用检查器在不使用垃圾回收器的情况下实现内存安全。这些差异使得两者之间的选择高度依赖具体场景，通常取决于性能要求和团队专长。

**社区讨论**: 评论者就托管运行时的优劣展开辩论，有人认为 Go 的垃圾回收比 Rust 的复杂性负担更小。其他人则对 Rust 的包管理以及指南的真实性表示担忧，怀疑其内容是由 AI 生成的。

**标签**: `#Go`, `#Rust`, `#migration`, `#programming languages`, `#web backend`

---

<a id="item-7"></a>
## [LLM 代理的约束衰减：后端代码生成脆弱性](https://arxiv.org/abs/2605.06445) ⭐️ 8.0/10

该论文提出“约束衰减”概念，证明 LLM 编码代理在多文件后端代码生成任务中，当需要遵循 ORM 映射和框架约定等具体架构约束时，性能显著下降约 30 个百分点。 这一发现凸显了 LLM 代理在无约束编码方面令人印象深刻的能力与在生产级软件开发中所需的严格遵守架构规则之间的关键差距，强调需要在 AI 辅助编码工具中改进约束处理能力。 该研究在多个 LLM 代理上评估了多文件后端生成基准，发现约束条件下断言通过率从无约束时的约 90%下降到约 60%。值得注意的是，由于成本原因，论文未测试 GPT-4 或 Claude 3.5 等前沿模型，这可能影响结论的普适性。

hackernews · wek · 5月24日 12:55 · [社区讨论](https://news.ycombinator.com/item?id=48256912)

**背景**: 在软件工程中，生产级后端代码必须遵循特定的架构模式、ORM 配置和框架约定，以确保可维护性和可扩展性。现有的 LLM 代码生成基准通常关注单文件任务的功能正确性，忽略了这些结构约束。本论文通过系统评估 LLM 代理在真实约束下的表现，填补了这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2605.06445">[2605.06445] Constraint Decay: The Fragility of LLM Agents in Backend ...</a></li>
<li><a href="https://www.agentpatterns.ai/verification/constraint-decay-backend-agents/">Constraint Decay in Backend Code Generation - agentpatterns.ai</a></li>
<li><a href="https://www.knowlab.io/content/30febb02-ec40-4138-8212-025d65f0a583/">Constraint Decay: The Fragility of LLM Agents in Backend Code ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论普遍认同论文的发现，用户分享了 LLM 在约束下性能下降的经历。有人指出，逐步引入约束而非一次性添加可以缓解衰减，并提到一种称为“固化”的相关现象，即代理反复强化现有模式。一个被指出的局限是未包含前沿模型，其表现可能不同。

**标签**: `#LLM agents`, `#code generation`, `#constraint decay`, `#production software`, `#AI reliability`

---

<a id="item-8"></a>
## [微软开源已知最早的 DOS 源代码](https://arstechnica.com/gadgets/2026/04/microsoft-open-sources-the-earliest-dos-source-code-discovered-to-date/) ⭐️ 8.0/10

微软开源了已知最早的 DOS 源代码，这段代码由历史学家和保存专家团队通过 OCR 从纸质打印输出中艰辛重建。 此次发布保存了计算历史的基础部分，使开发者和历史学家能够研究启动个人电脑革命的操作系统的早期起源。 源代码来自 DOS 原作者 Tim Paterson 提供的纸质打印输出，现代 OCR 软件难以处理年代久远的打印件，需要手动清理。

hackernews · DamnInteresting · 5月24日 01:21 · [社区讨论](https://news.ycombinator.com/item?id=48253386)

**背景**: DOS（磁盘操作系统）是 20 世纪 80 年代至 90 年代初 IBM PC 兼容机的主流操作系统。微软从西雅图电脑产品公司获得了早期版本的 DOS，并授权给 IBM，这成为该公司的关键转折点。已知最早的源代码已遗失数十年，因此这次重建和开源是一项重要的存档成就。

**社区讨论**: 社区普遍赞扬微软的这次发布，有人指出同样开源的 BASIC 解释器的历史重要性。评论者表达了对过去的怀念，并对当时仅需几千行汇编代码就能创立一家成功公司感到惊讶。

**标签**: `#open-source`, `#history`, `#DOS`, `#Microsoft`, `#software preservation`

---

<a id="item-9"></a>
## [内存现占 AI 芯片成本近三分之二](https://epoch.ai/data-insights/ai-chip-component-cost-shares) ⭐️ 8.0/10

根据 Epoch AI 的数据，内存占 AI 芯片组件成本的比例从 2024 年的约 13-14%上升至 2025 年的 63%，主要受 HBM 支出驱动。AI 芯片组件总支出从 2024 年的 220 亿美元激增至 2025 年的 520 亿美元。 这一变化意味着内存现已成为 AI 加速器的主要成本，从根本上改变了硬件定价和供应链动态。它可能导致 AI 训练和推理成本上升，影响从云计算到消费设备的一切，并凸显了内存供应的关键瓶颈。 HBM（高带宽内存）是主要推动力，据 Epoch AI 报道，仅 HBM 支出就占了成本增长的很大一部分。同期逻辑芯片成本占比保持在约 13-14%不变。

hackernews · intelkishan · 5月24日 16:31 · [社区讨论](https://news.ycombinator.com/item?id=48258684)

**背景**: HBM 是一种 3D 堆叠 DRAM 接口，用于 NVIDIA H100 和 B200 等 AI 加速器，提供高带宽。AI 热潮急剧增加了对内存的需求，但内存供应每年仅增长 20-25%，造成供需不匹配。这使得内存成为 AI 芯片中最大的组件成本，超过了逻辑芯片。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://epoch.ai/data-insights/ai-chip-component-cost-shares">AI Chip Component Costs: Memory at 63% | Epoch AI | Epoch AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://siliconanalysts.com/tools/cost-bridge">AI Chip Cost Bridge: Manufacturing Cost Breakdown for 18 Accelerators (2026) | Silicon Analysts</a></li>

</ul>
</details>

**社区讨论**: 评论者指出了不同的影响：有人预测一旦 DRAM 供应赶上需求，硬件成本可能降低约 3 倍；而其他人则指出消费级内存价格大幅上涨（例如，96GB 现价 1200 美元，两年前为 250 美元）。一些人表示，内存供应增长（每年 20-25%）不足以满足 AI 需求，不涉及 AI 的游戏玩家和 PC 爱好者正因高价而受苦。

**标签**: `#AI hardware`, `#memory costs`, `#chip components`, `#HBM`, `#semiconductor industry`

---

<a id="item-10"></a>
## [Armin Ronacher 批评 AI 生成的错误报告](https://simonwillison.net/2026/May/24/armin-ronacher/#atom-everything) ⭐️ 8.0/10

Flask 创始人 Armin Ronacher 批评了开源项目中大量出现的 AI 生成错误报告。他提出了一个简单的四行模板，要求问题报告聚焦于人类观察而非 AI 生成的推测。 这凸显了开源维护中一个日益严重的问题：低质量的 AI 生成报告浪费了维护者的时间。Ronacher 的模板可能有助于制定新的问题报告社区标准。 Ronacher 特别指出，AI 生成的报告通常包含自信但不准确的根因分析和虚假的最小复现。他提出的模板要求填写运行的确切命令、预期行为、实际行为以及错误日志。

rss · Simon Willison · 5月24日 18:46

**背景**: Armin Ronacher 是 Flask Web 框架的创建者，也是 Python 社区的杰出人物。随着开发者使用大语言模型草拟问题，AI 生成的错误报告变得越来越常见，但往往内容冗长且不准确，让维护者感到沮丧。

**标签**: `#open source`, `#AI`, `#bug reports`, `#software maintenance`, `#community standards`

---

<a id="item-11"></a>
## [马斯克宣布 Grok V9-Medium（1.5T）训练完成](https://x.com/elonmusk/status/2058787384364265734) ⭐️ 8.0/10

埃隆·马斯克宣布 xAI 已完成 Grok V9-Medium 模型的训练，该模型拥有 1.5 万亿参数，评估结果良好。目前正在进行微调，并计划在强化学习后于 2-3 周内向公众发布。 此次发布标志着从当前 0.5 万亿参数的 Grok 模型大幅升级，可能在复杂编程任务上带来显著改进。它凸显了 xAI 在竞争激烈的大型语言模型领域的快速进步。 Grok V9-Medium 模型的参数规模是当前 Grok 4.2 基础模型的三倍，其训练中加入了大量 Cursor 数据以增强编程能力。该模型将在发布前进行强化学习。

telegram · zaihuapd · 5月25日 07:07

**背景**: Grok 是埃隆·马斯克的公司 xAI 开发的一系列大型语言模型，旨在与 GPT-4 和 Claude 等模型竞争。Cursor 是一款基于人工智能的代码编辑器，提供代码生成和编辑辅助；将 Cursor 数据纳入训练旨在提升模型对代码的理解和生成能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.kucoin.com/news/flash/musk-s-xai-completes-grok-v9-medium-training-focuses-on-complex-programming">Musk's xAI Completes Training on Grok V 9 - Medium ... | KuCoin</a></li>
<li><a href="https://www.kucoin.com/news/flash/musk-announces-grok-v9-medium-1-5t-model-to-launch-in-2-3-weeks">Musk announces the launch of the Grok V 9 - Medium ( 1 . 5 T ) model in...</a></li>
<li><a href="https://digg.com/ai/2xkcq9ut?rank=28">xAI completes training run for Grok V 9 model · Digg</a></li>

</ul>
</details>

**标签**: `#Grok`, `#AI`, `#Large Language Model`, `#Elon Musk`, `#Machine Learning`

---