---
layout: default
title: "Horizon Summary: 2026-05-28 (ZH)"
date: 2026-05-28
lang: zh
---

> 从 40 条内容中筛选出 10 条重要资讯。

---

1. [微软 Copilot Cowork 漏洞可通过提示注入窃取文件](#item-1) ⭐️ 9.0/10
2. [GitHub 事故影响拉取请求、议题和 Git 操作](#item-2) ⭐️ 8.0/10
3. [Go 将实现对结构体的泛型方法支持](#item-3) ⭐️ 8.0/10
4. [科技 CEO 的 AI 炒作被批为‘精神病’](#item-4) ⭐️ 8.0/10
5. [私募股权接管美国关键服务](#item-5) ⭐️ 8.0/10
6. [SQLite 引入 AGENTS.md 政策拒绝 AI 代理代码](#item-6) ⭐️ 8.0/10
7. [AI 安全报告让 curl 维护者不堪重负](#item-7) ⭐️ 8.0/10
8. [NASA 公布月球基地计划细节，授予着陆器合同](#item-8) ⭐️ 8.0/10
9. [7-Zip 高危堆溢出漏洞已在 26.01 版本修复](#item-9) ⭐️ 8.0/10
10. [长鑫科技科创板 IPO 过会，拟募资 295 亿元](#item-10) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [微软 Copilot Cowork 漏洞可通过提示注入窃取文件](https://simonwillison.net/2026/May/26/copilot-cowork-exfiltrates-files/#atom-everything) ⭐️ 9.0/10

PromptArmor 披露了微软 Copilot Cowork 的一个漏洞，攻击者可通过发送包含外部图片的恶意邮件来窃取文件，当用户打开邮件时图片渲染会触发网络请求泄露数据。 该攻击利用了自动批准的代理操作和外部图片渲染，暴露了 AI 代理系统中的严重安全缺陷，凸显了在能够访问敏感数据的 LLM 代理中防范提示注入的持续挑战。 该漏洞利用了 OneDrive 预认证的下载链接，成功的提示注入可泄露这些链接，使攻击者能够下载文件。该攻击对包括 Claude Opus 4.7 在内的最先进模型取得了高成功率。

rss · Simon Willison · 5月26日 15:36

**背景**: 提示注入是一种网络安全攻击，通过恶意提示使 LLM 产生非预期行为。在如 Copilot Cowork 的代理系统中，代理可以执行发送邮件等操作，如果渲染了外部图片，则可能通过触发向攻击者控制的服务器发送网络请求来窃取数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.promptarmor.com/resources/microsoft-copilot-cowork-exfiltrates-files">Microsoft Copilot Cowork Exfiltrates Files</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>

</ul>
</details>

**标签**: `#security`, `#prompt injection`, `#Microsoft Copilot`, `#exfiltration`, `#AI agents`

---

<a id="item-2"></a>
## [GitHub 事故影响拉取请求、议题和 Git 操作](https://www.githubstatus.com/incidents/xy1tt3hs572m) ⭐️ 8.0/10

在最近一个未指定的日期，GitHub 发生了一起事故，影响了拉取请求、议题、Git 操作和 API 请求，导致不一致的行为，例如拉取请求未能反映所有提交或分支更改。 这一事故意义重大，因为它影响了软件开发协作所需的核心 GitHub 功能，并且是近期一系列中断的一部分，引发了人们对 GitHub 可靠性的担忧。 用户报告称，Web UI 和 API 上的拉取请求未能一致地反映所有提交或分支更改，这可能导致未经全面审查就合并代码。该事故加剧了过去一个月发生的系列中断。

hackernews · maxnoe · 5月27日 12:15 · [社区讨论](https://news.ycombinator.com/item?id=48293080)

**背景**: GitHub 是一个广泛使用的版本控制和协作平台，基于 Git。GitOps 是一种运营框架，将 Git 仓库作为基础设施和应用部署的唯一真实来源。此类中断会影响到依赖 GitHub 进行持续集成和交付的开发者和团队。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://about.gitlab.com/topics/gitops/">What is GitOps?</a></li>
<li><a href="https://www.redhat.com/en/topics/devops/what-is-gitops">What is GitOps?</a></li>
<li><a href="https://www.atlassian.com/git/tutorials/gitops">What Is GitOps? | Atlassian Git Tutorial</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了对于近期中断频率的沮丧和担忧。有用户创建了 'isgithubcooked.com' 网站来追踪可靠性，其他人则强调了由于 PR 状态不一致导致合并不完整代码的风险。还有人呼吁问责，包括建议解雇领导层。

**标签**: `#github`, `#outage`, `#gitops`, `#reliability`, `#infrastructure`

---

<a id="item-3"></a>
## [Go 将实现对结构体的泛型方法支持](https://github.com/golang/go/issues/77273) ⭐️ 8.0/10

Go 团队正在着手实现对结构体支持泛型方法，具体记录在 GitHub issue #77273 中。这将允许方法拥有独立于接收者类型参数的类型参数。 此特性弥补了 Go 泛型的一个重大空白，使得更富有表现力的库设计成为可能，例如通用数据访问模式和单子接口。它回应了社区长期以来的诉求，并使 Go 更接近其他静态类型语言的能力。 实现将允许在泛型结构体上使用泛型方法，但由于实现难度，泛型接口方法仍不被支持。该提议仍在 Go 团队内部进行技术讨论。

hackernews · f311a · 5月27日 09:02 · [社区讨论](https://news.ycombinator.com/item?id=48291575)

**背景**: Go 在 1.18 版本中引入了泛型，但最初不允许方法拥有独立于接收者的类型参数。这一限制在最初的设计中被认为是“现在不做，不代表永远不做”。自泛型引入以来，社区一直积极请求这一特性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/golang/go/issues/77273">spec: generic methods for Go · Issue #77273 · golang/go</a></li>
<li><a href="https://go.dev/doc/tutorial/generics">Tutorial: Getting started with generics - The Go Programming Language</a></li>
<li><a href="https://www.digitalocean.com/community/tutorials/how-to-use-generics-in-go">How To Use Generics in Go | DigitalOcean</a></li>

</ul>
</details>

**社区讨论**: 社区反应总体积极，如 xena 用户对于构建单子库感到兴奋，nasretdinov 指出最初对缺乏泛型方法感到惊讶。一些评论者如 h1fra 讽刺地观察到 Go 现在正在实现之前被认为不必要的特性，而 reactordev 则认可这一方向，认为它弥合了与其他语言的差距。

**标签**: `#Go`, `#generics`, `#programming languages`, `#open source`

---

<a id="item-4"></a>
## [科技 CEO 的 AI 炒作被批为‘精神病’](https://techcrunch.com/2026/05/27/tech-ceos-are-apparently-suffering-from-ai-psychosis/) ⭐️ 8.0/10

TechCrunch 上的一篇评论文章和 Hacker News 的讨论指责科技 CEO 们患上了‘AI 精神病’，其特点是对 AI 能力非理性的过度自信。文章认为，CEO 们往往缺乏技术理解，却对 AI 能实现什么做出笼统的断言。 这一批评凸显了科技行业中对炒作驱动决策日益增长的担忧。过高的期望可能导致资源错配和不切实际的产品承诺，影响投资者、员工和最终用户。 文章将 CEO 的行为比作精神病，即他们在不了解底层技术的情况下依据信念行事。社区评论指出，类似的动态在之前的科技泡沫（如云计算和移动互联网）中也曾出现，并且这种现象并非 AI 独有。

hackernews · IAmGraydon · 5月27日 15:20 · [社区讨论](https://news.ycombinator.com/item?id=48295679)

**背景**: 这篇评论文章是围绕 AI 炒作周期的持续辩论的一部分，公司在实际理解有限的情况下匆忙将 AI 融入产品。历史上，类似的热潮曾伴随区块链和元宇宙等技术。‘精神病’一词是比喻性的，用来批评科技领导者中出现的非理性狂热和过度承诺。

**社区讨论**: Hacker News 社区在很大程度上同意这一批评，许多人指出这种过度炒作在科技行业并不新鲜。一些用户分享了成功 AI 应用的个人经历，但警告不要从这些例子中过度推断。一个关键观点是，领导层往往缺乏技术深度，导致不切实际的期望和糟糕的决策。

**标签**: `#AI`, `#tech industry`, `#critique`, `#hype`, `#community discussion`

---

<a id="item-5"></a>
## [私募股权接管美国关键服务](https://rubbishtalk.com/economy/how-private-equity-bought-americas-essential-services/) ⭐️ 8.0/10

本文分析了私募股权公司如何主要因养老基金对高回报的需求而收购美国关键基础设施控制权。 这一发展对经济具有系统性影响，因为关键服务变得以利润为导向，可能导致质量下降和消费者成本上升。 文章指出，养老基金需要约 7%的年回报率才能维持偿付能力，这促使它们投资私募股权（PE），而 PE 往往导致削减成本和服务质量下降。

hackernews · NoRagrets · 5月27日 12:00 · [社区讨论](https://news.ycombinator.com/item?id=48292941)

**背景**: 私募股权公司从养老基金等机构投资者筹集资金，通常利用杠杆收购公司。它们旨在改善后出售获利，有时会优先考虑短期收益。养老基金投资私募股权（PE）以达到回报目标，但这种模式可能给关键服务的提供带来压力。

**社区讨论**: 评论者指出具有讽刺意味的是，养老基金推动了私募股权（PE），将价值从当前生活水平转移到退休金。一些人将之比作古罗马克拉苏的消防队，而另一些人则哀叹 PE 收购小企业时对社会资本的掠夺。

**标签**: `#private equity`, `#economy`, `#pensions`, `#essential services`, `#investment`

---

<a id="item-6"></a>
## [SQLite 引入 AGENTS.md 政策拒绝 AI 代理代码](https://simonwillison.net/2026/May/27/sqlite-agents/#atom-everything) ⭐️ 8.0/10

SQLite 在其仓库中添加了 AGENTS.md 文件，声明不接受代理代码贡献，但欢迎错误报告和文档补丁。此外，该项目还创建了一个单独的错误论坛来处理大量 AI 生成的错误报告。 该政策为开源项目治理 AI 生成的贡献树立了明确先例，直接回应了许多项目面临的低质量 AI 提交挑战。它可能促使其他重大项目采用类似指导方针。 AGENTS.md 还要求拉取请求事先获得同意并附上法律文件，最新提交删除了“（目前）”一词以强化对代理代码的拒绝。SQLite 论坛被 AI 错误报告淹没，因此创建了由 D. Richard Hipp 维护的专用错误论坛。

rss · Simon Willison · 5月27日 23:44

**背景**: 代理编码指使用自主 AI 代理在最少人工干预下规划、编写、测试和修改代码。SQLite 是一个广泛部署的嵌入式数据库引擎，以其保守的开发实践著称。该政策阐明了项目对 AI 生成代码的立场，区分了自动化代码贡献和人工审查的错误报告。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cloud.google.com/discover/what-is-agentic-coding">What is agentic coding? How it works and use cases | Google Cloud</a></li>

</ul>
</details>

**标签**: `#sqlite`, `#AI agents`, `#open-source governance`, `#software engineering`

---

<a id="item-7"></a>
## [AI 安全报告让 curl 维护者不堪重负](https://simonwillison.net/2026/May/26/the-pressure/#atom-everything) ⭐️ 8.0/10

curl 维护者 Daniel Stenberg 报告说，项目目前面临的安全报告数量是 2024 年的 4 到 5 倍，是 2025 年的两倍，平均每天超过一份报告，这些报告都非常详细，而且往往是 AI 辅助生成的。 这一激增凸显了 AI 生成的安全研究给开源维护者带来的越来越大的压力，威胁到维护者的福祉和项目的可持续性，尤其是像 curl 这样的关键基础设施。 尽管报告数量激增，但发现的漏洞几乎都是低或中等严重性，最后一个高严重性 CVE (CVE-2023-38545) 发布于 2023 年 10 月。

rss · Simon Willison · 5月26日 23:48

**背景**: curl 是一个广泛使用的命令行工具和库，用于通过 URL 传输数据，支持 HTTP、FTP 等多种协议。它是无数系统和应用中的关键组件。该项目由 Daniel Stenberg 领导的一个小团队维护，由于 AI 辅助安全报告的涌入，他现在面临着前所未有的心理压力和工作生活失衡。

**标签**: `#curl`, `#open source`, `#security`, `#AI`, `#maintenance`

---

<a id="item-8"></a>
## [NASA 公布月球基地计划细节，授予着陆器合同](https://www.bbc.com/news/articles/c39228nxyr4o) ⭐️ 8.0/10

NASA 公布了月球基地计划的新细节，目标是在 2032 年前在南极建成一个半永久性前哨站。多家公司，包括 Blue Origin、Intuitive Machines 和 Astrobotic，已获得建造着陆器、漫游车和通信设备的合同。 这一计划代表着向月球持续有人驻留迈出的具体一步，对资源开采和火星任务具有重要意义。然而，SpaceX 载人登月着陆器的延误以及来自中国的竞争增加了政治紧迫性。 该计划包括在 2029 年前进行 25 次发射，运送 4 吨货物，使用机器人着陆器和跳跃无人机勘测南极。基地将由核反应堆和太阳能联合供电。

telegram · zaihuapd · 5月27日 03:08

**背景**: NASA 的 Artemis 计划旨在让人类重返月球并建立可持续的存在。月球基地将作为未来火星任务的中转站。由于恶劣环境和漫长的月夜，核能被认为是长期月球操作所必需的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bbc.com/future/article/20240417-the-nuclear-reactors-that-could-power-moon-bases">The nuclear reactors that could power bases on the Moon</a></li>
<li><a href="https://phys.org/news/2025-03-firm-moon-drill-rovers-drone.html">US firm targets Moon landing with drill, rovers, hopping drone</a></li>

</ul>
</details>

**标签**: `#NASA`, `#lunar base`, `#space exploration`, `#Blue Origin`, `#SpaceX`

---

<a id="item-9"></a>
## [7-Zip 高危堆溢出漏洞已在 26.01 版本修复](https://socprime.com/blog/cve-2026-48095-7-zip-heap-overflow-flaw/) ⭐️ 8.0/10

7-Zip 的 NTFS 处理程序中存在一个高危堆缓冲区写入溢出漏洞（CVE-2026-48095），攻击者可通过特制压缩文件执行任意代码。该漏洞已在 2026 年 4 月 27 日发布的 26.01 版本中修复。 7-Zip 是全球广泛使用的文件压缩工具，此漏洞可通过基于签名的回退逻辑触发，即使带有 .7z 或 .zip 等常见扩展名的压缩文件也可能被伪装利用。用户应立即更新以防远程代码执行或应用崩溃。 该漏洞位于 NTFS 归档处理程序（NTFSHandler.cpp）中，解析特制 NTFS 镜像时会导致堆缓冲区溢出。漏洞 CVSS 评分为 8.8，影响 7-Zip 26.00 及之前所有版本，由 GitHub 安全实验室的 Jaroslav Lobačevski 发现。

telegram · zaihuapd · 5月27日 08:01

**背景**: 堆缓冲区溢出发生在程序向堆中已分配的内存区域之外写入数据时，可能覆盖关键数据结构。攻击者可利用此漏洞执行任意代码或导致应用崩溃。7-Zip 使用基于签名的回退机制：当根据文件扩展名的处理程序失败时，会按文件签名尝试所有剩余处理程序。这使得伪装成 .7z 或 .zip 文件的特制 NTFS 镜像能够到达存在漏洞的 NTFS 处理程序。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://securitylab.github.com/advisories/GHSL-2026-140_7-Zip/">GHSL-2026-140: Heap Buffer Write Overflow in 7-Zip | GitHub Security Lab</a></li>
<li><a href="https://blog.gridinsoft.com/7-zip-cve-2026-48095/">7-Zip CVE-2026-48095: Update to 26.01 and Handle Archives Safely</a></li>
<li><a href="https://socprime.com/blog/cve-2026-48095-7-zip-heap-overflow-flaw/">CVE-2026-48095: 7-Zip Heap Overflow Flaw</a></li>

</ul>
</details>

**标签**: `#security`, `#vulnerability`, `#CVE`, `#7-Zip`, `#heap overflow`

---

<a id="item-10"></a>
## [长鑫科技科创板 IPO 过会，拟募资 295 亿元](https://static.sse.com.cn/stock/disclosure/announcement/c/202605/000001_20260527_SPLE.pdf) ⭐️ 8.0/10

长鑫科技在科创板 IPO 获得上市委会议通过，拟募资 295 亿元，用于 DRAM 制造升级和前瞻技术研发。 此次 IPO 是中国本土 DRAM 行业的一个重要里程碑，将为存储器制造升级提供巨额资金，减少对外部供应商的依赖，也体现了国家对半导体自主可控的持续支持。 募集资金将用于存储器晶圆制造量产线技术升级、DRAM 技术升级和前瞻技术研发。该公司是中国领先的 DRAM 制造商之一。

telegram · zaihuapd · 5月27日 09:12

**背景**: DRAM（动态随机存取存储器）是一种易失性存储器，广泛用作计算机等设备的主存。全球 DRAM 市场目前由三星、SK 海力士和美光主导。中国一直致力于发展本土 DRAM 生产以减少进口依赖，长鑫科技（CXMT）等公司是其中的先锋。科创板是上海证券交易所专门支持高科技和创新企业的板块。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dynamic_random-access_memory">Dynamic random-access memory - Wikipedia</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#DRAM`, `#IPO`, `#China technology`, `#memory manufacturing`

---