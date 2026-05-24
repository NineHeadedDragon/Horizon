---
layout: default
title: "Horizon Summary: 2026-05-24 (ZH)"
date: 2026-05-24
lang: zh
---

> 从 27 条内容中筛选出 7 条重要资讯。

---

1. [APKPure 上的 Telegram 被植入间谍后门窃取数据](#item-1) ⭐️ 9.0/10
2. [微软开源最早的 DOS 源代码](#item-2) ⭐️ 8.0/10
3. [唤醒！16 字节：极致极简主义的视听演示](#item-3) ⭐️ 8.0/10
4. [AI 对 HBM 的需求推高消费电子产品价格](#item-4) ⭐️ 8.0/10
5. [微软内部大规模推广 Claude Code，非程序员也可使用](#item-5) ⭐️ 8.0/10
6. [富途控股拟被罚 18.5 亿元，老虎证券被罚 4.11 亿元](#item-6) ⭐️ 8.0/10
7. [海盗船采用长鑫存储 DRAM 芯片，DDR5 价格或下调](#item-7) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [APKPure 上的 Telegram 被植入间谍后门窃取数据](https://x.com/EricParker/status/2058411298195661221) ⭐️ 9.0/10

APKPure 上发布的 Telegram 12.6.5 版本被重新签名并注入了名为 DataCollector 的间谍框架，能够窃取聊天记录、通讯录、照片、GPS 和 SIM 卡信息，经加密后上传至 C2 服务器 38.190.225.166。 这一严重安全事件动摇了用户对第三方应用商店的信任，数百万从 APKPure 下载 Telegram 的用户面临全面数据窃取的风险，可能导致隐私泄露和财产损失。 恶意代码位于 classes3.dex 中，代码量超过 3000 行，使用 AES-GCM 加密进行数据外泄，且应用的签名密钥并非 Telegram 官方所有。从 APKPure 安装的用户应立即卸载并下载官方版本。

telegram · zaihuapd · 5月24日 11:38

**背景**: APKPure 是一个第三方 Android 应用商店，常提供 Google Play 上未上架的 APK 文件。Telegram 是一款广泛使用的云消息应用，以其安全性著称。重新打包是指修改官方应用并植入恶意代码，同时保留其外观，诱骗用户安装带有后门的版本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://kod.ru/telegram-s-apkpure-virus">В Telegram со стороннего магазина APKPure нашли...</a></li>
<li><a href="https://apkpure.net/telegram/org.telegram.messenger/download">Download Telegram 12.7.1 APK for Android - Free and Safe Download</a></li>

</ul>
</details>

**标签**: `#security`, `#malware`, `#backdoor`, `#spyware`, `#Telegram`

---

<a id="item-2"></a>
## [微软开源最早的 DOS 源代码](https://arstechnica.com/gadgets/2026/04/microsoft-open-sources-the-earliest-dos-source-code-discovered-to-date/) ⭐️ 8.0/10

微软已经开源了已知最早的 MS-DOS 源代码，包括 86-DOS 内核和实用程序，这些代码是由 DOS 反汇编小组通过 OCR 从纸质打印件中辛苦恢复的。 此次发布为人们提供了对启动 PC 革命的操作系统起源前所未有的洞察，为研究人员、业余爱好者和复古计算爱好者提供了历史价值。 源代码是从车库中发现的打印清单中恢复的，现代 OCR 软件对数十年前的打印质量处理困难，需要专门团队手动转录。

hackernews · DamnInteresting · 5月24日 01:21 · [社区讨论](https://news.ycombinator.com/item?id=48253386)

**背景**: MS-DOS 是早期 IBM PC 的基础操作系统，最初由 Seattle Computer Products 开发为 86-DOS，并由微软授权。此次早期代码的开源使开发者能够研究在早期 x86 硬件上运行的极简汇编语言。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/microsoft/MS-DOS">GitHub - microsoft/MS- DOS : The original sources of MS- DOS 1.25...</a></li>
<li><a href="https://computerhistory.org/blog/microsoft-ms-dos-early-source-code/">Microsoft MS- DOS early source code - CHM</a></li>
<li><a href="https://onehack.st/t/microsoft-just-open-sourced-45-year-old-dos-code-found-on-paper-printouts-in-a-garage/322059">Microsoft Just Open-Sourced 45-Year-Old DOS Code Found on Paper ...</a></li>

</ul>
</details>

**社区讨论**: 社区反应基本积极，许多人感谢微软保护了计算历史。一些评论者指出同时开源的早期 Microsoft BASIC 的重要性，其他评论者则表达了对那个时代能通过几千行汇编代码创办软件公司的怀旧之情。

**标签**: `#open-source`, `#DOS`, `#Microsoft`, `#software history`, `#retrocomputing`

---

<a id="item-3"></a>
## [唤醒！16 字节：极致极简主义的视听演示](https://hellmood.111mb.de/wake_up_16b_writeup.html) ⭐️ 8.0/10

一个名为“唤醒！”的 16 字节可执行程序生成了令人印象深刻的视听演示，包含画面和声音，将极简编程推向极限。 这一成就展示了大小编码艺术的巅峰，激励程序员探索创造性约束。它表明即便只有 16 字节，程序也能提供丰富且引人入胜的体验。 该演示包含视觉效果和声音，这在如此微小的 intro 中实属罕见。实现这一点可能需要利用系统调用、自修改代码以及精心选择指令。

hackernews · MaximilianEmel · 5月24日 00:30 · [社区讨论](https://news.ycombinator.com/item?id=48253060)

**背景**: Demoscene（演示场景）是一个国际计算机艺术亚文化，创作称为 demo 的小型自包含程序，通常有大小限制（如 64K、4K intro）。大小编码技术旨在生成尽可能小的可执行文件，同时仍产生令人印象深刻的视听输出。16 字节的演示极为罕见，被认为是极简主义的杰作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Demoscene">Demoscene</a></li>
<li><a href="http://www.sizecoding.org/wiki/Main_Page">SizeCoding</a></li>

</ul>
</details>

**社区讨论**: 评论者对这一成就表示惊叹，有人称这让他们深入探究，最终看到了用 PowerPoint 构建的谢尔宾斯基三角形。其他人将其与其他小型演示比较，并称之为杰作，感叹行业工作很少提供这样的创作自由。

**标签**: `#demoscene`, `#minimalism`, `#programming`, `#creativity`, `#assembly`

---

<a id="item-4"></a>
## [AI 对 HBM 的需求推高消费电子产品价格](https://simonwillison.net/2026/May/22/memory-shortage/#atom-everything) ⭐️ 8.0/10

内存制造商正将晶圆产能从 DDR 和 LPDDR 内存生产转向用于 AI 数据中心的高带宽内存（HBM），导致消费电子产品价格重新定价，尤其在 100 美元以下的智能手机市场。 这一转变意味着智能手机和 PC 等消费设备将在未来几年显著涨价，影响全球市场，尤其对非洲和南亚等价格敏感地区冲击更大。 HBM 每 GB 消耗的晶圆容量是 DDR 或 LPDDR 的三倍以上，其晶圆分配预计从 2%升至 2026 年底的 20%，挤压了消费级内存的供应。

rss · Simon Willison · 5月22日 22:01

**背景**: 全球仅有三大内存制造商，晶圆产能固定。HBM 是一种用于 AI GPU 的 3D 堆叠内存，虽提供高带宽，但每 GB 消耗更多晶圆资源。AI 数据中心需求的激增正推动内存生产结构性转变，优先生产 HBM，挤压用于消费电子的 DDR 和 LPDDR 等通用 DRAM 产能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://semiwiki.com/wikis/semiconductor-ip-wikis/ddr-vs-lpddr-vs-hbm-wiki/">DDR vs. LPDDR vs. HBM Wiki - SemiWiki</a></li>
<li><a href="https://www.fusionww.com/insights/blog/ai-sets-the-price-why-dram-shortages-are-rewriting-memory-market-economics">AI Sets the Price: Why DRAM Shortages Are Rewriting Memory ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>

</ul>
</details>

**标签**: `#memory shortage`, `#AI demand`, `#consumer electronics`, `#HBM`, `#hardware pricing`

---

<a id="item-5"></a>
## [微软内部大规模推广 Claude Code，非程序员也可使用](https://t.me/zaihuapd/41535) ⭐️ 8.0/10

微软正在其核心工程团队（包括 CoreAI 团队以及负责 Windows 和 Microsoft 365 的体验与设备部门）广泛推广 Anthropic 的 Claude Code。此外，微软还要求软件工程师同时使用 Claude Code 和 GitHub Copilot 并提交对比反馈。 此举表明微软愿意采用竞争对手的 AI 编程工具，即便它自己也在销售 GitHub Copilot，这可能会重塑 AI 辅助编程的格局。鼓励非技术员工使用 Claude Code 进行原型设计，也凸显了其推动软件开发民主化的潜力。 微软特别要求负责 Windows、Microsoft 365 和 Outlook 的团队安装 Claude Code。同时，工程师被要求并行对比 Claude Code 和 GitHub Copilot，以收集性能数据，为未来的工具选型提供依据。

telegram · zaihuapd · 5月23日 06:05

**背景**: Claude Code 是由 Anthropic 公司开发的 AI 编程助手，该公司也是 Claude 系列大语言模型的开发商。它直接与微软旗下的 GitHub Copilot 竞争。Anthropic 采用'宪法 AI'技术训练 Claude，以提升道德合规性。该工具旨在帮助开发者直接在 IDE 或终端中编写、调试和重构代码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**标签**: `#AI programming tools`, `#Microsoft`, `#Claude Code`, `#GitHub Copilot`, `#software engineering`

---

<a id="item-6"></a>
## [富途控股拟被罚 18.5 亿元，老虎证券被罚 4.11 亿元](https://t.me/zaihuapd/41539) ⭐️ 8.0/10

中国监管机构拟对富途控股（18.5 亿元）和老虎证券（4.11 亿元）处以总计约 22.6 亿元的罚款，原因是它们未获许可在中国大陆开展证券业务。相关公司须整改或停止这些业务。 此举突显了中国对无牌跨境金融服务加强执法，可能影响数百万使用这些平台进行海外交易的内地投资者。这也预示着对外国金融科技公司监管环境将更加严格。 处罚包括没收违法所得和罚款。富途创始人李华面临 125 万元个人罚款。这些罚款尚属初步决定，需经过后续程序并等待最终裁定。

telegram · zaihuapd · 5月23日 10:58

**背景**: 富途控股和老虎证券是总部位于香港的在线券商，深受内地投资者青睐用于交易美股和港股。它们一直未取得中国证券监管机构的直接许可而运营，中国通常禁止离岸券商招揽内地客户。此次打击是中国控制资本外流、确保证券法合规的更大监管行动的一部分。

**标签**: `#fintech`, `#regulation`, `#China`, `#securities`, `#cross-border`

---

<a id="item-7"></a>
## [海盗船采用长鑫存储 DRAM 芯片，DDR5 价格或下调](https://thenextweb.com/news/chinese-dram-cxmt-corsair-ddr5-memory-prices) ⭐️ 8.0/10

美商海盗船已开始在其 DDR5 内存模组中采用长鑫存储（CXMT）的 DRAM 芯片，目前 6000 MT/s 规格的内存已上市，性能与国际主流产品一致。 这一转变标志着市场对中国 DRAM 供应商的接受度提高，可能降低消费者的 DDR5 价格，因为全球 DRAM 供应因产能转向 AI 所需的高带宽内存（HBM）而紧张。 全球 DRAM 巨头（三星、SK 海力士、美光）优先生产 AI 所需的 HBM，导致消费级 DRAM 短缺。长鑫存储计划在 2026 年大规模扩产并上市，业内专家预计 DDR5 价格将在 2027 年下半年明显回落。

telegram · zaihuapd · 5月23日 11:17

**背景**: DRAM（动态随机存取存储器）是计算机和设备中使用的一种易失性内存。长鑫存储是一家中国 DRAM 制造商，成立于 2016 年，总部位于安徽合肥。目前 DRAM 市场由三星、SK 海力士和美光三家公司主导。高带宽内存（HBM）是一种 3D 堆叠 DRAM 接口，主要用于 AI 加速器和高性能计算，其需求激增导致制造商将产能从标准 DDR5 生产转移。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Changxin_Memory_Technologies">ChangXin Memory Technologies - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>

</ul>
</details>

**标签**: `#DRAM`, `#Corsair`, `#CXMT`, `#memory pricing`, `#supply chain`

---