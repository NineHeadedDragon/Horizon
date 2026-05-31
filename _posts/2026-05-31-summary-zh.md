---
layout: default
title: "Horizon Summary: 2026-05-31 (ZH)"
date: 2026-05-31
lang: zh
---

> 从 36 条内容中筛选出 13 条重要资讯。

---

1. [vLLM v0.22.0 发布：DeepSeek V4 成熟、MRv2 进展、Rust 前端](#item-1) ⭐️ 8.0/10
2. [领域专长依然是开发者的真正护城河](#item-2) ⭐️ 8.0/10
3. [AV2 v1.0 规范发布，效率提升 20-30%](#item-3) ⭐️ 8.0/10
4. [微软 Office 2019/2021 Mac 版将于 2026 年变为只读模式](#item-4) ⭐️ 8.0/10
5. [请不要用“AI vibe”毁掉这个软件](#item-5) ⭐️ 8.0/10
6. [埃森哲以 12 亿美元收购 Ookla 以增强网络 AI 能力](#item-6) ⭐️ 8.0/10
7. [OpenBSD 发布新 rsync 实现 openrsync](#item-7) ⭐️ 8.0/10
8. [Voxel Space：复古高度图渲染技术](#item-8) ⭐️ 8.0/10
9. [Zig ELF 链接器实现快速增量链接](#item-9) ⭐️ 8.0/10
10. [OpenRouter 完成 1.13 亿美元 B 轮融资](#item-10) ⭐️ 8.0/10
11. [Anthropic 详解 Claude 跨产品沙箱技术](#item-11) ⭐️ 8.0/10
12. [在浏览器中使用 Pyodide 和服务人员运行 Python ASGI 应用](#item-12) ⭐️ 8.0/10
13. [FROST 攻击利用 SSD 计时窥探浏览活动](#item-13) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [vLLM v0.22.0 发布：DeepSeek V4 成熟、MRv2 进展、Rust 前端](https://github.com/vllm-project/vllm/releases/tag/v0.22.0) ⭐️ 8.0/10

vLLM v0.22.0 发布，包含来自 230 位贡献者的 459 次提交，对 DeepSeek V4 支持进行了重大加固，推动 Model Runner V2 成为默认选项，并增加了实验性的 Rust 前端。 此版本显著提高了 DeepSeek V4 等前沿模型的推理效率，通过 NVFP4 融合 MoE 和批次不变推理等功能实现了高达 28.9% 的延迟改进，惠及更广泛的 LLM 服务生态系统。 DeepSeek V4 获得了专用包、NVFP4 融合 MoE 支持、CUDA 图改进和 MTP 推测解码；Model Runner V2 获得了 Qwen3 稠密模型的选择器和休眠模式权重重载；Rust 前端增加了用于数据并行服务的 DP Supervisor。

github · khluu · 5月29日 10:28

**背景**: vLLM 是一个用于大语言模型的高吞吐量、内存高效的推理和服务引擎。NVFP4 是一种用于量化的 4 位浮点格式。MTP（多令牌预测）是一种推测解码方法，其中目标模型本身预测多个令牌，无需单独的草稿模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/latest/features/speculative_decoding/mtp/">MTP (Multi-Token Prediction) - vLLM</a></li>
<li><a href="https://www.kad8.com/ai/megamoe-megakernel-architecture-optimizing-deepseek-v4-llm-performance/">MegaMoE MegaKernel Architecture: Optimizing DeepSeek-V4 LLM Performance · KAD</a></li>
<li><a href="https://docs.vllm.ai/en/latest/api/vllm/model_executor/layers/fused_moe/experts/trtllm_nvfp4_moe/">trtllm_ nvfp 4 _ moe - vLLM</a></li>

</ul>
</details>

**标签**: `#vllm`, `#LLM inference`, `#DeepSeek`, `#Rust`, `#Model Runner`

---

<a id="item-2"></a>
## [领域专长依然是开发者的真正护城河](https://www.brethorsting.com/blog/2026/05/domain-expertise-has-always-been-the-real-moat/) ⭐️ 8.0/10

这一见解很重要，因为随着 AI 的发展，理解和验证领域特定需求的能力变得比原始编码能力更为关键。它改变了软件开发者的职业发展建议和招聘标准，使其更重视领域专长。 文章和社区评论强调，验证生成代码及其输出是否正确需要深厚的领域知识，而目前 AI 缺乏这一点。例如，金融管理系统和海洋数据应用需要多年的领域经验。

hackernews · aaronbrethorst · 5月30日 20:40 · [社区讨论](https://news.ycombinator.com/item?id=48340411)

**社区讨论**: 社区普遍认同这一论点，并补充了领域专长证明其价值的个人实例。多位评论者指出，验证输出的能力与生成输出的能力是不同的，而将编码技能与领域知识结合会使开发者变得不可或缺。

**标签**: `#domain expertise`, `#software engineering`, `#AI`, `#developer skills`, `#competitive advantage`

---

<a id="item-3"></a>
## [AV2 v1.0 规范发布，效率提升 20-30%](https://av2.aomedia.org/) ⭐️ 8.0/10

开放媒体联盟（AOMedia）发布了 AV2 视频编解码器的最终 v1.0 规范，声称压缩效率比 AV1 提升约 20-30%。 AV2 代表了下一代开源视频压缩技术，但由于需要专门的硬件和尚未解决的专利许可问题，实际部署预计要等到 2028 年左右。 目前的 AV2 参考编码器在良好硬件上运行速度约为每秒 1 帧，硬件加速芯片预计要到 2028 年才能问世，而流媒体广泛采用可能要等到 2030 年左右。

hackernews · ksec · 5月30日 21:46 · [社区讨论](https://news.ycombinator.com/item?id=48340910)

**背景**: 视频编解码器压缩数字视频以实现高效存储和流媒体传输。AV1 由 AOMedia 于 2018 年发布，已被广泛使用，但面临专利挑战。AV2 旨在以更好的压缩效率改进 AV1，但计算复杂度更高。硬件支持和法律明确性的时间表仍然是主要障碍。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnx-software.com/2025/11/21/aomedia-av2-open-video-codec-release-nears-delivers-around-40-bandwidth-reduction/">AOMedia AV 2 open video codec release nears... - CNX Software</a></li>
<li><a href="https://www.fastpix.io/blog/av2-vs-av1-a-comprehensive-comparison-of-next-gen-video-codecs">AV 2 vs AV 1 : Next-Gen Video Codec Comparison</a></li>

</ul>
</details>

**社区讨论**: 社区评论持谨慎乐观态度：虽然效率提升显著，但许多人指出实际应用的时间线很长（硬件约 2028 年，主流约 2030 年）以及潜在的专利诉讼。一些人对 AVIF 图像格式的改进感兴趣，而另一些人则对“免版税”的说法表示怀疑，因为围绕 AV1 的诉讼仍在进行。

**标签**: `#video codec`, `#AV2`, `#compression`, `#open standards`, `#patent licensing`

---

<a id="item-4"></a>
## [微软 Office 2019/2021 Mac 版将于 2026 年变为只读模式](https://consumerrights.wiki/w/Microsoft_Office_2019_and_2021_for_Mac_view-only_conversion_(2026)) ⭐️ 8.0/10

微软计划在 2026 年将 Office 2019 和 2021 for Mac 的永久许可证转换为只读模式，用户若无订阅将无法编辑文档。 这一变化削弱了被宣传为一次性购买的永久许可证的价值，可能违反多个国家的消费者权益法，并促使用户转向 Microsoft 365 订阅。 该转换仅适用于 Office 2019 和 2021 的 Mac 版本；只读模式允许打开和打印文件，但不能编辑。具体强制执行日期预计在 2026 年。

hackernews · antipurist · 5月30日 23:26 · [社区讨论](https://news.ycombinator.com/item?id=48341578)

**背景**: 永久许可证是一种一次性购买，传统上允许无限期使用软件。微软一直在推广其基于订阅的 Microsoft 365 服务。只读模式是一种许可证强制执行机制，当检测不到有效许可证时会限制功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://learn.microsoft.com/en-us/microsoft-365-apps/licensing-activation/overview-viewer-mode">Overview of viewer mode for Microsoft 365 Apps - Microsoft 365 Apps | Microsoft Learn</a></li>
<li><a href="https://trustwrites.com/en/life-office-licensing-2025-en/">《Life Notes》Is Perpetual Office Really Going Away? Microsoft's Policy ...</a></li>

</ul>
</details>

**社区讨论**: 评论者表示愤怒，认为这一变化违反了消费者保障（例如在澳大利亚），并可能导致法律诉讼。一些人建议改用 LibreOffice，而另一些人指出盗版版本可能更尊重原始购买条款。

**标签**: `#Microsoft Office`, `#software licensing`, `#consumer rights`, `#Mac`, `#subscription model`

---

<a id="item-5"></a>
## [请不要用“AI vibe”毁掉这个软件](https://github.com/RsyncProject/rsync/issues/929) ⭐️ 8.0/10

rsync 社区强烈反对在软件中集成 AI 的任何提议，用户认为此举毫无必要且可能损害稳定性。 这场争论反映了开源项目中，在维持既有可靠工具与采纳潮流 AI 功能之间的紧张关系，可能影响维护者如何平衡创新与用户信任。 该 GitHub issue 已有 122 条评论，参与度很高，部分用户明确建议创建分支来开发带 AI 的版本，而不是修改原始 rsync。

hackernews · justdotJS · 5月31日 03:16 · [社区讨论](https://news.ycombinator.com/item?id=48342705)

**背景**: rsync 是一款广泛使用的命令行工具，用于文件同步和数据传输，以其可靠性和高效性著称。该软件历史悠久，拥有大量依赖其稳定性的用户。

**社区讨论**: 评论显示了对 AI 集成的强烈反对意见，用户引用 GPL 保修免责声明，认为 AI 对 rsync 的核心功能毫无必要，并对维护者竟然考虑此事表示沮丧。部分用户建议为 AI 功能建立独立分支，另一些则批评原始 issue 的措辞。

**标签**: `#rsync`, `#AI integration`, `#software maintenance`, `#open-source debate`, `#community reaction`

---

<a id="item-6"></a>
## [埃森哲以 12 亿美元收购 Ookla 以增强网络 AI 能力](https://newsroom.accenture.com/news/2026/accenture-to-acquire-ookla-to-strengthen-network-intelligence-and-experience-with-data-and-ai-for-enterprises) ⭐️ 8.0/10

埃森哲于 2026 年 3 月宣布以 12 亿美元收购 Ookla，后者是 Speedtest 和 Downdetector 的母公司。该交易旨在将 Ookla 的网络数据与埃森哲的 AI 能力相结合，为企业提供增强的网络智能。 此次收购凸显了网络数据和智能在 AI 时代日益增长的价值，尤其是对电信和企业客户而言。它使埃森哲能够提供更深入的网络优化洞察，可能重塑 CSP 和企业管理 5G 和 Wi-Fi 网络的方式。 Ookla 的数据平台每月包含超过 2.5 亿次消费者发起的测试，以及受控的驾车、步行和嵌入式测试。此次收购还将 Downdetector、Ekahau 和 RootMetrics 等品牌纳入埃森哲旗下。

hackernews · Garbage · 5月30日 16:28 · [社区讨论](https://news.ycombinator.com/item?id=48337987)

**背景**: Ookla 最著名的是 Speedtest.net（一款广泛使用的互联网速度测试服务）和 Downdetector（一个实时故障监控平台）。电信运营商每年支付高额费用购买 Ookla 聚合的网络性能数据，以识别覆盖缺口并改善服务质量。埃森哲此前已通过收购 Umlaut 拥有网络咨询业务，因此这笔交易是其数据资产的战略扩展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ookla.com/about">About | Ookla</a></li>
<li><a href="https://en.wikipedia.org/wiki/Downdetector">Downdetector - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，这笔交易本质上是一次数据收购，因为电信运营商每年为 Ookla 的洞察支付六位数金额。一些人因产品看似简单而对 12 亿美元的估值感到惊讶，而另一些人则强调了 Ookla 数据变现的深度及其竞争地位。少数人提到了像 nettfart.no 这样的替代工具。

**标签**: `#acquisition`, `#network intelligence`, `#data monetization`, `#telecommunications`, `#AI`

---

<a id="item-7"></a>
## [OpenBSD 发布新 rsync 实现 openrsync](https://github.com/kristapsdz/openrsync) ⭐️ 8.0/10

OpenBSD 团队发布了 openrsync，这是 rsync 文件同步工具的一个新实现，代码托管在 GitHub 上。 作为原 Samba 维护的 rsync 的替代品，openrsync 提供了更简洁且可能更安全的代码库，考虑到主 rsync 代码库因大量提交而出现回归问题，这一点尤为重要。 Openrsync 目前缺少原 rsync 的某些功能，例如完全保留所有文件元数据或处理复杂的 rsync 选项；它最初是作为一个 RPKI 验证器项目的一部分开发的。

hackernews · sph · 5月30日 10:51 · [社区讨论](https://news.ycombinator.com/item?id=48334854)

**背景**: rsync 是一款广泛使用的开源工具，用于高效地同步本地或网络上的文件，以其差异传输算法著称。openrsync 是 OpenBSD 团队从头实现的版本，强调安全性和代码简洁性，在许多情况下可以作为原 rsync 的直接替代品。

**社区讨论**: 社区评论表达了谨慎乐观的态度：部分用户报告成功使用，但指出某些功能缺失，如对 --rsync-path 的正确处理；另一些用户则因原 rsync 近期出现回归问题而欢迎该项目。还有评论提到了 Gokrazy 团队的 Go 语言实现作为另一个替代方案。

**标签**: `#openrsync`, `#rsync`, `#OpenBSD`, `#file synchronization`, `#open-source`

---

<a id="item-8"></a>
## [Voxel Space：复古高度图渲染技术](https://s-macke.github.io/VoxelSpace/) ⭐️ 8.0/10

一篇技术文章解释了 1992 年游戏《Comanche》中使用的基于高度图的渲染算法，社区成员分享了实现代码和见解。 该算法在当时具有开创性，能在有限硬件上实现流畅的 3D 地形渲染，而此次讨论让这一技术在现代游戏开发者和历史爱好者中保持活力。 该技术使用高度图（灰度图像）存储高程，然后从远到近逐列渲染颜色，类似于对高度场进行光线投射。它并非真正的体素渲染，因为缺乏完整的体积数据。

hackernews · davikr · 5月30日 14:25 · [社区讨论](https://news.ycombinator.com/item?id=48336564)

**背景**: 高度图是一种灰度图像，每个像素的亮度代表地形高程。Voxel Space 算法从视点发出射线，沿每条射线采样高度图，从而渲染高度图，产生 2.5D 效果。它是 20 世纪 90 年代初实时地形渲染的一个里程碑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Heightmap">Heightmap - Wikipedia</a></li>
<li><a href="https://observablehq.com/@ehouais/heightmap-rendering-using-a-floorcasting-algorithm">Heightmap rendering using a floorcasting algorithm / Philippe Deschaseaux | Observable</a></li>

</ul>
</details>

**社区讨论**: 评论澄清该技术基于高度图，并非真正的体素渲染，但放在 1992 年仍令人印象深刻。有用户分享了使用原始地图的 C++重新实现，有人将其移植到 AGS 引擎，还提出了一个用于软件质量的测试隐喻（'油罐假期测试'）。

**标签**: `#graphics`, `#rendering`, `#voxel`, `#game development`, `#history`

---

<a id="item-9"></a>
## [Zig ELF 链接器实现快速增量链接](https://ziglang.org/devlog/2026/#2026-05-30) ⭐️ 8.0/10

Zig 编程语言的 ELF 链接器得到了改进，支持快速增量链接，大幅缩短了开发过程中的编译时间。 这一改进使 Zig 更加接近 C 语言的全面替代品，开发者能够以解释型语言的速度进行迭代，同时保持类似 C 的性能。 增量链接预计与链接时优化（LTO）不兼容，因此主要适用于开发构建而非发布构建。

hackernews · kristoff_it · 5月30日 17:29 · [社区讨论](https://news.ycombinator.com/item?id=48338673)

**背景**: Zig 是一种通用系统编程语言，旨在作为 C 语言的现代改进。ELF（可执行与可链接格式）是 Linux 系统上的标准二进制格式。链接器将编译后的目标文件合并成可执行文件；增量链接重用之前链接的输出以加速后续构建。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Executable_and_Linkable_Format">Executable and Linkable Format - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员对此充满热情，有人表示 Zig 将“成为 C 语言的替代品”，实现类似 JavaScript 或 Python 的迭代速度。另一位用户因 Zig 更优的构建系统而选择它而非 Rust 用于一个转译项目。也有人担忧增量链接可能与 LTO 互斥。

**标签**: `#Zig`, `#linker`, `#ELF`, `#systems programming`, `#compiler`

---

<a id="item-10"></a>
## [OpenRouter 完成 1.13 亿美元 B 轮融资](https://openrouter.ai/announcements/series-b) ⭐️ 8.0/10

OpenRouter 宣布完成 1.13 亿美元的 B 轮融资，用于扩展其提供统一 API 以访问多个大语言模型的代理服务。 这笔巨额投资验证了 LLM 接入的代理模式，凸显了市场对简化多模型集成的强烈需求，并可能加速 OpenRouter 作为关键基础设施玩家的增长。 OpenRouter 在模型提供商价格之上收取 5%的附加费，并提供计费上限等功能以防止意外成本。融资后公司仍由创始人领导并控制。

hackernews · freeCandy · 5月30日 17:27 · [社区讨论](https://news.ycombinator.com/item?id=48338660)

**背景**: OpenRouter 是一个代理服务，提供单一 API 端点以访问来自不同提供商的多种大语言模型，简化了开发者的集成工作。它与其他 API 聚合解决方案以及 LiteLLM 等自托管代理竞争。B 轮融资将用于扩展基础设施和支持更多模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://apify.com/apify/openrouter">OpenRouter · Apify</a></li>
<li><a href="https://grokipedia.com/page/Openrouter-proxy">Openrouter-proxy</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的评论者称赞 OpenRouter 在尝试模型时的低摩擦和有用的计费上限，但有些人质疑 5%的附加费以及名称中的“Open”（开放），因为它不是开源的。联合创始人回应说，公司仍由创始人领导，专注于为爱好者构建优秀产品。

**标签**: `#AI`, `#LLM`, `#funding`, `#infrastructure`, `#API`

---

<a id="item-11"></a>
## [Anthropic 详解 Claude 跨产品沙箱技术](https://simonwillison.net/2026/May/30/how-we-contain-claude/#atom-everything) ⭐️ 8.0/10

Anthropic 发布了一篇详细的博文，解释了用于 Claude.ai、Claude Code 和 Claude Cowork 的沙箱技术，包括使用 gVisor、Seatbelt、Bubblewrap 和完整虚拟机。 这解决了 AI 代理沙箱普遍缺乏透明度的问题，帮助用户和开发者了解 Anthropic 产品的安全边界，建立信任。 Claude.ai 使用 Google 开发的 gVisor 容器沙箱；Claude Code 在 macOS 上使用 Seatbelt，在 Linux 上使用 Bubblewrap；Claude Cowork 运行完整虚拟机，使用 Apple 的虚拟化框架或 Windows 上的 HCS。文章还提到了过去遗漏的风险，包括通过 api.anthropic.com/v1/files 的数据外泄向量。

rss · Simon Willison · 5月30日 21:36

**背景**: 沙箱技术将 AI 代理与主机系统隔离，防止未授权访问。gVisor 是 Google 开发的开源容器沙箱，在用户空间实现 Linux 系统调用以提供安全隔离。Seatbelt 是 macOS 内置的沙箱框架，可限制文件系统和网络访问。Bubblewrap 是轻量级 Linux 沙箱工具，被 Flatpak 等容器系统使用。这些技术强制执行文件系统、网络和进程能力的严格边界。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gvisor.dev/">The Container Security Platform - gVisor</a></li>
<li><a href="https://code.claude.com/docs/en/sandboxing">Sandboxing - Claude Code Docs</a></li>
<li><a href="https://github.com/containers/bubblewrap">GitHub - containers/ bubblewrap : Low-level unprivileged sandboxing...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#sandboxing`, `#Claude`, `#security`, `#Anthropic`

---

<a id="item-12"></a>
## [在浏览器中使用 Pyodide 和服务人员运行 Python ASGI 应用](https://simonwillison.net/2026/May/30/pyodide-asgi-browser/#atom-everything) ⭐️ 8.0/10

Simon Willison 成功演示了通过将 Pyodide 与服务工作者结合，在浏览器中运行 Python ASGI 应用（包括 Datasette），这改进了他之前使用 Web Worker 的方法，后者无法执行<script>标签中的 JavaScript。 这项技术使更丰富的 Python Web 应用能够在没有服务器的情况下完全在客户端运行，可能扩大 Datasette 等工具的应用范围，并允许在浏览器中运行更复杂的 Python 应用。 该方法使用服务工作者拦截网络请求，并提供通过 Pyodide 在 WebAssembly 中运行的 Python ASGI 应用生成的响应，克服了 Web Worker 中<script>标签无法执行的限制。

rss · Simon Willison · 5月30日 21:02

**背景**: Pyodide 是将 CPython 移植到 WebAssembly/Emscripten 的项目，使 Python 能在浏览器中运行。ASGI（异步服务器网关接口）是构建异步 Python Web 应用的标准，是 WSGI 的继任者。服务工作者是浏览器在后台独立于网页运行的脚本，支持拦截网络请求等功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pyodide.org/en/stable/console.html">pyodide .org/en/stable/console.html</a></li>
<li><a href="https://en.wikipedia.org/wiki/Asynchronous_Server_Gateway_Interface">Asynchronous Server Gateway Interface - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Pyodide`, `#ASGI`, `#WebAssembly`, `#Service Workers`, `#Datasette`

---

<a id="item-13"></a>
## [FROST 攻击利用 SSD 计时窥探浏览活动](https://futurism.com/future-society/websites-spying-solid-state-drive) ⭐️ 8.0/10

研究人员披露了一种名为 FROST 的新型侧信道攻击，通过浏览器 Origin Private File System (OPFS)测量 SSD 读写时间，推断用户同时访问的网站或使用的应用。该攻击对网站识别的准确率达到 88.95%，对应用检测的准确率达到 95.83%，无需安装软件或用户交互。 此次攻击揭示了现代浏览器中一种新的隐私漏洞，任何恶意网站都可能未经许可窥探用户的浏览习惯。它挑战了 OPFS 是安全存储端点的假设，如果不加以缓解，可能会影响数百万用户。 该攻击已在 macOS 和 Linux 上进行了测试，但研究人员认为 Windows 同样易受攻击。使用后及时关闭浏览器标签页可降低风险，因为攻击依赖于多个打开标签页或应用同时访问 SSD 引起的时间变化。

telegram · zaihuapd · 5月31日 01:55

**背景**: 侧信道攻击利用系统间接泄露的信息（如时间、功耗或电磁辐射）来推断敏感数据。Origin Private File System (OPFS)是一种浏览器 API，为 Web 应用提供快速、针对来源的虚拟文件系统，但会无意中暴露因 SSD 访问模式导致的时间差异。FROST 攻击利用这些时间差异来推断哪些其他网站或应用正在积极使用存储。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Side-channel_attack">Side-channel attack - Wikipedia</a></li>
<li><a href="https://hothardware.com/news/frost-side-channel-attack-turns-ssd-activity-into-a-new-browser-privacy-nightmare">FROST Side-Channel Attack Turns SSD Activity Into A New Browser Privacy Nightmare | HotHardware</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/File_System_API/Origin_private_file_system">Origin private file system - Web APIs | MDN</a></li>

</ul>
</details>

**标签**: `#security`, `#side-channel attack`, `#browser privacy`, `#SSD`, `#OPFS`

---